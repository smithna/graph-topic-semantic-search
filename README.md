# Graph Topic Modeling for Semantic Search

The Jupyter notebooks in this repository accompany the blog post [Topic extraction with Neo4j Graph Data Science for better semantic search](https://medium.com/@nsmith_piano/topic-extraction-with-neo4j-graph-data-science-for-better-semantic-search-c5b7f56c7715).

To following along with the blog content, work through the notebooks in this order:

1. Download_TMDB_movies.ipynb
2. Extract themes.ipynb
3. Clean up themes and get embeddings.ipynb
4. Cluster themes.ipynb
5. Summarize theme groups.ipynb
6. Compare retrievers.ipynb

You will need a Neo4j environment with GDS installed. You can create an [Aura DS](https://neo4j.com/docs/aura/aurads/) instance or download [Neo4j Desktop](https://neo4j.com/download/).

You will also need an API key for the Large Language Model of your choice. The notebooks use Anthropic and OpenAI, but you can adapt the code to use others.
