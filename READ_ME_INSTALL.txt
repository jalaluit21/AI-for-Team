USE : 

POWERSHELL commande.
https://vscode.dev/

1. Setup:*
   - Install Python and Flask.
   - Install OpenAI's Python package.

*2. Create a Flask Application:*
   - Initialize a Flask app.
   - Define a route to render the homepage and a route to handle GPT-4 API requests.

*3. GPT-4 API Integration:*
   - Securely store your API key (use environment variables).
   - Create a function to send prompts to the OpenAI API and return responses.

### Frontend (HTML/CSS)

*1. Create a Simple Web Page:*
   - Design a basic HTML page with a form for inputting prompts.
   - Style the page using CSS for a clean and user-friendly interface.
### Step 1: Install Required Software

1. *Install Python:*
   - Go to the [Python official website](https://www.python.org/downloads/).
   - Download the latest version of Python for your operating system (Windows, MacOS, Linux).
   - Run the installer and follow the instructions. Make sure to check the box that says "Add Python to PATH" during installation.

2. *Install a Code Editor:*
   - Download and install [Visual Studio Code](https://code.visualstudio.com/) or any preferred code editor.

### Step 2: Set Up the Project

1. *Create a New Folder:*
   - On your computer, create a new folder where your project will reside. You can name it something like grant_ai_tool.

2. *Open the Folder in Your Code Editor:*
   - Open Visual Studio Code.
   - Go to File -> Open Folder and select the folder you created.

3. *Open a Terminal in the Code Editor:*
   - In Visual Studio Code, go to Terminal -> New Terminal.

4. *Create a Python Virtual Environment (optional but recommended):*
   - In the terminal, type python -m venv venv and press Enter. This creates a virtual environment named venv in your project folder.
   - To activate the virtual environment, on Windows type venv\Scripts\activate, or on MacOS/Linux type source venv/bin/activate.

5. *Install Flask and OpenAI:*
   - In the terminal, type pip install Flask openai and press Enter.
### Step 2: Run the Application

1. *Start the Flask Server:*
   - In the terminal (make sure your virtual environment is activated if you created one), type python app.py and press Enter.
   - Flask will start a local server.

2. *Access the Application:*
   - Open a web browser and go to http://127.0.0.1:5000/.
   - You should see the grant writing AI tool interface.

