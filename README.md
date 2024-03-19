# End-to-End-Nutritionist-Generative-AI-DoCtor-

# Health track System

This is a Streamlit web application designed to analyze images of food items and provide information about their calorie content using Google's Generative AI.


## Installation

1. Clone the repository:

```bash
git clone https://github.com/<usuario>/<nombre-del-repositorio>.git
cd <nombre-del-repositorio>

```
2. Install the required dependencies:
```bash
pip install -r requirements.txt
```
3. Set up environment variables:

Create a .env file in the root directory of the project.
Add your Google API key to the .env file:

```bash
GOOGLE_API_KEY=<your_google_api_key>
```

## Usage
1. Run the Streamlit app:
```bash
streamlit run app.py
```
2. Access the application via the provided URL.

3. Input Prompt: Enter a prompt describing the food items to be analyzed.

4. Choose an Image: Upload an image containing the food items.

5. Tell me the total calories: Click this button to analyze the image and get the total calorie count.

6. Show prompt explanation: Check this box to view an explanation of the expected input prompt format.


## Application Features

- Input Prompt: Users can enter a prompt describing the food items.

- Choose an Image: Users can upload an image containing the food items to be analyzed.

- Total Calories: The application provides the total calorie count of the food items in the uploaded image.

- Prompt Explanation: Users can view an explanation of the expected input prompt format.


## Dependencies

- Streamlit

- PIL

- Google Generative AI

## Acknowledgements
This application utilizes Google's Generative AI for content generation and follows the recommendations of @krishnaik06.