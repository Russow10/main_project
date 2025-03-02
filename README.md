# Streamlit App

A Streamlit application for analyzing audio files, counting Capuchin calls, and providing insights through an RAG-powered chatbot.

## Features

- Upload an audio file and play it
- Count Capuchin calls and perform general audio analysis
- RAG-powered chatbot for discussing project details and results

## Installation

1. Clone this repository:

    git clone https://github.com/Russow10/main_project.git
    cd main_project

2. Install the required dependencies:

    pip install -r requirements.txt

3. Set up your environment variables in the `.env` file.

## Usage

Run the application with:

    streamlit run app.py

## Project Structure

- `app.py`: Main application entry point
- `pages/`: Additional pages for the Streamlit application
- `docs/`: Documentation files
- `chroma_db/` and `temp_chroma_db/`: Database files
- `weights/`: Model weights

## License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Feel free to submit a Pull Request.
