About The Project
Welcome to LangChain ChatBot, a streamlined chat application powered by LangChain and OpenAI's text-davinci-003 model. Engage in dynamic conversations by entering your queries and witnessing the model's responses. The app is built using Streamlit, providing an intuitive interface for an immersive language interaction experience. Join the conversation and explore the possibilities of natural language processing!

Built With
Langchain
OpenAI
HuggingFace Hub
Streamlit
Getting Started
This will help you understand how you may give instructions on setting up your project locally. To get a local copy up and running follow these simple example steps.

Installation Steps
Option 1: Installation from GitHub
Follow these steps to install and set up the project directly from the GitHub repository:

Clone the Repository

Open your terminal or command prompt.
Navigate to the directory where you want to install the project.
Run the following command to clone the GitHub repository:
git clone https://github.com/k123659/Chatbot-using-Langchain
Create a Virtual Environment (Optional but recommended)

It's a good practice to create a virtual environment to manage project dependencies. Run the following command:
conda create -p <Environment_Name> python==<python version> -y
Activate the Virtual Environment (Optional)

Activate the virtual environment based on your operating system:
conda activate <Environment_Name>/
Install Dependencies

Navigate to the project directory:
cd [project_directory]
Run the following command to install project dependencies:
pip install -r requirements.txt
Run the Project

Start the project by running the appropriate command.
python app.py
Access the Project

Open a web browser or the appropriate client to access the project.
API Key Usage
This project utilizes the OpenAI GPT-3 API for generating responses. To run the chatbot with the API, you'll need to obtain an API key from OpenAI. Follow the steps below to set up your API key:

Obtaining an OpenAI API Key
Sign Up on OpenAI Platform:

If you don't have an account, sign up on the OpenAI platform.
Create a New API Key:

Once logged in, navigate to the API section or dashboard.
Create a new API key by following the on-screen instructions.
Copy Your API Key:

After creating the API key, copy it from the OpenAI platform.
Adding API Key to the Project
Create a .env File:

In the project's root directory, create a file named .env.
Add API Key to .env:

Open the .env file in a text editor.
Add the following line, replacing your-api-key with the actual API key:
OPENAI_API_KEY=your-api-key
Save the file.
Using the API Key in the Project
The project automatically reads the API key from the .env file using the python-dotenv library. Once the key is added to the .env file, the chatbot will use it to interact with the OpenAI GPT-3 API.

Note: Ensure the .env file is kept secure and not shared publicly, as it contains sensitive information.

Contributing
Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement". Don't forget to give the project a star! Thanks again!

Fork the Project
Create your Feature Branch
Commit your Changes
Push to the Branch
Open a Pull Request
License
Distributed under the MIT License. See LICENSE.txt for more information.

Contact
Karan Kaushik - @karankaushik904@gmail.com

Acknowledgements
We'd like to extend our gratitude to all individuals and organizations who have played a role in the development and success of this project. Your support, whether through contributions, inspiration, or encouragement, has been invaluable. Thank you for being a part of our journey.
