# semantic-search
What is Semantic Search?
Semantic search is a search technique that aims to understand the meaning behind a user's query and the content of web pages, rather than relying solely on matching keywords. It incorporates natural language processing, machine learning, and other technologies to comprehend the context and intent of the search query.

Semantic search improves search accuracy in several ways:



This is a simple application that demonstrates semantic search using Pinecone and Cohere. It allows users to enter a query and retrieve the most relevant results from a pre-indexed set of questions.
Installation

    Clone the repository: https://github.com/Nazzcodek/pinecone-semantic-search.git
    Install the required dependencies: pip install -r requirements.txt
    Set up your API keys:

    Get a Cohere API key from the Cohere website.
    Get a Pinecone API key from the Pinecone website.

    Update the environment variables:

    Set the COHERE_API_KEY environment variable with your Cohere API key.
    Set the PINECONE_API_KEY environment variable with your Pinecone API key.

Usage

    Run the application: streamlit run search.py
    Enter a query in the input field and click the "Search" button.
    The application will retrieve and display the top search results based on the query.

Project Ideas

The application uses a pre-defined list of project ideas for indexing and searching. You can customize the list by modifying the project_ideas variable in the script.
Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.
