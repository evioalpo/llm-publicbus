# LLM PDF Chatbot
 An LLM chatbot created with Cohere API and Streamlit that references a PDF document of Citybus public bus schedules.

## Quick Start
1. [Fork and then clone this repository](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo#about-forks) to a folder on your computer.
  
1. Open Visual Studio Code and then choose **File > Open Folder...** to open and edit the code.

1. Open the terminal window inside Visual Studio Code and type the following command to install the required Python packages.

   > pip install -r requirements.txt

1. Type the following terminal commands to create the necessary secrets file. Not having this will result in an error.

   > mkdir .streamlit

   > touch .streamlit/secrets.toml

   > echo "COHERE_API_KEY = 'PASTE YOUR API KEY HERE'" > .streamlit/secrets.toml

4. Run the app by typing the following command in the terminal window. 
   > streamlit run chatbot.py
   
   A new browser window will open where you can interact with the chatbot.

> [!NOTE]
> If you didn't paste a valid Cohere API key into your secrets file you will need to enter it into the sidebar for the chatbot to work.

5. Make minor changes to the code, save and then run your app again to see what happens.
