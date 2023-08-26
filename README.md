# Invoice Extraction LLM Bot 🤖

![image](https://github.com/prajwal-cn/Invoice-Extraction-LLM-Bot-Using-Langchain-Framework-OpenAI-and-Replicate-AI/assets/127007794/4407542f-2889-4eb0-ae58-c9de9876b520)


> A Streamlit-based web application to extract invoice data using a Language Model (LLAMA 2 70B).

## Table of Contents

- [About](#about)
- [Demo](#demo)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## About

The Invoice Extraction LLM Bot is a Streamlit-powered web application that leverages a Language Model (LLM) to extract key data from uploaded invoice PDFs. It provides a user-friendly interface for users to upload their invoices, and the bot processes the PDFs to extract essential information such as invoice number, description, quantity, date, unit price, amount, total, email, phone number, and address.

This project demonstrates the use of natural language processing and document parsing techniques to automate the extraction of structured data from unstructured PDF documents.

## Demo

<img width="911" alt="image" src="https://github.com/prajwal-cn/Invoice-Extraction-LLM-Bot-Using-Langchain-Framework-OpenAI-and-Replicate-AI/assets/127007794/16a9df70-c9d7-43bc-9f04-a79630181f0e">

## Getting Started

### Prerequisites

- Python 3.7 or higher
- pip package manager

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/invoice-extraction-llm-bot.git
   cd invoice-extraction-llm-bot
   ```

2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Run the Streamlit application:

   ```bash
   streamlit run app.py
   ```

2. Open your web browser and navigate to the URL provided by Streamlit (usually `http://localhost:8501`).

3. Upload one or more invoice PDFs.

4. Click the "Extract" button to initiate the data extraction process.

5. View the extracted data in a tabular format on the web page.

6. Optionally, download the extracted data as a CSV file.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, follow these steps:

1. Fork the repository.

2. Create a new branch for your feature or bug fix:

   ```bash
   git checkout -b feature/your-feature-name
   ```

3. Make your changes and commit them:

   ```bash
   git commit -m "Add your commit message here"
   ```

4. Push your changes to your fork:

   ```bash
   git push origin feature/your-feature-name
   ```

5. Create a pull request describing your changes.

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

For questions or inquiries, feel free to contact me at cnprajwal.official@email.com.
