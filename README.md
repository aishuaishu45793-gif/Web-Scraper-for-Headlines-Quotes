# 📰 Web Scraper for Headlines & Quotes

## 📌 Project Overview

The **Web Scraper for Headlines & Quotes** is a Python-based web scraping project that extracts quotes, authors, and tags from a website and saves the collected information in JSON and TXT formats.

This project demonstrates how to send HTTP requests, parse HTML content, extract specific information using BeautifulSoup, and store the extracted data in structured files.

## 🎯 Objectives

- Fetch website content using Python Requests.
- Parse HTML using BeautifulSoup.
- Extract quotes, authors, and tags.
- Navigate through multiple pages using pagination.
- Save extracted data in JSON and TXT files.
- Display basic scraping statistics.

## 🛠️ Technologies Used

- **Python** – Programming language.
- **Requests** – To send HTTP requests.
- **BeautifulSoup** – To parse HTML and extract information.
- **JSON** – To store structured data.
- **TXT** – To save extracted text data.

## 🌐 Website Used

Practice website: https://quotes.toscrape.com/

This website is designed for learning and practicing web scraping.

## 📂 Project Structure

```text
Web-Scraper-for-Headlines-Quotes/
│
├── scraper.py
├── requirements.txt
├── README.md
├── .gitignore
│
└── output/
    ├── quotes.json
    └── quotes.txt
```

## ⚙️ Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/aishuaishu45793-gif/Web-Scraper-for-Headlines-Quotes.git
```

### 2. Navigate to the Project Folder

```bash
cd Web-Scraper-for-Headlines-Quotes
```

### 3. Create a Virtual Environment

```bash
python -m venv venv
```

### 4. Activate the Virtual Environment

For Windows PowerShell:

```powershell
.\venv\Scripts\Activate
```

### 5. Install Required Libraries

```bash
pip install -r requirements.txt
```

If needed, install the libraries manually:

```bash
pip install requests beautifulsoup4
```

## ▶️ How to Run

Run the following command:

```bash
python scraper.py
```

The scraper will fetch the website content, extract quotes and related information, and save the results in the output folder.

## 📊 Output Files

After successful execution, the project generates:

- **quotes.json** – Stores quotes, authors, and tags in structured JSON format.
- **quotes.txt** – Stores extracted quotes and author information in readable text format.

## 📈 Features

- Automated web scraping.
- HTML parsing and data extraction.
- Quote and author collection.
- Tag extraction.
- Multi-page scraping.
- JSON and TXT file generation.
- Basic scraping statistics.

## 🎓 Learning Outcomes

Through this project, I learned:

- How web scraping works.
- How to use Python Requests.
- How to inspect and understand HTML elements.
- How to extract data using BeautifulSoup.
- How to work with JSON and text files.
- How to organize and manage a Python project.

## 👩‍💻 Author

**Aishwarya**

GitHub: https://github.com/aishuaishu45793-gif

## 📌 Project Repository

https://github.com/aishuaishu45793-gif/Web-Scraper-for-Headlines-Quotes

---

⭐ If you find this project useful, feel free to explore the repository!
