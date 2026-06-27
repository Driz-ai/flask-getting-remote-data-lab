# GetRequester Project

## 📌 Project Overview

This project demonstrates how to fetch data from a remote API endpoint using Python, then convert the returned JSON response into usable Python data structures.

It uses the `requests` library to make HTTP GET requests and the built-in `json` module to parse the response.

---

## 🚀 Features

- Sends a GET request to a remote URL
- Retrieves raw response data
- Converts JSON response into Python objects (lists/dictionaries)
- Includes automated tests to verify functionality

---

## 🧠 How It Works

The `GetRequester` class:

1. Accepts a URL when initialized
2. Fetches data from the URL using `requests.get()`
3. Returns the raw response body (`bytes`)
4. Converts JSON response into Python objects using `json.loads()`


## ✅ Test Results Screenshot

![Successful Test Run](./images/remote.png)

---


---

If you want, I can also:
- rename your files to match industry standards
- or help you turn this into a GitHub-ready submission (branch + PR description included)

## 📦 Installation

Install required dependency:

```bash
pip install requests