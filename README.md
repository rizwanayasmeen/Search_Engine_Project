<h2>Project Title: Enhancing Search Engine Relevance for Video Subtitles</h2>
<h3>Description:</h3>
In today's digital content landscape, search engines are critical in connecting users with relevant information. This project is essentially a semantic search engine tailored for subtitles. It harnesses the power of BERT-based SentenceTransformers to create embeddings, which are numerical representations of the semantic meaning of subtitle documents. These embeddings are stored and managed within ChromaDB, a specialized database system. By employing natural language processing techniques, the search engine can efficiently process user queries and retrieve relevant results by matching the semantic content of the queries with the stored embeddings. 
In essence, it provides users with highly accurate and contextually appropriate subtitle recommendations based on the underlying meaning of their search queries.

<h3>Core Features:</h3>
<ul>
<li><b>Semantic Embeddings:</b> Employs BERT-based SentenceTransformers to create numerical representations (embeddings) capturing the semantic meaning of both documents and user queries.</li>
<li><b>Data Preprocessing:</b> Cleans and prepares subtitle documents by standardizing text, removing unnecessary information, and structuring data for efficient storage.</li>
 <li><b>ChromaDB Storage:</b> Stores these embeddings within a ChromaDB database, optimizing data management and retrieval processes.</li> 
  <li><b>Cosine Similarity:</b> Computes the cosine similarity metric between embeddings of documents and user queries, facilitating the identification of the most relevant results.</li>
  <li><b>User-Friendly Flask</b> Interface: Accepts user queries and returns the top 10 most relevant documents based on similarity scores.</li>
</ul>
<h3>Technologies Used:</h3>
<ul>
<li>Python</li>
<li>SentenceTransformers</li>
<li>chromadb, SQlite</li>
<li>Flask</li>
</ul>
<h3>Result:</h3>


https://github.com/rizwanayasmeen/Search_Engine_Project/assets/112886657/0020ec86-a616-4bc1-88b9-2284a4ef5da6



<h3>Contribution:</h3>
Pavani Kasipeta played a vital role in a collaborative project aimed at developing an advanced semantic search engine tailored for video subtitles. Pavani's expertise and contributions were instrumental in key aspects of the project's development, particularly in data preprocessing, database integration, and performance optimization.



<h3>Acknowledgments:</h3>
<ul>
<li>The project uses data from opensubtitles.org for subtitle content.</li>
<li>Acknowledgment to the Sentence Transformers library's creators and contributors for their valuable semantic search tool.</li>
</ul>
<h3>License:</h3>
This project is licensed under the MIT License.
