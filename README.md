# recipe-generate

## Description
This project is a custom recipe generator that uses OpenAI's GPT-3.5-turbo model to generate recipes based on user-provided ingredients. Users can input a list of ingredients they have, and the application will generate a recipe using those ingredients.

## Installation
To set up the project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/itsmeneil23/recipe-generate.git
   cd recipe-generate
   ```

2. Create a virtual environment and activate it:
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```

3. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
To run the Flask application and use the web interface to generate recipes, follow these steps:

1. Set the `OPENAI_API_KEY` environment variable with your OpenAI API key:
   ```bash
   export OPENAI_API_KEY=your_openai_api_key
   ```

2. Run the Flask application:
   ```bash
   python api/main.py
   ```

3. Open your web browser and go to `http://localhost:8080` to access the web interface.

## Environment Variables
The following environment variables must be set:

- `OPENAI_API_KEY`: Your OpenAI API key.

## Vercel Deployment
The project is also deployed on Vercel. You can access it at the following domain:
[recipe-generate-psi.vercel.app](https://recipe-generate-psi.vercel.app)
