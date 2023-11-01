# ibm_AIPhase5

Creating chatbot using Python

Team Members:                                                                                                                                                                          
Pradeep S - au711021104033                                                                                                                                                            
Praveen R - au711021104034                                                                                                                                                               
Udhaya Kumar V - au711021104054                                                                                                                                                           
Gokul R - au711021104010                                                                                                                                                                     
Sansha MJ - au711021104042



### Running the Chatbot Application

Follow the steps below to run the chatbot application:

#### Prerequisites

- Python 3.x should be installed on your system.

#### Step 1: Clone the Repository

Clone the repository to your local machine using the following command:

```bash
git clone https://github.com/pradeepsivakumar03/ibm_AIPhase2.git
```

#### Step 2: Install Required Libraries

Navigate to the project directory and install the necessary libraries using the following command:

```bash
pip install flask openai
```

#### Step 3: Set Up OpenAI API Key

Sign up for OpenAI and obtain an API key. Set your OpenAI API key in the `app.py` file:

```python
api_key = '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'
openai.api_key = api_key
```

#### Step 4: Run the Application

In the project directory, execute the following command:

```bash
python app.py
```

This command will start the Flask development server.

#### Step 5: Access the Chatbot

Open a web browser and navigate to `http://localhost:5000/` to access the chatbot application.

### Important Notes

- Make sure to replace the placeholder API key with your actual OpenAI API key.

### Dataset Source

The dataset used for this project can be found in the `dialogs.txt` file.
