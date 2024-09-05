# Reddit Data Extraction and Chatbot Project

This project focuses on extracting data from Reddit and performing exploratory data analysis (EDA) using the extracted data. Additionally, the project includes a chatbot component that utilizes Natural Language Processing (NLP) techniques. The project is divided into two main parts: data extraction and chatbot interaction.

## Project Components

### 1. Reddit Data Extraction
- The notebook `Get Reddit Data.ipynb` handles the extraction of data from Reddit using the PRAW (Python Reddit API Wrapper) library.
- The script fetches the top posts from a list of specified subreddits (e.g., `MachineLearning`, `Artificial`, `DataScience`) and stores the post data in a CSV file.
- Key information retrieved includes:
  - Post ID
  - Subreddit
  - Title
  - Selftext (post body)
  - Number of comments
  - Upvote ratio
  - Post URL
  - Score (upvotes)
  
- The extracted data is saved into a file called `DS_ML_AI_posts.csv`, which is used for further analysis.

### 2. Exploratory Data Analysis (EDA) and Chatbot Integration
- The notebook `Reddit EDA and Chatbot.ipynb` includes further analysis of the extracted Reddit data.
- Basic data cleaning and analysis are performed on the extracted posts, including:
  - Checking the distribution of posts by subreddit
  - Analyzing the number of comments and upvote ratios
  - Investigating trends in post engagement across subreddits
- In addition to EDA, the notebook includes a chatbot implementation using the `transformers` library from Hugging Face. This component can respond to user queries based on the Reddit data or general text inputs.

## How to Run the Project

### Requirements:
- Python 3.x
- Jupyter Notebook
- The following Python libraries:
  - `pandas`
  - `praw`
  - `transformers`
  - `numpy`
  - `matplotlib` (for data visualization)

You can install these dependencies using pip:

```bash
pip install pandas praw transformers numpy matplotlib
```

## Running the Notebooks:

### Data Extraction: 
Open and run the `Get Reddit Data.ipynb` notebook. This will extract data from Reddit and save it to a CSV file.

### EDA and Chatbot Interaction: 
Once the data is saved, open and run the `Reddit EDA and Chatbot.ipynb` notebook to analyze the extracted data and interact with the chatbot.

## Project Goals
1. **Data Analysis**: Analyze trends in user engagement (e.g., upvotes, comments) in popular subreddits like `MachineLearning`, `Artificial`, and `DataScience`.
2. **Chatbot**: Provide a chatbot capable of understanding and responding to user queries, potentially based on the analyzed data.

#### Files in the Repository
1. `Get Reddit Data.ipynb`: Notebook for extracting Reddit data using the PRAW API.
2. `Reddit EDA and Chatbot.ipynb`: Notebook for performing EDA and interacting with the chatbot.
3. `DS_ML_AI_posts.csv`: CSV file containing the extracted data (generated after running the extraction script).


