Data Ingestion: Here we load the dataset from different-different sources, it may be .txt file, pdf file, webpage, wikipedia, excel file, JSON, image, videos etc. Here I am taking text file and pdf file for data loading.
For loading text data I am using TextLoader from langchain_community.document_loaders.
Later I have used PyPDFLoader from langchain_community.document_loader for loading PDF data. Similarly we can use WebBaseLoader for loading web pages, ArxivLoader for Arxiv data, WikipediaLoader for wikipedia data.
