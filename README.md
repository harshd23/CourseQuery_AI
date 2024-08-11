# CourseQuery AI: Question and Answer System for E-learning Website  

CourseQuery AI is a comprehensive LLM project built on Langchain and Google Generative AI. For the e-learning company, we are developing a Q&A system. E-Learning Company offers bootcamps and courses focused on data. Thousands of students use the email or Discord server to ask questions. Students will be able to ask questions and receive answers via this system's streamlit-based user interface.

![CourseQuery AI](https://github.com/harshd23/CourseQuery_AI/blob/main/coursequery.png)

## Technologies Used:-

- Langchain + Google Generative AI: LLM based Q&A
- Streamlit: UI
- Huggingface embeddings: Text embeddings
- FAISS: Vector databse

## Features:-

- Use an actual CSV file containing the FAQs that the e-learning company is currently using.
- This material will be used by their human personnel to help their course participants.
- We're going to develop a question-and-answer system based on LLM, which will help their human workers work less.
- With this technique, students ought to be able to ask questions straight and receive prompt responses.

## Project Structure:-

- app.py: The main Streamlit application script.
- langchain_code.py: This has all the langchain code
- requirements.txt: A list of required Python packages for the project.
- .env: Configuration file for storing your Google API key.

## Steps to run the project:-

1.Clone this repository to your local machine using:

```bash
  git clone https://github.com/harshd23/CourseQuery_AI.git
```

2.Install the required dependencies using pip:

```bash
  pip install -r requirements.txt
```

3.Acquire an api key through makersuite.google.com and put it in .env file

```bash
  GOOGLE_API_KEY="your_api_key_here"
```

## Usage of the project:-

1.Run the Streamlit app by executing:

```bash
streamlit run app.py

```

2.The web app will open in your browser.

- Click the "Create Knolwedge Base" button to start a knowledge base with FAQs. Please be patient as the creation of the knowledgebase will take some time.

- Your current folder will contain a directory named faiss_index once the knowledge base has been generated.

- You are now prepared to pose enquiries. In the Question field, type your query and press Enter.

## Sample Questions:-

- Do you guys provide EMI payments in addition to internships?
- Do you provide courses in JavaScript?
- Which should I study, tableau or power bi?
- My computer is a Mac. Does it support PowerBI use?
- I do not perceive a power pivot. How do I make it active?
