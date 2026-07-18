# WEB-SCRAPING-PROJECT-USING-BEAUTIFULSOUP

# 🕸️ Python Job Scraper using BeautifulSoup

A beginner-friendly Python web scraping project that extracts the latest Python job listings from **TimesJobs** using **BeautifulSoup** and **Requests**. The program filters out jobs containing skills you are not interested in and displays only recently posted jobs.

---

## 📌 Features

- Scrapes Python job listings from TimesJobs
- Filters jobs based on user-defined unwanted skills
- Displays only recently posted jobs
- Shows:
  - Company Name
  - Required Skills
  - Published Date
  - Job Link
- Automatically checks for new jobs every 10 minutes

---

## 🛠️ Technologies Used

- Python 3
- BeautifulSoup4
- Requests
- lxml

---

## 📂 Project Structure

```
Python-Job-Scraper/
│
├── job_scraper.py
├── README.md
└── requirements.txt
```

---

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/your-username/python-job-scraper.git
```

Go to the project directory:

```bash
cd python-job-scraper
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

Or install manually:

```bash
pip install beautifulsoup4 requests lxml
```

---

## ▶️ How to Run

Run the Python file:

```bash
python job_scraper.py
```

Example:

```
Put some skills that you are not familiar with
> django

Filtering out django

Company Name : ABC Technologies
Required Skills : Python, SQL, Flask
Published : Posted few days ago
More Info : https://www.timesjobs.com/...
```

The program automatically checks for new jobs every **10 minutes**.

---

## 🧠 How It Works

1. Downloads the TimesJobs webpage.
2. Parses the HTML using BeautifulSoup.
3. Finds all job postings.
4. Filters jobs posted within the last few days.
5. Removes jobs containing unwanted skills entered by the user.
6. Displays the remaining job information.
7. Repeats the process every 10 minutes.

---

## 📚 Concepts Practiced

- Web Scraping
- HTTP Requests
- HTML Parsing
- BeautifulSoup
- Python Functions
- Loops
- Conditional Statements
- String Manipulation
- User Input
- Time Module
- Automation

---

## 📸 Sample Output

```
Put some skills that you are not familiar with
> react

Filtering out react

Company Name : XYZ Pvt Ltd
Required Skills : Python, Flask, SQL
Published : Posted few days ago
More Info : https://www.timesjobs.com/...
```

---

## ⚠️ Note

This project is created for **educational purposes** to practice Python web scraping. Website structures may change over time, which can require updating the HTML selectors used in the scraper.

---

## 🚀 Future Improvements

- Export jobs to CSV or Excel
- Save data into a database
- Email notifications for new jobs
- Desktop notifications
- Search multiple job roles
- Add location-based filtering
- Create a Streamlit web interface

---

## 🤝 Contributing

Contributions are welcome!

Feel free to fork this repository, improve the project, and submit a pull request.

---

## 📄 License

This project is licensed under the MIT License.

---

## ⭐ If you found this project helpful

Give this repository a ⭐ on GitHub to support the project!
