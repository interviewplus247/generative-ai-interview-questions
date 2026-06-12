# Generative AI Interview Questions & Answers

<p align="center">
  <img src="images/image1.png" alt="Generative AI Interview Questions & Answers">
</p>

> A curated list of Generative AI interview questions covering Knowledge Bases, RAG, Embeddings, Vector Databases, Semantic Search, Python, SQL, and Enterprise Data Handling — from basic to advanced, plus real-world scenario-based questions.

---

### Table of Contents

<details open>
<summary>
Hide/Show table of contents
</summary>

| No. | Questions |
| --- | --------- |
|     | **Knowledge Base & Data Preparation** |
| 1 | [What is a Knowledge Base in a GenAI system?](#what-is-a-knowledge-base-in-a-genai-system) |
| 2 | [Why is data preparation important for LLM applications?](#why-is-data-preparation-important-for-llm-applications) |
| 3 | [What types of enterprise documents have you worked with?](#what-types-of-enterprise-documents-have-you-worked-with) |
| 4 | [How do you clean noisy data?](#how-do-you-clean-noisy-data) |
| 5 | [What is data normalization?](#what-is-data-normalization) |
| 6 | [How do you handle duplicate records?](#how-do-you-handle-duplicate-records) |
| 7 | [What is metadata and why is it important?](#what-is-metadata-and-why-is-it-important) |
| 8 | [How would you prepare PDF documents for a chatbot?](#how-would-you-prepare-pdf-documents-for-a-chatbot) |
| 9 | [What challenges arise with scanned PDFs?](#what-challenges-arise-with-scanned-pdfs) |
| 10 | [What is OCR?](#what-is-ocr) |
| 11 | [How would you process documents from SharePoint?](#how-would-you-process-documents-from-sharepoint) |
| 12 | [How do you extract tables from PDFs?](#how-do-you-extract-tables-from-pdfs) |
| 13 | [How do you maintain document versioning?](#how-do-you-maintain-document-versioning) |
| 14 | [How do you identify stale knowledge?](#how-do-you-identify-stale-knowledge) |
| 15 | [How would you handle multilingual documents?](#how-would-you-handle-multilingual-documents) |
| 16 | [What data quality checks do you perform?](#what-data-quality-checks-do-you-perform) |
| 17 | [How do you measure knowledge base completeness?](#how-do-you-measure-knowledge-base-completeness) |
| 18 | [Explain chunking and its importance](#explain-chunking-and-its-importance) |
| 19 | [What chunk size would you choose and why?](#what-chunk-size-would-you-choose-and-why) |
| 20 | [How do you handle document updates in a knowledge base?](#how-do-you-handle-document-updates-in-a-knowledge-base) |
|     | **Retrieval Augmented Generation (RAG)** |
| 21 | [What is RAG?](#what-is-rag) |
| 22 | [Why is RAG preferred over fine-tuning in many cases?](#why-is-rag-preferred-over-fine-tuning-in-many-cases) |
| 23 | [Explain the RAG workflow](#explain-the-rag-workflow) |
| 24 | [What problem does RAG solve?](#what-problem-does-rag-solve) |
| 25 | [What happens if retrieval quality is poor?](#what-happens-if-retrieval-quality-is-poor) |
| 26 | [Describe indexing and retrieval stages](#describe-indexing-and-retrieval-stages) |
| 27 | [What is hybrid search?](#what-is-hybrid-search) |
| 28 | [What is the difference between keyword search and semantic search?](#what-is-the-difference-between-keyword-search-and-semantic-search) |
| 29 | [What is reranking?](#what-is-reranking) |
| 30 | [How do you improve retrieval accuracy?](#how-do-you-improve-retrieval-accuracy) |
| 31 | [What is context window limitation?](#what-is-context-window-limitation) |
| 32 | [How does chunking affect RAG performance?](#how-does-chunking-affect-rag-performance) |
| 33 | [Explain Top-K retrieval](#explain-top-k-retrieval) |
| 34 | [What is context injection?](#what-is-context-injection) |
| 35 | [What are hallucinations and how does RAG reduce them?](#what-are-hallucinations-and-how-does-rag-reduce-them) |
| 36 | [How would you evaluate a RAG system?](#how-would-you-evaluate-a-rag-system) |
| 37 | [What is the difference between Precision and Recall in retrieval?](#what-is-the-difference-between-precision-and-recall-in-retrieval) |
| 38 | [What metrics would you use for RAG evaluation?](#what-metrics-would-you-use-for-rag-evaluation) |
| 39 | [How do you reduce latency in RAG?](#how-do-you-reduce-latency-in-rag) |
| 40 | [What are common failure scenarios in RAG?](#what-are-common-failure-scenarios-in-rag) |
|     | **Embeddings** |
| 41 | [What are embeddings?](#what-are-embeddings) |
| 42 | [Why do we need embeddings?](#why-do-we-need-embeddings) |
| 43 | [Explain vector representation](#explain-vector-representation) |
| 44 | [What is semantic similarity?](#what-is-semantic-similarity) |
| 45 | [How are embeddings generated?](#how-are-embeddings-generated) |
| 46 | [What is the difference between keyword search and embedding search?](#what-is-the-difference-between-keyword-search-and-embedding-search) |
| 47 | [What is cosine similarity?](#what-is-cosine-similarity) |
| 48 | [Why are embeddings high-dimensional vectors?](#why-are-embeddings-high-dimensional-vectors) |
| 49 | [What happens if two documents have similar embeddings?](#what-happens-if-two-documents-have-similar-embeddings) |
| 50 | [Explain Euclidean distance vs cosine similarity](#explain-euclidean-distance-vs-cosine-similarity) |
| 51 | [What embedding models have you used?](#what-embedding-models-have-you-used) |
| 52 | [How do embeddings capture meaning?](#how-do-embeddings-capture-meaning) |
| 53 | [Why might embedding quality vary?](#why-might-embedding-quality-vary) |
| 54 | [How would you evaluate an embedding model?](#how-would-you-evaluate-an-embedding-model) |
| 55 | [What are embedding drift issues?](#what-are-embedding-drift-issues) |
| 56 | [How do domain-specific embeddings help?](#how-do-domain-specific-embeddings-help) |
| 57 | [How would you handle millions of embeddings?](#how-would-you-handle-millions-of-embeddings) |
| 58 | [Explain dimensionality reduction](#explain-dimensionality-reduction) |
| 59 | [What is ANN (Approximate Nearest Neighbor)?](#what-is-ann-approximate-nearest-neighbor) |
| 60 | [How does ANN improve performance?](#how-does-ann-improve-performance) |
|     | **Vector Databases** |
| 61 | [What is a vector database?](#what-is-a-vector-database) |
| 62 | [Why can't traditional SQL databases efficiently handle vector search?](#why-cant-traditional-sql-databases-efficiently-handle-vector-search) |
| 63 | [Name some vector databases](#name-some-vector-databases) |
| 64 | [What is the difference between a vector DB and a relational DB?](#what-is-the-difference-between-a-vector-db-and-a-relational-db) |
| 65 | [What is vector indexing?](#what-is-vector-indexing) |
| 66 | [Explain HNSW indexing](#explain-hnsw-indexing) |
| 67 | [Explain FAISS](#explain-faiss) |
| 68 | [What is Pinecone?](#what-is-pinecone) |
| 69 | [What is ChromaDB?](#what-is-chromadb) |
| 70 | [What is Weaviate?](#what-is-weaviate) |
| 71 | [What is Milvus?](#what-is-milvus) |
| 72 | [How is similarity search performed?](#how-is-similarity-search-performed) |
| 73 | [Explain metadata filtering](#explain-metadata-filtering) |
| 74 | [What is Top-K nearest neighbor search?](#what-is-top-k-nearest-neighbor-search) |
| 75 | [How would you store document metadata?](#how-would-you-store-document-metadata) |
| 76 | [How do vector DBs scale?](#how-do-vector-dbs-scale) |
| 77 | [Explain indexing trade-offs](#explain-indexing-trade-offs) |
| 78 | [How would you handle billions of vectors?](#how-would-you-handle-billions-of-vectors) |
| 79 | [How do you update embeddings when documents change?](#how-do-you-update-embeddings-when-documents-change) |
| 80 | [How would you optimize vector search latency?](#how-would-you-optimize-vector-search-latency) |
|     | **Semantic Search** |
| 81 | [What is semantic search?](#what-is-semantic-search) |
| 82 | [How is semantic search different from keyword search?](#how-is-semantic-search-different-from-keyword-search) |
| 83 | [What problems does semantic search solve?](#what-problems-does-semantic-search-solve) |
| 84 | [Give a practical example of semantic search](#give-a-practical-example-of-semantic-search) |
| 85 | [Explain intent matching](#explain-intent-matching) |
| 86 | [What is query embedding?](#what-is-query-embedding) |
| 87 | [What is document embedding?](#what-is-document-embedding) |
| 88 | [Why can semantic search return relevant results without exact keywords?](#why-can-semantic-search-return-relevant-results-without-exact-keywords) |
| 89 | [What is query expansion?](#what-is-query-expansion) |
| 90 | [How do you improve semantic search relevance?](#how-do-you-improve-semantic-search-relevance) |
| 91 | [How do you evaluate semantic search quality?](#how-do-you-evaluate-semantic-search-quality) |
| 92 | [What role does reranking play?](#what-role-does-reranking-play) |
| 93 | [Explain hybrid search architecture](#explain-hybrid-search-architecture) |
| 94 | [How would you debug poor search results?](#how-would-you-debug-poor-search-results) |
|     | **Python** |
| 95 | [How do you read CSV files using Python?](#how-do-you-read-csv-files-using-python) |
| 96 | [What is the difference between a list and a tuple?](#what-is-the-difference-between-a-list-and-a-tuple) |
| 97 | [Explain dictionaries in Python](#explain-dictionaries-in-python) |
| 98 | [What is Pandas?](#what-is-pandas) |
| 99 | [What is NumPy?](#what-is-numpy) |
| 100 | [How do you handle missing values?](#how-do-you-handle-missing-values) |
| 101 | [How would you clean text data?](#how-would-you-clean-text-data) |
| 102 | [Explain regex](#explain-regex) |
| 103 | [How do you remove stop words?](#how-do-you-remove-stop-words) |
| 104 | [How do you tokenize text?](#how-do-you-tokenize-text) |
| 105 | [What libraries are used in NLP?](#what-libraries-are-used-in-nlp) |
| 106 | [How do you process large files?](#how-do-you-process-large-files) |
| 107 | [Explain generators](#explain-generators) |
| 108 | [What is a DataFrame?](#what-is-a-dataframe) |
| 109 | [Write Python code to remove duplicate rows](#write-python-code-to-remove-duplicate-rows) |
| 110 | [How would you create document chunks?](#how-would-you-create-document-chunks) |
| 111 | [How would you generate embeddings using Python?](#how-would-you-generate-embeddings-using-python) |
| 112 | [How would you call an LLM API?](#how-would-you-call-an-llm-api) |
| 113 | [How would you process 1 million documents efficiently?](#how-would-you-process-1-million-documents-efficiently) |
|     | **SQL** |
| 114 | [What is the difference between WHERE and HAVING?](#what-is-the-difference-between-where-and-having) |
| 115 | [What are joins?](#what-are-joins) |
| 116 | [What is the difference between INNER and LEFT JOIN?](#what-is-the-difference-between-inner-and-left-join) |
| 117 | [What is GROUP BY?](#what-is-group-by) |
| 118 | [What is a primary key?](#what-is-a-primary-key) |
| 119 | [How do you find duplicate records?](#how-do-you-find-duplicate-records) |
| 120 | [Explain window functions](#explain-window-functions) |
| 121 | [What is the difference between ROW_NUMBER and RANK?](#what-is-the-difference-between-rownumber-and-rank) |
| 122 | [What is a CTE?](#what-is-a-cte) |
| 123 | [What are indexes?](#what-are-indexes) |
| 124 | [How do indexes improve performance?](#how-do-indexes-improve-performance) |
| 125 | [Write SQL to find top 5 documents by access count](#write-sql-to-find-top-5-documents-by-access-count) |
| 126 | [How would you identify duplicate KB articles?](#how-would-you-identify-duplicate-kb-articles) |
| 127 | [How would you detect stale documents?](#how-would-you-detect-stale-documents) |
| 128 | [Explain query optimization](#explain-query-optimization) |
| 129 | [What causes full table scans?](#what-causes-full-table-scans) |
|     | **Enterprise Data Handling** |
| 130 | [What is the difference between structured and unstructured data?](#what-is-the-difference-between-structured-and-unstructured-data) |
| 131 | [What are examples of enterprise data sources?](#what-are-examples-of-enterprise-data-sources) |
| 132 | [What challenges exist in enterprise data?](#what-challenges-exist-in-enterprise-data) |
| 133 | [How would you process emails for a knowledge base?](#how-would-you-process-emails-for-a-knowledge-base) |
| 134 | [How would you process Jira tickets?](#how-would-you-process-jira-tickets) |
| 135 | [How would you process Confluence pages?](#how-would-you-process-confluence-pages) |
| 136 | [How would you process SharePoint documents?](#how-would-you-process-sharepoint-documents) |
| 137 | [How would you handle confidential data?](#how-would-you-handle-confidential-data) |
| 138 | [How would you implement data governance?](#how-would-you-implement-data-governance) |
| 139 | [How would you ensure data privacy?](#how-would-you-ensure-data-privacy) |
| 140 | [How would you mask sensitive information?](#how-would-you-mask-sensitive-information) |
| 141 | [How would you build a knowledge base from 10TB of enterprise data?](#how-would-you-build-a-knowledge-base-from-10tb-of-enterprise-data) |
| 142 | [How would you handle access-controlled documents?](#how-would-you-handle-access-controlled-documents) |
|     | **Scenario-Based Questions** |
| 143 | [Users say chatbot answers are irrelevant. How would you investigate?](#users-say-chatbot-answers-are-irrelevant-how-would-you-investigate) |
| 144 | [Retrieval accuracy dropped after a KB update. What would you check?](#retrieval-accuracy-dropped-after-a-kb-update-what-would-you-check) |
| 145 | [Search returns too many unrelated documents. How would you fix it?](#search-returns-too-many-unrelated-documents-how-would-you-fix-it) |
| 146 | [Embedding generation is taking too long. What would you do?](#embedding-generation-is-taking-too-long-what-would-you-do) |
| 147 | [Documents are duplicated across systems. How would you handle it?](#documents-are-duplicated-across-systems-how-would-you-handle-it) |
| 148 | [Chatbot is hallucinating despite RAG. Why?](#chatbot-is-hallucinating-despite-rag-why) |
| 149 | [Vector DB storage costs are increasing. How would you optimize?](#vector-db-storage-costs-are-increasing-how-would-you-optimize) |
| 150 | [How would you design a GenAI knowledge platform for an enterprise with PDFs, SharePoint, Jira, and Confluence?](#how-would-you-design-a-genai-knowledge-platform-for-an-enterprise-with-pdfs-sharepoint-jira-and-confluence) |

</details>

## Knowledge Base & Data Preparation

### Basic

1. ### What is a Knowledge Base in a GenAI system?

   A **Knowledge Base (KB)** is a curated collection of documents and data that an AI application uses to answer questions accurately. Instead of relying solely on an LLM's internal training, relevant content is retrieved from the KB and passed to the model as context. KBs may contain structured and unstructured sources such as PDFs, manuals, database records, Jira tickets and Confluence pages.

   - **Source of truth:** Documents in the KB should be accurate and up-to-date.
   - **Separation from model weights:** Knowledge lives outside the model, so updating policies or product manuals only requires re-indexing documents, not fine-tuning.
   - **Metadata support:** Each document should include metadata (e.g., department, country, version) to support filtering and access control.

   Properly curated KBs reduce hallucinations and make the system easy to update because documents can be added or removed without retraining the model.

   **[⬆ Back to Top](#table-of-contents)**

2. ### Why is data preparation important for LLM applications?

   Data quality directly affects retrieval and generation quality. Poorly prepared data leads to irrelevant retrievals, hallucinations and duplicate answers. A typical preparation pipeline includes:

   1. **Data collection:** Gather documents from enterprise sources (SharePoint, Confluence, Jira, databases, emails).
   2. **Cleaning and normalization:** Remove headers, footers, page numbers, OCR noise and normalize case, dates and units to ensure consistent embeddings.
   3. **Deduplication:** Identify and remove duplicate records or documents to avoid redundant context.
   4. **Metadata enrichment:** Add attributes (department, version, country, author) to support filtering and access control.
   5. **Chunking:** Break large documents into manageable passages (e.g., 300–1000 tokens) so that embeddings capture local context.
   6. **Validation:** Check for completeness, stale versions and sensitive information before indexing.

   Clean, normalized and deduplicated data ensures reliable retrieval, reduces hallucinations and improves overall response quality.

   **[⬆ Back to Top](#table-of-contents)**

3. ### What types of enterprise documents have you worked with?

   Mention both **structured** (database tables, CSV/Excel files) and **unstructured/semi-structured** sources, such as:

   - Policy documents (HR, security, leave policies).
   - Product manuals, user guides and release notes.
   - Confluence pages, wikis, SOPs and runbooks.
   - Jira tickets and incident reports.
   - SharePoint repositories (PowerPoints, Word docs).
   - Emails and support tickets.
   - Database extracts (customer records, transaction logs).

   A good answer should describe how each source is extracted, cleaned, chunked and enriched with metadata before being indexed.

   **[⬆ Back to Top](#table-of-contents)**

4. ### How do you clean noisy data?

   Noise includes errors, inconsistent formatting, duplicate content, irrelevant sections and OCR artifacts. A cleaning strategy often involves:

   - **Removing boilerplate:** Strip headers, footers, watermarks and page numbers.
   - **Fixing encoding:** Correct character encoding issues and convert to a uniform encoding (e.g., UTF-8).
   - **Normalizing text:** Standardize case, whitespace, punctuation and date formats.
   - **OCR post-processing:** For scanned PDFs, review OCR output to correct misrecognized characters.
   - **Filtering irrelevant sections:** Exclude unrelated content such as advertisements or navigation elements.
   - **Data type conversion:** Ensure numbers, currencies and dates use consistent formats (e.g., ISO-8601).

   These steps reduce noise in embeddings and lead to more accurate retrievals.

   **[⬆ Back to Top](#table-of-contents)**

5. ### What is data normalization?

   Normalization converts data into a consistent format to improve search and analytical accuracy. It includes:

   - **Standardizing values:** Converting dates to a common format (e.g., `2025-01-01`), unifying country names (e.g., "United States" instead of "U.S.A." or "USA"), and consolidating phone number formats.
   - **Unifying case and whitespace:** Converting text to a consistent case (usually lower case) and trimming extra spaces.
   - **Removing duplicates:** Ensuring identical entities are represented only once.
   - **Harmonizing units:** Converting measurements (e.g., "lbs" to "kg") into a single unit.

   Proper normalization helps the semantic search engine recognize identical or related concepts even when they are written differently.

   **[⬆ Back to Top](#table-of-contents)**

6. ### How do you handle duplicate records?

   Duplicate records waste storage and reduce retrieval quality. Handling duplicates involves:

   - **Exact duplicate detection:** Compute file hashes (MD5/SHA-256) or string hashes to identify identical documents.
   - **Near-duplicate detection:** Use fuzzy matching or embedding similarity to detect records with minor textual differences.
   - **Deduplication policies:** Keep the latest approved version and archive or delete older duplicates.
   - **Version control:** Maintain version metadata so that only the current version appears in the knowledge base.

   By deduplicating data, you reduce storage costs and prevent multiple identical passages from being returned during retrieval.

   **[⬆ Back to Top](#table-of-contents)**

7. ### What is metadata and why is it important?

   Metadata is "data about data." In a KB, metadata provides context that describes each document or record, such as author, department, creation date, version, geographic scope and access control. Key benefits include:

   - **Search and filtering:** Users can filter documents by department, country or version.
   - **Access control:** Metadata tags enable role-based security so sensitive documents are only retrieved for authorized users.
   - **Version management:** Storing version numbers ensures that retrieval returns the most current document.
   - **Auditability:** Metadata tracks who created a document and when, assisting in compliance and governance.

   Metadata is stored alongside embeddings in the vector database to support hybrid semantic and metadata filtering during retrieval.

   **[⬆ Back to Top](#table-of-contents)**

8. ### How would you prepare PDF documents for a chatbot?

   Processing PDFs typically involves the following steps:

   1. **Identify the PDF type:** Determine whether it is text-based or scanned. For scanned PDFs, perform OCR (using tools such as Tesseract, Azure Document Intelligence or Google Cloud Vision) to extract text.
   2. **Extract text:** Use libraries like PyPDF2 or pdfminer for text-based PDFs.
   3. **Clean the text:** Remove headers, footers and page numbers; correct OCR errors; and normalize spacing and casing.
   4. **Chunk the content:** Divide the document into semantic sections (e.g., headings and paragraphs) so each chunk fits within the LLM's context window.
   5. **Enrich with metadata:** Add attributes such as document title, department, country, author and version.
   6. **Generate embeddings:** Use an embedding model to convert chunks into vectors.
   7. **Store in a vector database:** Save embeddings and metadata in a vector DB for semantic search.

   This pipeline makes PDFs searchable and allows the chatbot to fetch relevant passages at query time.

   **[⬆ Back to Top](#table-of-contents)**

9. ### What challenges arise with scanned PDFs?

   Scanned PDFs are images rather than selectable text. Challenges include:

   - **OCR requirement:** Text must be extracted via OCR before indexing; OCR can introduce misrecognitions, such as confusing "l" with "I".
   - **Poor scan quality:** Blurry or skewed pages reduce OCR accuracy.
   - **Complex layouts:** Multiple columns, tables and diagrams can confuse the OCR engine, causing incorrect ordering of content.
   - **Extraction of tables and diagrams:** Tables may lose structure; diagrams and charts might require specialized OCR or manual extraction.
   - **Processing time:** Running OCR on large numbers of pages is resource-intensive.
   - **Sensitive data:** Scanned documents may contain confidential information (IDs, salaries) that must be masked.

   Mitigate these issues by using robust OCR tools, manually validating critical documents, and splitting processing across compute resources.

   **[⬆ Back to Top](#table-of-contents)**

10. ### What is OCR?

    **OCR (Optical Character Recognition)** is the technology that converts images of text — scanned documents, photos, screenshots — into machine-readable text. In a GenAI pipeline, OCR is the first step for processing scanned PDFs and images before cleaning, chunking and embedding.

    Common OCR tools include:

    - **Tesseract:** Open-source OCR engine, good for clean scans.
    - **Azure Document Intelligence / AWS Textract / Google Cloud Vision:** Cloud services that handle complex layouts, tables and handwriting more reliably.

    OCR output usually needs post-processing to fix misrecognized characters, restore reading order and remove artifacts before it is indexed.

    **[⬆ Back to Top](#table-of-contents)**

### Intermediate

11. ### How would you process documents from SharePoint?

    Use SharePoint APIs or connectors to access the content:

    1. Use SharePoint APIs (Microsoft Graph) or connectors to list and download documents.
    2. Determine file type (Word, Excel, PowerPoint, PDF) and use appropriate extraction tools (e.g., `python-docx`, `openpyxl`, `pdfminer`).
    3. Clean and normalize text; handle tables and images separately.
    4. Capture metadata (site, library, folder, author, version).
    5. Chunk, embed and index the content in the vector database.

    **[⬆ Back to Top](#table-of-contents)**

12. ### How do you extract tables from PDFs?

    Table extraction depends on the PDF type:

    - **Text-based PDFs:** Use libraries like `camelot`, `tabula-py` or `pdfplumber`, which detect table boundaries and export rows/columns into DataFrames.
    - **Scanned PDFs:** Use OCR services with table-structure recognition (Azure Document Intelligence, AWS Textract), which return cells with row/column coordinates.
    - **Post-processing:** Validate headers, merge split cells, normalize data types and convert tables to a structured format (CSV/JSON or markdown) before chunking.

    Tables are often embedded separately or converted to a readable text representation (e.g., "Column: Value" pairs) so the LLM can interpret them correctly.

    **[⬆ Back to Top](#table-of-contents)**

13. ### How do you maintain document versioning?

    Versioning ensures retrieval always returns the most current document:

    - **Version metadata:** Store a version number and `last_updated` timestamp with each document and its embeddings.
    - **Upsert strategy:** When a new version arrives, mark or delete old embeddings and insert the new ones.
    - **Canonical source:** Designate a primary system for each document type so other copies sync to it.
    - **Archival:** Keep old versions archived for audit purposes but excluded from retrieval via metadata filters.

    **[⬆ Back to Top](#table-of-contents)**

14. ### How do you identify stale knowledge?

    Stale knowledge is outdated content that no longer reflects current policies or products:

    - **Timestamps:** Use metadata fields for `last_updated` and automatically flag documents older than a threshold.
    - **Versioning:** Track versions and deprecate old ones when new documents are added.
    - **Automated review workflows:** Notify content owners to review and update documents periodically.
    - **Query-failure analysis:** Analyze queries that retrieve outdated or conflicting answers to surface stale content.
    - **Retention policies:** Remove or archive documents that are no longer relevant or conflict with new policies.

    **[⬆ Back to Top](#table-of-contents)**

15. ### How would you handle multilingual documents?

    Handling multilingual documents involves:

    - **Detection:** Identify the language of each document using a language-detection library.
    - **Language-specific preprocessing:** Use appropriate tokenizers and stop-word lists for each language.
    - **Multilingual embeddings:** Use models like LaBSE, mBERT or XLM-Roberta that produce comparable embeddings across languages.
    - **Translation:** Optionally translate content to a common language (e.g., English) if using monolingual models.
    - **Metadata:** Tag documents with language information so that user queries are matched appropriately.

    **[⬆ Back to Top](#table-of-contents)**

16. ### What data quality checks do you perform?

    Quality checks performed before indexing include:

    - **Completeness:** Verify all expected documents and fields are present and extraction did not truncate content.
    - **Duplicates:** Detect exact and near duplicates via hashing and similarity checks.
    - **Freshness:** Flag documents older than a threshold or superseded by newer versions.
    - **Consistency:** Validate formats (dates, units, encodings) are normalized.
    - **Sensitive data:** Scan for PII or confidential content that must be masked before embedding.
    - **Extraction accuracy:** Spot-check OCR/parsing output, especially for tables and complex layouts.

    **[⬆ Back to Top](#table-of-contents)**

17. ### How do you measure knowledge base completeness?

    Define the scope of required knowledge (e.g., list of policies, product docs). Map existing documents to this list and track coverage metrics (percentage of topics covered). Conduct gap analysis by analysing queries that fail to retrieve relevant documents and update the KB accordingly. User feedback ("answer not found" flags) is a strong signal of missing coverage.

    **[⬆ Back to Top](#table-of-contents)**

18. ### Explain chunking and its importance

    **Chunking** is the process of splitting documents into smaller units before embedding. It matters because:

    - Embeddings capture local context better on focused passages than on entire documents.
    - Retrieved chunks must fit within the LLM's context window.
    - Granular chunks improve retrieval precision — the model gets only the relevant passage, not a whole manual.

    Too small and the context may lose meaning; too large and the chunk may exceed the model's context window or dilute relevance. Good chunking improves both retrieval recall and downstream generation quality.

    **[⬆ Back to Top](#table-of-contents)**

19. ### What chunk size would you choose and why?

    A typical balanced choice is **300–1000 tokens per chunk with some overlap** (e.g., 10–20%). The right size depends on:

    - **Content structure:** Chunk by headings/paragraphs for structured docs; sliding window for continuous text.
    - **Context window:** Smaller chunks let you pass more diverse passages to the LLM.
    - **Query style:** Short factual queries favor smaller chunks; summarization favors larger ones.

    Overlap maintains coherence across chunk boundaries while preserving retrieval granularity. The best size is found by experimentation against retrieval metrics (recall@k, precision@k).

    **[⬆ Back to Top](#table-of-contents)**

20. ### How do you handle document updates in a knowledge base?

    Implement an update pipeline:

    - **Change detection:** Monitor source systems for document updates (e.g., new versions, modifications).
    - **Re-ingestion:** Extract, clean, chunk and embed the updated document.
    - **Upsert:** Delete or mark old embeddings as deprecated; insert new embeddings.
    - **Versioning:** Update metadata to reflect the new version.
    - **Reindex:** If the index does not support incremental updates, schedule periodic rebuilds.

    **[⬆ Back to Top](#table-of-contents)**


## Retrieval Augmented Generation (RAG)

### Basic

21. ### What is RAG?

    **Retrieval-Augmented Generation (RAG)** is an architecture that combines information retrieval with text generation. A retriever component searches a knowledge base for relevant documents and passes the content to a large language model (LLM), which then generates an answer. RAG reduces hallucinations and allows the model to access up-to-date domain knowledge without retraining.

    **[⬆ Back to Top](#table-of-contents)**

22. ### Why is RAG preferred over fine-tuning in many cases?

    Fine-tuning embeds knowledge into model weights and requires retraining whenever data changes. RAG keeps knowledge external, enabling updates simply by adding or replacing documents. RAG benefits include:

    - **Freshness:** New documents can be indexed immediately without retraining.
    - **Lower cost:** Generating embeddings and storing vectors is cheaper than fine-tuning large models.
    - **Explainability:** The system can show the retrieved documents used to generate an answer.
    - **Reduced hallucinations:** Answers are grounded in retrieved content.

    Fine-tuning is preferred when you need to change the model's behaviour, style or domain understanding deeply; RAG is preferred for dynamic enterprise knowledge.

    **[⬆ Back to Top](#table-of-contents)**

23. ### Explain the RAG workflow

    RAG has three main stages:

    1. **Ingestion:** Documents are ingested, cleaned, chunked and converted into embeddings. The embeddings and metadata are stored in a vector database.
    2. **Retrieval:** During a query, the user's question is embedded and compared to stored vectors to find the most similar chunks (e.g., via approximate nearest neighbour search).
    3. **Augmentation and generation:** The retrieved chunks are concatenated with the query and provided to an LLM, which uses them to generate a final answer. The system may optionally rerank or filter results before augmentation.

    **[⬆ Back to Top](#table-of-contents)**

24. ### What problem does RAG solve?

    LLMs trained on fixed data cannot update their knowledge easily and often hallucinate when they lack information. RAG addresses this by retrieving relevant documents from an external knowledge base at query time, thereby grounding the model's response in authoritative sources. It allows the model to answer domain-specific or time-sensitive questions without costly retraining.

    **[⬆ Back to Top](#table-of-contents)**

25. ### What happens if retrieval quality is poor?

    RAG's success hinges on retrieving relevant context. If the retriever returns unrelated or low-quality passages, the LLM may either hallucinate or produce incorrect answers. Poor retrieval can result from:

    - Inadequate cleaning/normalization leading to noisy embeddings.
    - Incorrect chunk sizes (too small or too large).
    - Missing or outdated documents in the knowledge base.
    - Lack of metadata filters, causing the system to search across all departments or geographies.

    Therefore, evaluating and improving retrieval accuracy (via recall@k, precision metrics) is essential.

    **[⬆ Back to Top](#table-of-contents)**

### Intermediate

26. ### Describe indexing and retrieval stages

    **Indexing stage:** Documents are processed and stored in a vector database. Key steps include chunking, embedding generation and building an ANN index (e.g., HNSW) for fast similarity search.

    **Retrieval stage:** The user's query is embedded and used to search the index. Top-k candidate chunks are retrieved based on similarity (cosine similarity or Euclidean distance) and may be reranked. Additional metadata filters (department, country, version) are applied to limit results to relevant subsets. The selected chunks are then passed to the LLM.

    **[⬆ Back to Top](#table-of-contents)**

27. ### What is hybrid search?

    Hybrid search combines **semantic vector search** (embeddings) with **keyword search** (inverted index). This approach captures both conceptual similarity (synonyms and paraphrases) and exact keyword matches. Hybrid search often uses weighted scoring to balance the two components; for example, retrieving top documents via vector similarity and then applying a BM25 keyword scorer to rerank them. Hybrid search is useful when synonyms alone might miss domain-specific terms or when keywords provide strong signals.

    **[⬆ Back to Top](#table-of-contents)**

28. ### What is the difference between keyword search and semantic search?

    **Keyword search** uses exact or partial matches of words, typically via inverted indices. It does not understand context or synonyms and may fail when phrasing differs.

    **Semantic search** uses embeddings to capture meaning; documents with similar meaning are close in vector space even when they don't share keywords. For example, semantic search for "cool a room without AC" can return results about fans, whereas keyword search might only look for "cool" and "room".

    Semantic search is computationally heavier but yields more relevant results for natural language queries.

    **[⬆ Back to Top](#table-of-contents)**

29. ### What is reranking?

    Reranking is a second-stage process applied after initial retrieval. A reranker (often a smaller language model or cross-encoder) re-evaluates the relevance of retrieved documents and orders them more accurately. The first stage (ANN search) may retrieve approximate matches; reranking scores each candidate by jointly encoding the query and document to compute a fine-grained relevance score. This improves retrieval precision and reduces irrelevant context before passing results to the LLM.

    **[⬆ Back to Top](#table-of-contents)**

30. ### How do you improve retrieval accuracy?

    To improve retrieval:

    - **Tune chunk sizes:** Experiment with different chunk lengths and overlaps to capture context without including unrelated sentences.
    - **Use better embeddings:** Select embedding models suitable for your domain and language. Domain-specific embeddings often improve semantic similarity.
    - **Normalize and clean data:** Consistent formatting improves embedding quality and retrieval.
    - **Hybrid search:** Combine vector search with keyword search and metadata filters to capture both semantic and exact matches.
    - **Rerank results:** Apply cross-encoder models to reorder candidates.
    - **Evaluate retrieval metrics:** Use recall@k, precision and MRR (Mean Reciprocal Rank) to measure performance and iterate.

    **[⬆ Back to Top](#table-of-contents)**

31. ### What is context window limitation?

    LLMs have a finite context window (e.g., 4k–32k tokens). If the retrieved content plus user question exceeds this window, the model may truncate or drop important information. To mitigate this, choose appropriate chunk sizes, restrict the number of retrieved passages and condense or summarize long documents. Newer models with longer context windows (e.g., 128k tokens) reduce this problem but require careful prompt engineering.

    **[⬆ Back to Top](#table-of-contents)**

32. ### How does chunking affect RAG performance?

    Chunking is the process of splitting documents into smaller units. Too small and the context may lose meaning; too large and the chunk may exceed the model's context window. A balanced chunk size (typically 300–1000 tokens) with overlap maintains coherence while preserving retrieval granularity. Good chunking improves both retrieval recall and downstream generation quality.

    **[⬆ Back to Top](#table-of-contents)**

33. ### Explain Top-K retrieval

    Top-k retrieval is a common strategy in vector search where the system returns the **k most similar documents** (according to cosine similarity or other metrics) to the query. The value of k (e.g., 3, 5, 10) balances recall and efficiency: too low may miss relevant passages; too high adds noise and increases latency. In RAG, top-k retrieval is often combined with reranking to choose the best context for the LLM.

    **[⬆ Back to Top](#table-of-contents)**

34. ### What is context injection?

    Context injection refers to prepending retrieved passages to the user's query in a prompt. The LLM uses this additional context to generate an answer. The order of contexts, separators and instructions matters; providing clear separators (e.g., `DOCUMENT:` or `CONTEXT:`) helps the model differentiate between retrieved text and the actual user question. Prompt templates should also include system instructions to encourage the model to answer using the provided context.

    **[⬆ Back to Top](#table-of-contents)**

35. ### What are hallucinations and how does RAG reduce them?

    Hallucinations occur when a model confidently generates incorrect or invented information. By grounding the answer in retrieved documents, RAG reduces the chance of hallucination. However, if retrieval fails or context is irrelevant, hallucinations can still occur; therefore, high-quality retrieval and prompt engineering are essential.

    **[⬆ Back to Top](#table-of-contents)**

### Advanced

36. ### How would you evaluate a RAG system?

    RAG evaluation has two components: **retrieval evaluation** and **generation evaluation**.

    - **Retrieval:** Use metrics such as recall@k, precision@k and Mean Reciprocal Rank (MRR). These measure how often the relevant document is retrieved in the top-k results.
    - **Generation:** Evaluate the answer's correctness, completeness and faithfulness. Reference-based metrics (e.g., ROUGE, BLEU) compare generated answers to a ground truth. Reference-free metrics evaluate factuality or hallucination. Human evaluation may also be necessary.

    A robust evaluation framework isolates retrieval issues from generation issues and iterates on both components.

    **[⬆ Back to Top](#table-of-contents)**

37. ### What is the difference between Precision and Recall in retrieval?

    - **Precision** measures the proportion of retrieved documents that are relevant. High precision means few false positives.
    - **Recall** measures the proportion of all relevant documents that are retrieved. High recall means few false negatives.

    In RAG, you often prioritize recall (to ensure relevant documents are available for the LLM) and then use reranking to improve precision.

    **[⬆ Back to Top](#table-of-contents)**

38. ### What metrics would you use for RAG evaluation?

    Beyond recall@k and precision@k, you can use:

    - **Mean Average Precision (MAP) and MRR:** Evaluate ranking quality.
    - **Faithfulness metrics:** Assess whether the generated answer is supported by retrieved evidence.
    - **Human evaluation:** Rate helpfulness, completeness and correctness.
    - **Latency and throughput:** Measure time to retrieve and generate responses.

    **[⬆ Back to Top](#table-of-contents)**

39. ### How do you reduce latency in RAG?

    Latency can be reduced by:

    - **Optimizing vector search:** Use efficient indexes like HNSW for approximate nearest neighbour search.
    - **Parallel retrieval:** Query multiple vector databases or shards concurrently.
    - **Caching:** Cache embeddings of frequent queries and retrieved contexts.
    - **Streamed generation:** Stream tokens from the LLM instead of waiting for the full answer.
    - **Asynchronous pipelines:** Overlap retrieval and generation when possible.
    - **Prompt summarization:** Summarize or compress retrieved content to fit within the context window and reduce LLM processing time.

    **[⬆ Back to Top](#table-of-contents)**

40. ### What are common failure scenarios in RAG?

    Common failure scenarios include:

    - **Missing or outdated documents:** The knowledge base lacks relevant content.
    - **Poor chunking or embedding quality:** Leads to irrelevant retrievals.
    - **Context window overflow:** Too many or too large chunks cause truncation.
    - **Insufficient filtering:** Retrieval returns documents from wrong departments or geographies.
    - **Hallucinations:** The model still invents information if context is weak or contradictory.

    **[⬆ Back to Top](#table-of-contents)**


## Embeddings

### Basic

41. ### What are embeddings?

    Embeddings are **dense numerical vectors** that represent words, sentences or documents in a continuous vector space. Similar items have vectors that are close together, while dissimilar items are far apart. They allow models to compute semantic similarity and power tasks such as search, recommendation and clustering. Embeddings compress high-dimensional text into more manageable representations, capturing meaning and relationships.

    **[⬆ Back to Top](#table-of-contents)**

42. ### Why do we need embeddings?

    Embedding models translate discrete language into continuous spaces, enabling:

    - **Semantic similarity:** Detect similarity between queries and documents even if they don't share keywords.
    - **Clustering and classification:** Group documents by topic or sentiment.
    - **Vector search:** Use approximate nearest neighbour algorithms to find similar documents quickly.
    - **Dimensionality reduction:** Represent long texts as fixed-length vectors.

    Embeddings are the foundation of semantic search and RAG systems.

    **[⬆ Back to Top](#table-of-contents)**

43. ### Explain vector representation

    In a vector space model, each item (word, sentence or document) is mapped to a high-dimensional numerical vector. The dimensions capture latent features learned from training data. For example, an embedding model might place "France" and "Paris" close together because they frequently co-occur. The distances between vectors (cosine similarity, Euclidean distance) reflect semantic similarity.

    **[⬆ Back to Top](#table-of-contents)**

44. ### What is semantic similarity?

    Semantic similarity measures how close in meaning two texts are. By comparing their embeddings (using cosine similarity), you can determine if two phrases express similar ideas. In RAG, high semantic similarity indicates that a document chunk is relevant to the query.

    **[⬆ Back to Top](#table-of-contents)**

45. ### How are embeddings generated?

    Embeddings are generated by models trained on large corpora. Common methods include:

    - **Word2Vec / GloVe:** Older word-level models that learn embeddings based on co-occurrence.
    - **Transformer-based models:** Models such as BERT, RoBERTa or Sentence Transformers compute contextual embeddings at sentence or passage level.
    - **LLM embedding APIs:** Many providers (OpenAI, Azure, Cohere) offer endpoints to generate document embeddings.

    For each chunk of text, pass it to the embedding model and store the resulting vector in the vector database.

    **[⬆ Back to Top](#table-of-contents)**

### Intermediate

46. ### What is the difference between keyword search and embedding search?

    Keyword search uses exact word matching and cannot understand synonyms or context. Embedding search converts text into vectors and measures semantic similarity. Embedding search returns conceptually related results even when keywords differ. However, embedding search requires specialized vector databases and is more computationally intensive than simple inverted-index search.

    **[⬆ Back to Top](#table-of-contents)**

47. ### What is cosine similarity?

    Cosine similarity measures the **cosine of the angle between two vectors**. It ranges from –1 (opposite) to 1 (identical) and is widely used in embedding search to determine how similar two texts are. A higher cosine similarity indicates greater semantic similarity.

    **[⬆ Back to Top](#table-of-contents)**

48. ### Why are embeddings high-dimensional vectors?

    High-dimensional spaces can capture nuanced relationships among words or documents. Each dimension represents a latent feature learned from data. High dimensionality allows embeddings to encode complex patterns, though it also increases storage and computational requirements. Dimensionality reduction techniques (e.g., PCA, t-SNE) can be applied to visualize or compress embeddings.

    **[⬆ Back to Top](#table-of-contents)**

49. ### What happens if two documents have similar embeddings?

    Similar embeddings indicate that the documents share semantic content. In vector search, they will be near each other, so the retriever is likely to return one when the other is relevant. If they represent duplicates or near-duplicates, deduplication policies should ensure only one is indexed.

    **[⬆ Back to Top](#table-of-contents)**

50. ### Explain Euclidean distance vs cosine similarity

    - **Euclidean distance:** Measures the straight-line distance between two vectors; influenced by magnitude.
    - **Cosine similarity:** Measures the angle between vectors; unaffected by magnitude, focusing on direction.

    Cosine similarity is commonly used for text embeddings because it normalizes vector lengths and better reflects similarity in meaning. Euclidean distance may be appropriate when vector norms carry meaningful information (e.g., in some image embeddings).

    **[⬆ Back to Top](#table-of-contents)**

51. ### What embedding models have you used?

    Mention models appropriate to the domain, such as:

    - **Sentence Transformers** (e.g., `all-mpnet-base-v2` from HuggingFace).
    - **OpenAI embeddings** (e.g., `text-embedding-3-small`).
    - **Cohere or Azure embeddings.**
    - **Domain-specific models:** e.g., SciBERT for scientific texts or BioClinicalBERT for healthcare.

    Discuss why a particular model was chosen (e.g., available in-house, cost, performance).

    **[⬆ Back to Top](#table-of-contents)**

52. ### How do embeddings capture meaning?

    Embedding models learn patterns in large corpora: they adjust weights so that words/phrases appearing in similar contexts have similar vectors. For instance, "king" and "queen" appear in related contexts ("royal", "crown"), so their vectors become close. Contextual models (BERT) consider surrounding words, enabling them to differentiate between polysemous words (e.g., "bank" as river vs financial institution).

    **[⬆ Back to Top](#table-of-contents)**

53. ### Why might embedding quality vary?

    Quality depends on the training data, model architecture, domain and language. Generic models trained on general text might not capture domain-specific terminology. Additionally, cleaning and normalization of text before embedding affect the resulting vectors. Domain-specific fine-tuning of embedding models often yields better performance.

    **[⬆ Back to Top](#table-of-contents)**

### Advanced

54. ### How would you evaluate an embedding model?

    Use tasks such as similarity search, clustering and classification. Evaluate whether similar texts are close in vector space and dissimilar texts are far apart. Compute retrieval metrics (e.g., recall@k) using a labelled dataset. You can also visualize embeddings via t-SNE to see whether categories cluster appropriately.

    **[⬆ Back to Top](#table-of-contents)**

55. ### What are embedding drift issues?

    Embedding drift occurs when the relationship between vectors changes over time because the domain language evolves (e.g., new slang or technical terms). This can cause previously similar vectors to diverge, reducing retrieval quality. Regularly updating embeddings with new data and retraining or fine-tuning embedding models helps mitigate drift.

    **[⬆ Back to Top](#table-of-contents)**

56. ### How do domain-specific embeddings help?

    Domain-specific models are trained on text from the target domain (legal, medical, finance). They capture specialized vocabulary and semantics better than general models, leading to more accurate retrieval and classification. For example, a biomedical embedding model will understand medical abbreviations and synonyms that a generic model might misrepresent.

    **[⬆ Back to Top](#table-of-contents)**

57. ### How would you handle millions of embeddings?

    Storing millions of vectors requires scalable infrastructure:

    - Use dedicated vector databases (e.g., Pinecone, Milvus) that support sharding, replication and approximate nearest neighbour indexing.
    - Batch embedding generation and use streaming ingestion with background compaction.
    - Apply metadata filtering to narrow the search space.
    - For cost control, compress embeddings or reduce dimensionality if acceptable.

    **[⬆ Back to Top](#table-of-contents)**

58. ### Explain dimensionality reduction

    Dimensionality reduction techniques (e.g., PCA, UMAP, t-SNE) project high-dimensional vectors into lower dimensions while preserving structural relationships. They are used for visualization or reducing storage and computational costs. However, reducing dimensions may lose some semantic information, so the trade-off must be evaluated carefully.

    **[⬆ Back to Top](#table-of-contents)**

59. ### What is ANN (Approximate Nearest Neighbor)?

    ANN algorithms find nearest vectors quickly **without scanning the entire dataset**. They trade exactness for speed. Common algorithms include **HNSW** (Hierarchical Navigable Small World graphs) and **IVF** (Inverted File). HNSW organizes vectors into layers of proximity graphs, enabling logarithmic search complexity. ANN is essential for real-time retrieval over millions of embeddings.

    **[⬆ Back to Top](#table-of-contents)**

60. ### How does ANN improve performance?

    Exact nearest neighbour search scales poorly as the number of vectors increases. ANN indexes precompute structures that enable the retrieval engine to prune the search space. HNSW, for example, uses a multilayer graph so the search algorithm quickly jumps closer to the query point, drastically reducing comparisons. This improves latency while achieving high recall.

    **[⬆ Back to Top](#table-of-contents)**


## Vector Databases

### Basic

61. ### What is a vector database?

    A vector database stores **high-dimensional vectors** and supports **similarity search**. Unlike traditional relational databases that store structured rows and use exact matching, vector databases use specialized indexes (e.g., HNSW, IVF) to perform approximate nearest neighbour searches quickly. They often support metadata filtering and integration with machine-learning pipelines.

    **[⬆ Back to Top](#table-of-contents)**

62. ### Why can't traditional SQL databases efficiently handle vector search?

    Relational databases are optimized for exact queries with indexes on discrete values. They lack efficient mechanisms to search high-dimensional floating-point vectors and compute similarity. Without specialized indexes, searching for nearest vectors becomes a full table scan and scales poorly. Vector databases incorporate ANN algorithms and memory layouts designed for vector operations.

    **[⬆ Back to Top](#table-of-contents)**

63. ### Name some vector databases

    Popular vector stores include **Pinecone, Milvus, Weaviate, ChromaDB, Qdrant and Redis Vector**. These systems provide APIs for embedding storage, similarity search, filtering and scaling. Postgres with the **pgvector** extension is also a common choice when teams want vector search inside an existing relational database.

    **[⬆ Back to Top](#table-of-contents)**

64. ### What is the difference between a vector DB and a relational DB?

    - **Data model:** Vector DBs store embeddings and metadata; relational DBs store rows with typed columns.
    - **Query type:** Vector DBs support similarity search via ANN; relational DBs support SQL operations, joins and exact filtering.
    - **Index structures:** Vector DBs use HNSW, IVF or PQ indexes; relational DBs use B-trees or hash indexes.
    - **Use cases:** Vector DBs power semantic search, recommendation and RAG; relational DBs handle OLTP transactions and structured reporting.

    **[⬆ Back to Top](#table-of-contents)**

65. ### What is vector indexing?

    Vector indexing creates an efficient data structure to search for nearest neighbours. HNSW builds a layered graph where nodes connect to neighbours and long-range links; IVF splits the vector space into clusters and searches only relevant buckets. Index building is crucial for low-latency retrieval.

    **[⬆ Back to Top](#table-of-contents)**

### Intermediate

66. ### Explain HNSW indexing

    **HNSW (Hierarchical Navigable Small World)** is an ANN algorithm where vectors are organized into multiple layers of navigable small-world graphs. Higher layers have fewer nodes and long connections; lower layers have denser connections. A search begins at the top layer, quickly finds a close neighbour and "descends" through layers to refine results. HNSW achieves logarithmic search complexity with high recall.

    **[⬆ Back to Top](#table-of-contents)**

67. ### Explain FAISS

    **Faiss** is a library developed by Meta for efficient similarity search. It provides algorithms for indexing and searching large collections of vectors, supporting CPU and GPU acceleration. Faiss helps store and search billions of vectors, offering both exact and approximate search methods, including IVF, HNSW and PQ. The library's GPU capabilities make it suitable for large-scale deployment.

    **[⬆ Back to Top](#table-of-contents)**

68. ### What is Pinecone?

    **Pinecone** is a managed vector database service. It abstracts away infrastructure, offering API endpoints to upsert embeddings, query using vector similarity, filter by metadata and manage scaling. Pinecone uses ANN indexing (e.g., HNSW) and provides hybrid search and incremental updates. It also integrates with LLM pipelines for RAG applications.

    **[⬆ Back to Top](#table-of-contents)**

69. ### What is ChromaDB?

    **ChromaDB** is an open-source vector database that is lightweight and easy to embed in Python applications. It supports storing and querying document embeddings along with metadata. ChromaDB is often used for local prototypes and small to medium-sized RAG applications.

    **[⬆ Back to Top](#table-of-contents)**

70. ### What is Weaviate?

    **Weaviate** is an open-source vector database that supports hybrid search, schema-free objects, REST and GraphQL APIs. It can integrate with external modules (e.g., transformer encoders) and offers hybrid keyword and vector search, metadata filtering and multi-tenant support.

    **[⬆ Back to Top](#table-of-contents)**

71. ### What is Milvus?

    **Milvus** is an open-source vector database that scales horizontally and integrates with ANN libraries like Faiss and HNSW. It supports billions of vectors, multi-collection management, partitions and metadata filters. Milvus is widely used for RAG and recommendation systems.

    **[⬆ Back to Top](#table-of-contents)**

72. ### How is similarity search performed?

    Similarity search computes the distance between a query vector and stored vectors. Common metrics are cosine similarity and Euclidean distance. ANN indexes like HNSW prune the search space so only a subset of vectors is scanned. The top-k most similar vectors are returned.

    **[⬆ Back to Top](#table-of-contents)**

73. ### Explain metadata filtering

    Metadata stored alongside embeddings (e.g., department, country, version) allows the retriever to restrict search results. For example, a query for "leave policy" can filter by `department=HR` and `country=India`. Filtering is applied before or during vector search to improve relevance and performance.

    **[⬆ Back to Top](#table-of-contents)**

74. ### What is Top-K nearest neighbor search?

    When a query vector is provided, top-k search returns the **k most similar stored vectors** based on a similarity metric. The value of k determines how many candidates will be passed to the LLM; adjusting k balances recall and noise.

    **[⬆ Back to Top](#table-of-contents)**

75. ### How would you store document metadata?

    Most vector DBs allow storing an arbitrary JSON or key-value map with each embedding. For instance, a record could include fields like:

    ```json
    {
      "document_id": "HR_policy_v3",
      "department": "HR",
      "country": "India",
      "version": "3.0"
    }
    ```

    This metadata can then be used for filtering or retrieving the original document.

    **[⬆ Back to Top](#table-of-contents)**

### Advanced

76. ### How do vector DBs scale?

    Vector DBs scale **horizontally** by sharding data across nodes or partitions. They replicate data for durability and use distributed indexes. As the dataset grows to millions or billions of vectors, additional nodes are added. Some managed services automatically handle scaling and failover.

    **[⬆ Back to Top](#table-of-contents)**

77. ### Explain indexing trade-offs

    Indexing improves query speed but requires memory and rebuild time. Choices include:

    - **Exact vs approximate search:** Exact search returns the true nearest neighbours but is slow for large datasets. Approximate search sacrifices a bit of accuracy for speed.
    - **Index type:** HNSW offers high recall and fast search but higher memory usage; IVF uses less memory but might have lower recall.
    - **Rebuild frequency:** Frequent updates may require periodic reindexing to maintain performance.
    - **Parallelization:** Sharding across nodes can accelerate indexing but complicates query routing.

    **[⬆ Back to Top](#table-of-contents)**

78. ### How would you handle billions of vectors?

    Use a distributed vector database (e.g., Milvus or Pinecone) with sharding and replication. Compress vectors using techniques like **Product Quantization (PQ)** to reduce memory. Partition the data by domain or metadata and perform multi-stage retrieval (coarse filtering, followed by fine search). Ensure the infrastructure provides enough CPU/GPU resources to build indexes and answer queries in time.

    **[⬆ Back to Top](#table-of-contents)**

79. ### How do you update embeddings when documents change?

    When a document is updated, regenerate embeddings for the changed chunks and **upsert** them. Delete or mark the old embeddings as outdated (e.g., use version metadata). Some vector DBs support incremental indexing; otherwise, schedule periodic index rebuilds.

    **[⬆ Back to Top](#table-of-contents)**

80. ### How would you optimize vector search latency?

    - **Use efficient indexes:** HNSW with tuned parameters (M, efConstruction, efSearch).
    - **Reduce vector dimensions:** Keep embeddings as small as possible while maintaining accuracy.
    - **Utilize GPU acceleration:** Use libraries like Faiss with GPU support.
    - **Warm up caches:** Cache frequent queries and their results.
    - **Parallelize queries:** Route queries across multiple shards and nodes.

    **[⬆ Back to Top](#table-of-contents)**


## Semantic Search

### Basic

81. ### What is semantic search?

    Semantic search finds results based on **meaning** rather than exact keywords. It converts queries and documents into embeddings and compares them in a vector space. This allows the system to understand synonyms, paraphrases and context. For example, searching for "how to cool a room without AC" might return results about fans or ventilation despite the absence of the term "cool" in the document.

    **[⬆ Back to Top](#table-of-contents)**

82. ### How is semantic search different from keyword search?

    Keyword search indexes words and matches them exactly; it does not account for synonyms or context. Semantic search uses embeddings to capture meaning and therefore returns results that are conceptually similar even when the wording differs. Keyword search is faster and easier to implement; semantic search is slower and requires vector infrastructure but yields more relevant results for natural language queries.

    **[⬆ Back to Top](#table-of-contents)**

83. ### What problems does semantic search solve?

    Semantic search addresses challenges like:

    - **Synonym mismatch:** Returns results for "physician" when the query uses "doctor."
    - **Context understanding:** Recognizes that "Apple" could refer to the company or the fruit based on context.
    - **User intent:** Handles ambiguous queries by leveraging embeddings and context to infer user intent.

    It is well-suited for unstructured text search, question answering and recommendation systems.

    **[⬆ Back to Top](#table-of-contents)**

84. ### Give a practical example of semantic search

    In an HR chatbot, a user may ask "How many vacation days can I take?" A semantic search engine will retrieve the leave policy document even if it uses the phrase "annual leave days" instead of "vacation." Keyword search might miss the document if no direct match exists.

    **[⬆ Back to Top](#table-of-contents)**

### Intermediate

85. ### Explain intent matching

    Intent matching involves understanding the user's underlying intent beyond the surface wording. Embeddings help capture intent; for example, "I forgot my password" and "How do I reset my login credentials?" express the same intent. Good embeddings and classification models can identify these queries as the same intent and route them to the right knowledge base or workflow.

    **[⬆ Back to Top](#table-of-contents)**

86. ### What is query embedding?

    A query embedding is the **vector representation of the user's question**. It is generated using the same embedding model as document embeddings. Semantic search systems compute similarity between query embeddings and document embeddings to find relevant content.

    **[⬆ Back to Top](#table-of-contents)**

87. ### What is document embedding?

    A document embedding is the **vector representation of a document or chunk**. For fairness, the same embedding model should be used for both queries and documents. Document embeddings capture the semantics of the text and are stored in the vector database.

    **[⬆ Back to Top](#table-of-contents)**

88. ### Why can semantic search return relevant results without exact keywords?

    Because embeddings capture meaning, the search engine can find documents with similar semantics even if the exact words don't appear. For example, "physician" and "doctor" produce similar vectors; therefore, a query for "doctor" may return documents containing "physician." 

    **[⬆ Back to Top](#table-of-contents)**

89. ### What is query expansion?

    Query expansion involves adding synonyms or related terms to the query to improve recall. In a hybrid search system, the original query may be expanded with synonyms (via thesaurus or knowledge graphs) to retrieve more relevant documents. However, embedding models often obviate the need for explicit query expansion because they implicitly capture synonym relationships.

    **[⬆ Back to Top](#table-of-contents)**

### Advanced

90. ### How do you improve semantic search relevance?

    - **Use high-quality embeddings:** Choose models trained on large, diverse corpora or specific to your domain.
    - **Clean and normalize text:** Remove noise and standardize text to generate better embeddings.
    - **Metadata filtering:** Limit search to relevant departments or document types.
    - **Hybrid search and reranking:** Combine vector and keyword search and re-rank results to maximize precision.
    - **Continuous evaluation:** Use user feedback and evaluation metrics to refine retrieval.

    **[⬆ Back to Top](#table-of-contents)**

91. ### How do you evaluate semantic search quality?

    Use labelled datasets to compute recall@k, precision@k, MAP and MRR. Evaluate whether the top-k results truly answer the query and adjust embedding models or search parameters accordingly. Human evaluation and A/B testing can further assess user satisfaction.

    **[⬆ Back to Top](#table-of-contents)**

92. ### What role does reranking play?

    Reranking improves precision by applying a more powerful model to the top candidates retrieved by the ANN search. The reranker jointly encodes the query and candidate documents to compute an exact relevance score. It can incorporate cross-attention to better capture relationships and filter out noise.

    **[⬆ Back to Top](#table-of-contents)**

93. ### Explain hybrid search architecture

    Hybrid search combines keyword search and vector search. Typical workflow:

    1. Use metadata filters and keyword search (e.g., BM25) to narrow the search space.
    2. Compute embeddings for the query and candidate documents.
    3. Perform vector search on the reduced set to rank documents by semantic similarity.
    4. Optionally, rerank with a cross-encoder.

    This combination leverages the precision of keyword search and the contextual understanding of vector search.

    **[⬆ Back to Top](#table-of-contents)**

94. ### How would you debug poor search results?

    - **Check preprocessing:** Verify that text was cleaned, normalized and chunked correctly.
    - **Inspect embeddings:** Use t-SNE to visualize vectors and see if similar documents cluster together.
    - **Evaluate retrieval metrics:** Compute recall and precision to see if the retriever returns relevant documents.
    - **Analyze queries:** Identify whether certain terms or phrasings are causing misinterpretation.
    - **Adjust search parameters:** Experiment with different k values, similarity thresholds, hybrid weights and reranker models.

    **[⬆ Back to Top](#table-of-contents)**


## Python

### Basic

95. ### How do you read CSV files using Python?

    Use the **pandas** library:

    ```python
    import pandas as pd
    df = pd.read_csv('file.csv')
    ```

    The DataFrame `df` will contain the contents of the CSV. Pandas is a powerful library for data analysis and manipulation.

    **[⬆ Back to Top](#table-of-contents)**

96. ### What is the difference between a list and a tuple?

    Both lists and tuples store collections, but their characteristics differ:

    | Property | List | Tuple |
    | --- | --- | --- |
    | Mutability | Mutable (elements can be modified) | Immutable (elements cannot be changed) |
    | Performance | Slower iteration, more memory | Faster iteration, less memory |
    | Operations | Better for insertion and deletion | Better for access; hashable, so usable as dictionary keys |
    | Built-in methods | Many methods (append, extend, etc.) | Fewer methods |

    Choose a list when you need to modify data; choose a tuple when you need an immutable collection or a key in a dictionary.

    **[⬆ Back to Top](#table-of-contents)**

97. ### Explain dictionaries in Python

    A dictionary stores data values in **key:value pairs**. Dictionaries are ordered (as of Python 3.7), changeable and do not allow duplicate keys. Keys must be unique and immutable; values can be of any type.

    ```python
    my_dict = {"brand": "Ford", "model": "Mustang", "year": 1964}
    value = my_dict["model"]  # returns 'Mustang'
    ```

    **[⬆ Back to Top](#table-of-contents)**

98. ### What is Pandas?

    **Pandas** is an open-source Python library providing fast, flexible and expressive data structures for manipulating numerical and textual data. It offers DataFrames for tabular data, enabling easy reading, filtering, aggregation and visualization.

    **[⬆ Back to Top](#table-of-contents)**

99. ### What is NumPy?

    **NumPy** stands for Numerical Python. It is a library used for working with arrays, including mathematical functions, linear algebra and Fourier transforms. NumPy provides the `ndarray` object, which allows efficient numerical computations and is optimized for performance (up to 50× faster than Python lists). Many data-science libraries (pandas, scikit-learn) build upon NumPy arrays.

    **[⬆ Back to Top](#table-of-contents)**

100. ### How do you handle missing values?

     Use `df.isna()` to identify missing values and `df.dropna()` or `df.fillna(value)` to remove or impute them. You can fill missing numeric values with the mean or median and categorical values with the mode. Always analyse the percentage of missing data and decide whether imputation is appropriate or dropping rows/columns is better.

     **[⬆ Back to Top](#table-of-contents)**

### Intermediate

101. ### How would you clean text data?

     Text cleaning steps include:

     1. Converting to lower case.
     2. Removing punctuation and special characters (using regex).
     3. Tokenizing text into words.
     4. Removing stopwords (common words like "and", "the").
     5. Stemming or lemmatizing words to their base forms.
     6. Handling emojis, accents and whitespace.

     Libraries such as `re`, `nltk` and `spaCy` help with these tasks.

     **[⬆ Back to Top](#table-of-contents)**

102. ### Explain regex

     Regular expressions (regex) are sequences of characters that define search patterns. Python's `re` module provides functions like `re.sub()` to replace patterns and `re.findall()` to extract matches. Regex is powerful for cleaning text (e.g., removing URLs, special characters) and validating formats (e.g., email addresses).

     **[⬆ Back to Top](#table-of-contents)**

103. ### How do you remove stop words?

     Use libraries like **nltk**:

     ```python
     from nltk.corpus import stopwords
     stop_words = set(stopwords.words('english'))
     tokens = [word for word in tokens if word not in stop_words]
     ```

     Alternatively, use custom stop-word lists or spaCy's built-in stop words.

     **[⬆ Back to Top](#table-of-contents)**

104. ### How do you tokenize text?

     Tokenization splits a string into individual tokens (words or subwords). In Python, you can use `str.split()` for simple tokenization or use more advanced tokenizers from nltk (`word_tokenize`) or spaCy. Tokenization is often the first step in NLP preprocessing.

     **[⬆ Back to Top](#table-of-contents)**

105. ### What libraries are used in NLP?

     Common NLP libraries include **nltk, spaCy, gensim, transformers (HuggingFace), sentence_transformers**, and **fuzzywuzzy** for fuzzy string matching. Each library offers different capabilities ranging from tokenization and POS tagging to advanced transformer models.

     **[⬆ Back to Top](#table-of-contents)**

106. ### How do you process large files?

     To process large files efficiently, avoid loading the entire file into memory. Use chunked reading with `pandas.read_csv(..., chunksize=N)` or Python's built-in `open()` with iteration over lines. For parallel processing, use Dask or PySpark to distribute the workload.

     **[⬆ Back to Top](#table-of-contents)**

107. ### Explain generators

     Generators are iterators that yield items one at a time and maintain state between yields. They are created using functions with the `yield` keyword or generator expressions. Generators are memory-efficient because they produce items on the fly rather than storing the entire sequence in memory. Use them for streaming large data or infinite sequences.

     **[⬆ Back to Top](#table-of-contents)**

108. ### What is a DataFrame?

     A DataFrame is a **two-dimensional data structure** in pandas with labeled axes (rows and columns). It supports heterogeneous data types and offers methods for selecting, filtering, aggregating and reshaping data. DataFrames are analogous to tables in relational databases.

     **[⬆ Back to Top](#table-of-contents)**

### Advanced

109. ### Write Python code to remove duplicate rows

     ```python
     import pandas as pd
     df = pd.read_csv('data.csv')
     df_unique = df.drop_duplicates()
     ```

     `drop_duplicates()` removes duplicate rows based on all columns or specified subsets. You can also specify `keep='first'` or `keep='last'`.

     **[⬆ Back to Top](#table-of-contents)**

110. ### How would you create document chunks?

     Use a simple sliding window:

     ```python
     def chunk_text(text, max_tokens=500, overlap=50):
         words = text.split()
         chunks = []
         start = 0
         while start < len(words):
             end = start + max_tokens
             chunk = ' '.join(words[start:end])
             chunks.append(chunk)
             start += max_tokens - overlap
         return chunks
     ```

     This splits a document into overlapping chunks. Adjust `max_tokens` and `overlap` based on the model's context window.

     **[⬆ Back to Top](#table-of-contents)**

111. ### How would you generate embeddings using Python?

     Use a sentence transformer:

     ```python
     from sentence_transformers import SentenceTransformer
     model = SentenceTransformer('all-mpnet-base-v2')
     embeddings = model.encode(list_of_chunks, show_progress_bar=True)
     ```

     You can then store these embeddings in a vector database along with metadata.

     **[⬆ Back to Top](#table-of-contents)**

112. ### How would you call an LLM API?

     Use the provider's SDK. For example, using OpenAI:

     ```python
     import openai
     openai.api_key = 'YOUR_KEY'
     response = openai.ChatCompletion.create(
         model='gpt-3.5-turbo',
         messages=[
             {'role': 'system', 'content': 'You are a helpful assistant.'},
             {'role': 'user', 'content': 'What is RAG?'}
         ]
     )
     answer = response['choices'][0]['message']['content']
     ```

     Ensure proper error handling, rate limiting and cost management.

     **[⬆ Back to Top](#table-of-contents)**

113. ### How would you process 1 million documents efficiently?

     - **Parallelism:** Use multiprocessing or asynchronous tasks to handle extraction and embedding generation concurrently.
     - **Batching:** Process documents in batches rather than individually.
     - **Streaming:** Stream data from storage (e.g., cloud buckets) to avoid memory overload.
     - **Distributed systems:** Use Dask, PySpark or Ray to distribute workloads.
     - **Monitoring:** Track throughput and failures; retry failed tasks.
     - **Resource scaling:** Use cloud computing resources (GPUs for embedding generation, large memory machines for extraction).

     **[⬆ Back to Top](#table-of-contents)**


## SQL

### Basic

114. ### What is the difference between WHERE and HAVING?

     The `WHERE` clause filters **rows before** grouping or aggregation, whereas `HAVING` filters **groups after** aggregation. `WHERE` applies to individual rows and cannot contain aggregate functions; `HAVING` applies to aggregated results and can include aggregate functions. `WHERE` can be used without `GROUP BY`; `HAVING` is typically used with `GROUP BY`.

     **[⬆ Back to Top](#table-of-contents)**

115. ### What are joins?

     Joins combine rows from two or more tables based on related columns. Types of joins include **INNER, LEFT (OUTER), RIGHT (OUTER) and FULL (OUTER)**. Joins enable you to retrieve data scattered across multiple tables by specifying matching conditions.

     **[⬆ Back to Top](#table-of-contents)**

116. ### What is the difference between INNER and LEFT JOIN?

     - **INNER JOIN:** Returns only rows with matching values in both tables. Rows without matches are excluded.
     - **LEFT JOIN:** Returns all rows from the left table and the matching rows from the right table; if there is no match, the result contains `NULL` for right-table columns.

     Right joins mirror left joins but for the right table.

     **[⬆ Back to Top](#table-of-contents)**

117. ### What is GROUP BY?

     `GROUP BY` groups rows that have the same values into summary rows. It is typically used with aggregate functions (e.g., `COUNT`, `SUM`, `AVG`) to compute statistics per group. You can use `HAVING` to filter aggregated results.

     **[⬆ Back to Top](#table-of-contents)**

118. ### What is a primary key?

     A primary key is a column or combination of columns that **uniquely identifies each record** in a table. The primary key enforces uniqueness and cannot contain `NULL`. A table can have only one primary key constraint. Primary keys are often used as targets for foreign key references.

     **[⬆ Back to Top](#table-of-contents)**

### Intermediate

119. ### How do you find duplicate records?

     To find duplicates based on a column (e.g., email):

     ```sql
     SELECT email, COUNT(*)
     FROM users
     GROUP BY email
     HAVING COUNT(*) > 1;
     ```

     This groups by email and filters groups with a count > 1.

     **[⬆ Back to Top](#table-of-contents)**

120. ### Explain window functions

     Window functions perform calculations across sets of rows related to the current row. They include `ROW_NUMBER`, `RANK`, `DENSE_RANK`, `LEAD`, `LAG` and aggregate functions with `OVER` clauses. Window functions differ from aggregates because they do not collapse rows; they return a value for each row.

     ```sql
     SELECT customer_id, order_date,
            ROW_NUMBER() OVER (PARTITION BY customer_id ORDER BY order_date) AS row_no
     FROM orders;
     ```

     This assigns a sequence number to each order per customer, ordered by date.

     **[⬆ Back to Top](#table-of-contents)**

121. ### What is the difference between ROW_NUMBER and RANK?

     `ROW_NUMBER` assigns a **unique sequential number** to each row, regardless of ties. `RANK` assigns the **same rank to equal values and leaves gaps**; numbers may go 1, 2, 2, 4 etc. `DENSE_RANK` is similar to `RANK` but does not leave gaps. Use `ROW_NUMBER` when you need an arbitrary ordering of rows; use `RANK`/`DENSE_RANK` when ties need equal ranks.

     **[⬆ Back to Top](#table-of-contents)**

122. ### What is a CTE?

     A Common Table Expression (CTE) is a **temporary result set** defined within the execution scope of a single query. It is created using the `WITH` clause and can be referenced multiple times within the query. CTEs simplify complex queries and support recursion.

     ```sql
     WITH AvgSalary AS (
         SELECT department, AVG(salary) AS avg_sal
         FROM employees
         GROUP BY department
     )
     SELECT * FROM AvgSalary;
     ```

     This query defines a temporary table `AvgSalary` and then selects from it. CTEs can also be recursive to traverse hierarchical structures.

     **[⬆ Back to Top](#table-of-contents)**

123. ### What are indexes?

     An index is a database structure that improves query performance by allowing the database engine to locate rows faster than scanning the entire table. An index acts like a lookup table for the database, enabling operations such as filtering and sorting to use the index rather than performing a full table scan. Indexes also enforce constraints (e.g., primary keys and unique constraints) and help maintain referential integrity. However, excessive indexing can slow down writes (INSERT/UPDATE/DELETE) because indexes must be maintained.

     **[⬆ Back to Top](#table-of-contents)**

124. ### How do indexes improve performance?

     Indexes allow the database to filter and sort data efficiently. A query using an index avoids loading all rows (table scan) and can retrieve matching rows directly. For example, an index on an email column allows the query to isolate only the matching user's records rather than scanning 1 million rows. Indexes reduce disk I/O and improve response time, especially for large tables. The trade-off: each insert or update must also update the index, so more indexes mean slower write performance.

     **[⬆ Back to Top](#table-of-contents)**

### Advanced

125. ### Write SQL to find top 5 documents by access count

     Assuming a table `DocumentAccesses (doc_id, access_count)`:

     ```sql
     SELECT doc_id, access_count
     FROM DocumentAccesses
     ORDER BY access_count DESC
     LIMIT 5;
     ```

     **[⬆ Back to Top](#table-of-contents)**

126. ### How would you identify duplicate KB articles?

     Group by a unique field such as title or hash of the content and use `HAVING COUNT(*) > 1`. For near duplicates, compute text similarity (e.g., using Levenshtein distance or embeddings) and identify records above a similarity threshold.

     **[⬆ Back to Top](#table-of-contents)**

127. ### How would you detect stale documents?

     Add a `last_updated` timestamp column. Query documents older than a threshold (e.g., one year) and mark them for review:

     ```sql
     SELECT doc_id, last_updated
     FROM documents
     WHERE last_updated < DATE_SUB(CURRENT_DATE, INTERVAL 365 DAY);
     ```

     You can also track version numbers and compare them to the latest version.

     **[⬆ Back to Top](#table-of-contents)**

128. ### Explain query optimization

     Query optimization involves rewriting queries and using indexes to reduce execution time. Techniques include:

     - **Using proper indexes:** Avoid full table scans.
     - **Selecting only necessary columns:** Use `SELECT` with specific columns instead of `SELECT *`.
     - **Filtering early:** Use `WHERE` clauses to restrict rows before performing joins.
     - **Avoiding functions on indexed columns:** Functions prevent index usage.
     - **Using EXPLAIN plans:** Inspect how the database executes the query and adjust indexes or rewrite queries accordingly.

     **[⬆ Back to Top](#table-of-contents)**

129. ### What causes full table scans?

     Full table scans occur when no suitable index exists for the query's filtering conditions, when filters are not sargable, when functions are applied to indexed columns in the `WHERE` clause, when data types are mismatched, or when the query requests nearly the entire table. To prevent them:

     - Create indexes on frequently filtered columns.
     - Avoid `LIKE '%pattern'` and functions in `WHERE` clauses on indexed columns.
     - Ensure the query predicates match the index order.
     - Use covering indexes to satisfy queries without needing to access the table.

     For very small tables, full table scans might actually be faster, but for large tables they severely impact performance.

     **[⬆ Back to Top](#table-of-contents)**


## Enterprise Data Handling

### Basic

130. ### What is the difference between structured and unstructured data?

     - **Structured data:** Organized in predefined formats like tables (rows and columns) with clearly defined fields and data types. Examples include database tables and CSV files.
     - **Unstructured data:** No fixed schema; includes text documents, emails, images, audio and video. Requires NLP or computer vision to process.
     - **Semi-structured data:** Contains tags or markers but not a rigid schema, such as JSON, XML or log files.

     **[⬆ Back to Top](#table-of-contents)**

131. ### What are examples of enterprise data sources?

     - **Structured:** Relational databases (PostgreSQL, MySQL), data warehouses (Snowflake), CSV/Excel files.
     - **Semi-structured:** JSON logs, XML configuration files, HTML pages.
     - **Unstructured:** PDFs, Word documents, emails, chat transcripts, images and audio recordings.
     - **SaaS systems:** Jira, Confluence, ServiceNow, Salesforce, SharePoint, Slack.

     **[⬆ Back to Top](#table-of-contents)**

132. ### What challenges exist in enterprise data?

     - **Heterogeneity:** Diverse formats (PDFs, spreadsheets, emails) require different extraction methods.
     - **Quality:** Data may be incomplete, inconsistent or outdated.
     - **Duplication:** Same content may exist across multiple systems.
     - **Security:** Sensitive information must be masked and access controlled.
     - **Scalability:** Handling terabytes of data and millions of documents efficiently.
     - **Compliance:** Ensuring data governance, privacy and auditability.

     **[⬆ Back to Top](#table-of-contents)**

### Intermediate

133. ### How would you process emails for a knowledge base?

     1. **Extraction:** Use IMAP/SMTP APIs to pull messages.
     2. **Parsing:** Extract subject, sender, date and body; remove signatures, footers and quoted replies.
     3. **Normalization:** Standardize date formats and remove PII.
     4. **Classification:** Categorize emails (e.g., support tickets, HR inquiries).
     5. **Chunking:** Break long emails into paragraphs; treat each as a chunk with metadata (sender, date).
     6. **Embedding & storage:** Generate embeddings and store them in the vector database.

     **[⬆ Back to Top](#table-of-contents)**

134. ### How would you process Jira tickets?

     1. **API extraction:** Use Jira REST API to pull tickets with fields (summary, description, comments).
     2. **Cleaning:** Remove markup (e.g., Markdown), code blocks and irrelevant metadata.
     3. **Metadata:** Include ticket ID, status, priority, assignee, created date.
     4. **Chunking:** Split long descriptions and comments into smaller pieces.
     5. **Deduplication:** Remove duplicate tickets or duplicate comments.
     6. **Indexing:** Generate embeddings and store with metadata.

     **[⬆ Back to Top](#table-of-contents)**

135. ### How would you process Confluence pages?

     1. **API extraction:** Use Confluence REST API to fetch page content and metadata (space, title, version).
     2. **Cleaning:** Strip HTML tags, macros and attachments; convert to plain text.
     3. **Chunking:** Split by headings or paragraphs.
     4. **Metadata:** Capture page title, space, version, labels and last updated date.
     5. **Deduplication:** Detect near duplicates across spaces.
     6. **Indexing:** Embed and store with metadata.

     **[⬆ Back to Top](#table-of-contents)**

136. ### How would you process SharePoint documents?

     1. Use SharePoint APIs or connectors to list and download documents.
     2. Determine file type (Word, Excel, PowerPoint, PDF) and use appropriate extraction tools (e.g., `python-docx`, `openpyxl`, `pdfminer`).
     3. Clean and normalize text; handle tables and images separately.
     4. Capture metadata (site, library, folder, author, version).
     5. Chunk, embed and index the content.

     **[⬆ Back to Top](#table-of-contents)**

137. ### How would you handle confidential data?

     Implement security measures:

     - **PII masking:** Remove or obfuscate personally identifiable information (e.g., SSN, credit card numbers).
     - **Encryption:** Encrypt data in transit and at rest.
     - **Access control:** Use metadata tags to enforce role-based permissions in the vector database.
     - **Audit logging:** Track who accessed which documents and when.
     - **Data classification:** Label sensitive documents and store them in segregated collections.

     **[⬆ Back to Top](#table-of-contents)**

### Advanced

138. ### How would you implement data governance?

     Establish policies and processes to ensure data integrity, security and compliance:

     - **Define data owners:** Assign responsibility for each dataset.
     - **Data catalogue:** Maintain a catalogue of datasets with metadata descriptions.
     - **Retention policies:** Define how long data should be kept and how to dispose of outdated information.
     - **Quality monitoring:** Implement automated checks and manual reviews for completeness and accuracy.
     - **Access governance:** Define roles, permissions and segregation of duties.
     - **Regulatory compliance:** Ensure adherence to GDPR, HIPAA and other regulations.

     **[⬆ Back to Top](#table-of-contents)**

139. ### How would you ensure data privacy?

     - **Data minimization:** Collect only necessary data for the task.
     - **Anonymization & pseudonymization:** Remove direct identifiers and replace with pseudonyms.
     - **Consent management:** Track user consent for data usage.
     - **Security controls:** Use encryption, access controls and network segmentation.
     - **Audit & compliance:** Conduct regular audits and maintain compliance documentation.

     **[⬆ Back to Top](#table-of-contents)**

140. ### How would you mask sensitive information?

     Use regex patterns to identify sensitive data (e.g., credit card numbers) and replace them with masked formats (e.g., `**** **** **** 1234`). In RAG pipelines, remove or obfuscate sensitive data **before embedding**. Metadata should indicate that the document contains masked data. NER (Named Entity Recognition) models can also detect names, addresses and other PII that regex alone might miss.

     **[⬆ Back to Top](#table-of-contents)**

141. ### How would you build a knowledge base from 10TB of enterprise data?

     Break the process into phases:

     1. **Discovery:** Catalogue sources and their sizes; prioritize high-value data.
     2. **Parallel ingestion:** Use distributed systems (Spark, Dask) to extract and clean data concurrently.
     3. **Streaming & batching:** Process data in streams or batches to manage memory.
     4. **Deduplication & normalization:** Use hashing and similarity detection to remove duplicates and normalize formats.
     5. **Metadata enrichment:** Add metadata fields for filtering and access control.
     6. **Chunking & embedding:** Generate embeddings; use scalable vector databases.
     7. **Governance:** Implement access control, retention policies and quality checks.

     **[⬆ Back to Top](#table-of-contents)**

142. ### How would you handle access-controlled documents?

     Implement **role-based access control (RBAC)** or **attribute-based access control (ABAC)**. Store metadata fields indicating required permissions. When retrieving documents, apply filters to ensure only accessible documents are returned. Use encryption and secure authentication to prevent unauthorized access. Audit logs should track access attempts.

     **[⬆ Back to Top](#table-of-contents)**


## Scenario-Based Questions

143. ### Users say chatbot answers are irrelevant. How would you investigate?

     1. **Collect examples:** Gather user queries and the corresponding retrieved documents and responses.
     2. **Check retrieval quality:** Verify that the retriever returns relevant documents (inspect recall@k). If not, revisit cleaning, normalization, chunking, embedding model choice or metadata filters.
     3. **Review ranking:** Evaluate the reranker's performance; adjust its training data or parameters.
     4. **Examine prompt design:** Ensure that the prompt instructs the model to use the retrieved context and avoid hallucinations.
     5. **Feedback loop:** Allow users to flag wrong answers and use this feedback to improve retrieval and generation.

     **[⬆ Back to Top](#table-of-contents)**

144. ### Retrieval accuracy dropped after a KB update. What would you check?

     - **Indexing errors:** Confirm that new documents were correctly processed (cleaned, chunked, embedded) and metadata was applied.
     - **Version issues:** Ensure that older versions were archived and the latest versions are used.
     - **Schema changes:** Verify that the metadata schema has not changed, causing filters to fail.
     - **Embedding model drift:** Check if the embedding model or parameters changed, causing semantic mismatch.
     - **Evaluate recall and precision:** Use labelled queries to measure performance before and after the update.

     **[⬆ Back to Top](#table-of-contents)**

145. ### Search returns too many unrelated documents. How would you fix it?

     - **Adjust similarity threshold:** Increase the minimum similarity score for retrieved results.
     - **Tune top-k:** Reduce k to return fewer candidates.
     - **Improve chunking:** Reduce chunk size or increase overlap to better capture context.
     - **Enhance embeddings:** Use a more accurate embedding model or domain-specific model.
     - **Add metadata filters:** Restrict search by department, document type or version.
     - **Use reranking:** Apply a cross-encoder to refine the top results.

     **[⬆ Back to Top](#table-of-contents)**

146. ### Embedding generation is taking too long. What would you do?

     - **Use GPUs:** Many embedding models run much faster on GPUs.
     - **Batch processing:** Encode multiple chunks in parallel to reduce overhead.
     - **Choose a smaller model:** Use a lighter embedding model if slight performance loss is acceptable.
     - **Parallelize across workers:** Use multiprocessing or distributed computing.
     - **Optimize I/O:** Ensure data reading and writing do not bottleneck embedding generation.

     **[⬆ Back to Top](#table-of-contents)**

147. ### Documents are duplicated across systems. How would you handle it?

     - **Compute hashes:** Generate content hashes or checksums to identify exact duplicates.
     - **Fuzzy matching:** Use embedding similarity or fuzzy string matching to detect near duplicates.
     - **Maintain canonical sources:** Designate a primary system for each document type and synchronize other sources to it.
     - **Automated deduplication:** Build deduplication pipelines that detect and remove duplicates during ingestion.

     **[⬆ Back to Top](#table-of-contents)**

148. ### Chatbot is hallucinating despite RAG. Why?

     - **Irrelevant retrieval:** The retriever is returning wrong documents; the LLM is forced to guess.
     - **Insufficient context:** The relevant information may not exist in the KB or is truncated due to context length.
     - **Prompt issues:** The prompt might not instruct the model to only use context; including system instructions may help.
     - **Model limitations:** Some models still hallucinate; consider using models with lower hallucination rates or employing hallucination-detection techniques.
     - **Reranking:** Without reranking, irrelevant contexts may dominate.

     **[⬆ Back to Top](#table-of-contents)**

149. ### Vector DB storage costs are increasing. How would you optimize?

     - **Dimensionality reduction:** Use smaller embedding dimensions if quality allows.
     - **Compression:** Apply quantization or Product Quantization to compress vectors.
     - **Retention policies:** Remove outdated or low-utility embeddings.
     - **Sharding and tiered storage:** Move less frequently accessed embeddings to cheaper storage tiers.

     **[⬆ Back to Top](#table-of-contents)**

150. ### How would you design a GenAI knowledge platform for an enterprise with PDFs, SharePoint, Jira, and Confluence?

     1. **Source integration:** Build connectors to ingest data from each system (SharePoint API, Jira REST API, Confluence API) plus PDF extraction pipelines.
     2. **Data processing:** Normalize, clean and deduplicate content; extract metadata.
     3. **Chunking & embedding:** Choose appropriate chunk sizes; generate embeddings.
     4. **Vector storage:** Use a scalable vector database; store embeddings with metadata.
     5. **Retrieval API:** Provide endpoints to query by embedding with metadata filters.
     6. **LLM integration:** Use a prompt template to combine retrieved context with user questions.
     7. **Governance & security:** Implement RBAC/ABAC, encryption and audit logging.
     8. **Monitoring & evaluation:** Measure retrieval and generation quality; allow feedback loops.

     **[⬆ Back to Top](#table-of-contents)**

---

### Disclaimer

The questions provided in this repository are a summary of frequently asked questions for Generative AI engineering roles. There is no guarantee these exact questions will be asked in interviews — the purpose of this list is to help you quickly cover the key concepts. Contributions are welcome.

Good luck with your interview 😊

---
