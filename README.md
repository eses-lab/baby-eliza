 
# Baby Eliza 

Baby Eliza is a simple chatbot built in Python based on the classic ELIZA bot. It uses pattern matching rules and response templates to simulate conversation.

## Background

ELIZA was one of the first chatbots designed to demonstrate natural language processing. It was created by Joseph Weizenbaum between 1964-1966 to emulate a Rogerian psychotherapist. 

Baby Eliza seeks to implement the core functionality of ELIZA - matching input to rules and selecting preset responses. It forgoes some of the complexity of ELIZA to focus on the foundational approach.

## Usage

To use Baby Eliza:

1. Ensure Python 3.x is installed

2. Clone this repository 

3. Run `pip install -r requirements.txt` to install dependencies

4. Run `python bot.py` to launch the bot

5. Chat with Baby Eliza in the console window

## File Structure

**bot.py** - Main bot class and functions 

**rules.json** - Rules for pattern matching 

**responses.json** - Bank of response templates

**utils.py** - Utility functions 

**ui.py** - User interface code 

**logs/** - Conversation log storage  

**tests/** - Testing code 
