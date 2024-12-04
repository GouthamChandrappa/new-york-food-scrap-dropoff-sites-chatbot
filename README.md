# NYC Food Scrap Drop-Off Sites Chatbot
 ## Introduction
- This project is a chatbot designed to assist users in finding information about food scrap drop-off sites in New York City. It leverages OpenAI's language models to provide detailed and accurate information about locations, hours of operation, and other relevant details. The chatbot processes a dataset of NYC food scrap drop-off sites and retrieves contextually relevant information based on user queries.

Features
Retrieves information about food scrap drop-off sites, including location, hosting organization, hours, and more.

Uses cosine similarity to find the most relevant entries in the dataset based on user queries.

Leverages OpenAI's GPT model for natural language understanding and response generation.

Prerequisites
Python 3.10.15

Required libraries:

pandas

numpy

openai

tiktoken

Ensure you have these installed before proceeding.

Setup
Clone the Repository

git clone https://github.com/GouthamChandrappa/new-york-food-scrap-dropoff-sites-chatbot.git
cd new-york-food-scrap-dropoff-sites-chatbot
Install Required Libraries Use pip to install the necessary dependencies:

pip install pandas numpy openai tiktoken
Set Up OpenAI API Key Update the openai.api_key in the script with your OpenAI API key. Replace:

openai.api_key = "YOUR API KEY"
with your actual API key. Ensure you keep this key secure.

Prepare the Dataset The project includes a dataset file, nyc_food_scrap_drop_off_sites.csv. Ensure this file remains in the project directory:

/home/goutham/GENAI/customchatbot/nyc_food_scrap_drop_off_sites.csv
Run the Chatbot Execute the script to test the chatbot:

python chatbot_nyc_scrap+drop_off_sites.ipynb
Alternatively, use Jupyter Notebook to open and run the .ipynb file.

Usage
Once the chatbot is running, it will respond to predefined queries such as:

"Where can I drop off food scraps in NYC?"

"What are the hours for food scrap recycling locations?"

You can modify the queries in the demonstrate_chatbot() function to test additional scenarios.

Project Files
chatbot_nyc_scrap+drop_off_sites.ipynb: The main Python script (Jupyter Notebook) for the chatbot.

nyc_food_scrap_drop_off_sites.csv: The dataset containing information about NYC food scrap drop-off sites.

Contributing
Contributions to this project are welcome. Please fork the repository, create a feature branch, and submit a pull request.

License
This project is released under the MIT License.
