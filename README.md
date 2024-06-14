# Semantic Search System using Homomorphic Encryption Scheme
**Homomorphic Encryption:**
 <br /> Homomorphic encryption is a powerful cryptographic technique that unlocks a new level of security and functionality when dealing with encrypted data. The encrypted data, called cipher text, is operated on and then decrypted to produce the desired output. The critical property of homomorphic encryption is that the output should be the same whether the cipher text is decrypted or the original data is operated on.
<br /><br />**Project Description:**
 <br /> -This is a semantic search model that finds the best matching sentences to a query all with encrypted computation. In other words, in a client-server setting, the server will never handle the raw query from the client and will still return the best matching sentence.
 <br /> -Initially, the code creates a semantic search model built with text embeddings from the text embedding model all-MiniLM-L6-v2
 <br />  -Once the embeddings for the text data and query are formed, a CKKS Homomorphic Encryption scheme is set up that allows encrypted calculations with vectors
 <br /> -Using the cryptographic scheme, the cosine similarity between the query and data is fetched and the sentences that match closest to the query are ranked
 <br /> -Use of Microsoft's open source homomorphic encryption library SEAL
