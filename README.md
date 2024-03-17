# SMS/Emails Spam Detection

<p align="center"><img src="https://images.unsplash.com/photo-1709477544343-56ceb8272ceb?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8NHx8c2NhbW1lcnxlbnwwfHwwfHx8MA%3D%3D" width="80%" height="auto"></p>

Welcome to the project. This project is created for detecting whether the message or sms is spam or not spam. 

  
## Live Demo:

See Project in Streamlit Webapp: https://sms-emails-spam-detection.streamlit.app/

## About this Project:

### Motivation/Purpose:

Today as internet is growing, scam also growing. Google also focus on this strategy in gmail.com. Whenever anyone send us email, google first see the content of email and try to detect that email is spam(include scam) or not, if email found spam then that transferred to spam folder. That's really help us to prevent from scammer. That's thing motivate me that I should also need to develop such similar project to understand how google do this. 

### Tools & Libraries:

I use following tools and python libraries to develop this whole project:

- **Python**
- **Streamlit** for deployment
- **Jupyter Notebook**
- **NLTK Library** for applying stemming and tokenization
- **String Library** for removing punctuation marks from text
- **Scikit-Learn Library**
- **Pickle Library** for exporting files from Jupyter Notebook to Python file
  


### Learning Outcomes:

- Handling Computation effeciently
- Text Preprocessing such as tokenization, stemming, removing punctuation marks and special characters etc from text
- Vectorization(Bag of Words, TF-IDF)
- Project handling
- Deployment on Streamlit free of cost


### How to Run on Your Machine:

1. **Clone the Repository:** Download all files and folders from this repository.
2. **Create Virtual Environment:**
   ```bash
   py -3 -m venv virtualEnv
3. **Run this command:**
   ```bash
   pip freeze > requirements.txt
4. **Finally start the streamlit app:** Run the following command on command terminal.
   ```bash
   streamlit run streamlit_app.py
