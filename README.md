# Personal Assistant

Welcome to the Personal Assistant repository! This Python-based application is designed to answer any of your questions using the Google Gemini API. 

## Features

- Answer questions on a wide range of topics
- Utilizes the powerful Gemini Pro model from Google
- Simple and easy-to-use interface

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

- Python 3.6 or higher
- pip (Python package installer)
- IDE
  
### Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/yourusername/Personal-Assistant.git
    cd Personal_Assistant
    ```

2. **Install the required packages:**

    ```bash
    pip install -r requirements.txt
    ```

3. **Set up your Google API Key:**

    - Visit the [Google Gemini site](https://cloud.google.com/gemini) to obtain your API key.
    - Open the `Personal_Assistant.ipynb` file in the root directory of the repository.
    - Replace the `GOOGLE_API_KEY` variable with your own API key:

    ```python
    GOOGLE_API_KEY = 'your-api-key-here'
    ```

### Usage

Once you have set up your API key, you can start using the Personal Assistant:

1. **Run all the code in the file named:**

    ```bash
   Personal_Assistant.ipynb
    ```

2. **Ask a question:**

    The application will prompt you to enter a question. Simply type your question and press Enter. The assistant will provide you with an answer and an audio using the Gemini Pro model.

### Example

```bash
Enter your question: What is the capital of France?
Answer: The capital of France is Paris.
Audio of the given answer.
```

## Contributing

We welcome contributions to enhance the functionality of this project. To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add new feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Create a new Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgements

- [Google Gemini](https://cloud.google.com/gemini) for providing the API used in this project.

---

Thank you for using Personal Assistant! If you have any questions or feedback, please feel free to open an issue or contact us.

---

Happy coding!
