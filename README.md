## Different kinds of neural networks for movie genres classification and recommendation
We will build a hybrid recommendation system using Computer Vision (CV), Natural Language Processing (NLP), and Graph Neural Networks (GNNs). 

    Task 1: Computer Vision (CV) - You will tackle multi-label movie genre classification using two approaches: training a custom CNN from scratch and fine-tuning a pre-trained model on movie posters. After comparing their performance, you will extract dense visual embeddings from the penultimate layer of your best-performing model to use in the final recommendation graph.
    Task 2: Natural Language Processing (NLP) - Train an RNN or Transformer on movie plot summaries to predict genres, extracting semantic text embeddings.
    Task 3: Graph Neural Networks (GNN) - Construct a bipartite user-item graph using the ml-latest-small MovieLens dataset. You will initialize the movie nodes using the embeddings extracted from Tasks 1 & 2, and train a GNN to perform link prediction (recommending movies to users).
