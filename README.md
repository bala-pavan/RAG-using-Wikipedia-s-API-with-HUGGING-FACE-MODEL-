Semantic similarity
Write a Python script that pulls the Wikipedia article of Munich, chunks it in a reasonable way,
and stores the chunks in a RAG semantic similarity database. Then add a function that runs a
query on that page, e.g. “Do people use bicycles in Munich?”, and prints the top hits.
- You can pull and parse the page in any way you want, but using Wikipedia’s API is
likely the easiest way.
- Since it’s just one single article we’re indexing, you will be able to run this without a
GPU.
