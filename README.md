# Finance-Chatbot


## Installation

To set up the Ecommerce Chatbot locally, follow these steps:

1. Clone the repository to your local machine:
```
   git clone https://github.com/your-username/finance-chatbot.git
```

2. Create a Conda Environment
```
   conda create -n finance python=3.10 -y
   activate the conda environment
   conda activate ecommbot
```

3. Install the required Python packages using pip:
```
pip install -r requirements.txt
```

4. Set up environment variables:
- Create a .env file in the project directory.
- Define the necessary environment variables such as database connection strings, API keys, etc.
  
5. Run the Flask application:
```
python app.py
```