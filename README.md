# Gemini-Explorer

# Project Name: Create a Streamlit Chat Interface integrating Google’s Advanced LLM, Gemini

## Mission Scenario

Develop a chat interface using Streamlit to integrate with Google's cutting-edge large language model, Gemini. This project aims to provide an accessible platform to explore and demonstrate the capabilities of advanced language model applications. It also aims to serve as an educational and practical introduction to the fusion of large language models and user-friendly interfaces.

## Mission Workflow

Task 1: 🌐 Enable Google Cloud
Task 2: 🧬 Google Cloud Initialization
Task 3: ☁️ Setting up Google Gemini
Task 4: 📊 Streamlit Integration
Task 5: 🗣️ Adding Initial System Messages
Task 6: 📄 Preparing Submission

### Task 1: 🌐 Enabling Google Cloud
#### Steps:
- Create a Google Cloud account. Navigate to https://cloud.google.com/ and sign up for a new account or log in if you already have an account.
- Verify your account by entering the necessary billing information when prompted. Remember, you will not be charged now; it's just for verification purposes.
- Please make sure that your billing information is correct and up-to-date. This is crucial for account verification and access to Google Cloud Platform services.
- Create a new project in your Google Cloud Platform dashboard for the Gemini Explorer Mission. Give your project a unique and descriptive name to make it easy to identify.
- In the Google Cloud Platform console, go to the Vertex AI section and enable the recommended APIs for your project to utilize Vertex AI's capabilities fully.
  ![Task1](https://github.com/farzana-zaki/Gemini-Explorer/assets/126524003/7bf9a258-c770-4f35-abfa-1b01fa75095b)



### Task 2: 🧬 Google Cloud Initialization
🛠️ Dive into backend development with these steps! Clone the repository, set up a virtual environment, start the FastAPI server and test endpoints.
#### Google Cloud CLI: [1]
Google Cloud Command Line Interface (gcloud CLI) lets you manage resources and services from the command line. It also contains service and data emulators to speed up local development.
For example, you can use the gcloud CLI to create and manage the following:
- Compute Engine virtual machine instances and other resources
- Cloud SQL instances
- Google Kubernetes Engine clusters
- Dataproc clusters and jobs
- Cloud DNS managed zones and record sets
- Cloud Deployment Manager deployments

#### Steps:
- Install Google Cloud SDK: Visit the Google Cloud SDK webpage and download the installer for your operating system (https://cloud.google.com/sdk/docs/install).
- Initialize Google Cloud SDK by opening the command prompt and running the following command to start the initialization process: gcloud init
- Follow the on-screen instructions to log in to your Google Cloud account and set up your default project and configuration.
- Set No to compute region and zone (Optional Step)
- If you encounter authentication problems, use the following command to authenticate using your Google account: gcloud auth application-default login. This command will open a browser window for you to log in and 
  will help avoid the need to expose API keys.
  ![Task2](https://github.com/farzana-zaki/Gemini-Explorer/assets/126524003/6a105430-9add-49ab-a342-ff1e778c11d1)


### Task 3: ☁️ Setting up Google Gemini
🚀 Dive into generative models effortlessly! Import necessary libraries like Vertexai and Streamlit, then set up your project, initialize the model, and troubleshoot potential issues.

#### Steps:
To install Streamlit in a virtual environment, you can follow these steps:
- First, make sure you have Python installed on your system.
- Open a terminal or command prompt and navigate to the directory where you want to create your virtual environment.
- Create a new virtual environment by running the following command: 
python -m venv myenv
- Replace myenv with the name you want to give to your virtual environment.
- Activate the virtual environment: 
On Windows: myenv\Scripts\activate
On macOS and Linux: source myenv/bin/activate
- Once the virtual environment is activated, you can install Streamlit using pip: 
pip install streamlit
- After the installation, you can start using Streamlit within the virtual environment.

### Task 4:📊 Streamlit Integration
📲 Streamlit-powered Gemini Explorer! Define a chat function, set up the Streamlit interface, display and load chat history, and capture user input effortlessly.

### Task 5:🗣️ Adding Initial System Messages
🚀 Enhance ReX's personality in your Streamlit app! Implement logic for the initial prompt, experiment with different styles, and personalize ReX with user information for engaging interactions.

### Task 6:📄 Preparing Submission
- A GitHub repository for the project containing all the project files.
- Loom Video representing the overall approach. (Loom link: )

## References: 
1. https://cloud.google.com/sdk/gcloud
2. https://cloud.google.com/sdk/docs/install

## Acknowledgements
Special thanks to Radical AI for allowing me to embark on and complete this AI Mission.
![Radical AI Post](https://github.com/farzana-zaki/Gemini-Explorer/assets/126524003/6c75dbad-292a-4dd9-80e6-e79309cfb471)

