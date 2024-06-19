# Amazon-Alexa-Reviews

This project provides a web application for sentiment analysis on Amazon Alexa reviews. The application supports both single text input and bulk predictions via CSV file upload.


## How to Run

Follow these steps to set up and run the application.

### Step 1: Clone the Repository

Clone the repository to your local machine using the following command:

git clone https://github.com/KasimVali2207/Sentiment_Analysis.git

### Step 2: Create and activate a Conda environment

cd Amazon-Alexa-Reviews
conda create -n amazonreview python=3.10
conda activate amazonreview


### Step 3: Install dependencies

pip install -r requirements.txt


### Step 4: Run the application

flask --app api.py run
