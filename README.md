# Blog Generator using LLama 2 Model

This repository contains a Streamlit application that generates blogs using the LLama 2 model from Hugging Face. The application allows users to input a blog topic, specify the number of words, and select the target audience for the blog.

## Features

- Generate blogs for various target audiences including researchers, data scientists, college students, and AI engineers.
- Customize the number of words in the generated blog.
- User-friendly interface powered by Streamlit.

## Technologies Used

- **Streamlit**: For creating the web application.
- **Hugging Face**: For accessing the LLama 2 model.
- **Langchain**: For managing the prompt template and model interactions.
- **Python**: As the programming language.

## Installation

1. Clone the repository to your local machine:
   ```sh
   git clone https://github.com/yourusername/blog-generator.git

2. Navigate to the project directory:
  ```sh
  cd blog-generator

3. Create and activate a virtual environment:

```sh

python3 -m venv venv
source venv/bin/activate

4. Install the required packages:

```sh
pip install -r requirements.txt

5. Add your Hugging Face token:

```sh
# Replace "your_hugging_face_token" with your actual token
login(token="your_hugging_face_token")
Usage
6. Run the Streamlit application:

```sh
streamlit run app.py
 7. Open the provided URL in your web browser.

Enter the blog topic, specify the number of words, select the target audience, and click "Generate" to get the blog.

