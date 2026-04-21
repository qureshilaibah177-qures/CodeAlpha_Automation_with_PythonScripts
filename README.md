# CodeAlpha_Automation_with_PythonScripts
A Python script that automates fetching a webpage's title using requests and saves it to a text file



### Internship Project - CodeAlpha Python Programming Task 3
This repository contains the solution for **Task 3: Task Automation with Python Scripts** as part of the CodeAlpha Python Programming Internship.

## Project Description
This Python script automates the task of extracting the `<title>` tag from any given webpage URL. It sends an HTTP request to the specified URL, parses the HTML content, extracts the page title, and saves it into a local `.txt` file with a timestamp.

This solves the real-life repetitive task of manually opening websites and copying their titles for documentation, research, or SEO records.

## Key Features

- **Automated Web Scraping**: Fetches HTML content from any hardcoded URL using `requests`
- **Title Extraction**: Parses HTML using `re` to find the `<title>` tag without heavy libraries
- **Timestamp Logging**: Saves title with date-time so you can track when it was scraped
- **Error Handling**: Handles `requests.exceptions.RequestException` for invalid URLs or no internet
- **Simple Output**: Saves result in `scraped_title.txt` for easy access

##  Tech Stack & Concepts Used
- **Language**: Python 3.x
- **Key Libraries**: `requests`, `re`, `os`, `datetime` for web requests, regex, and file handling
- **Core Concepts**: HTTP requests, Regular Expressions, File I/O, Exception Handling

## Folder Structure
