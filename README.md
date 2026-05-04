# IT22073600_ITPM-Assignment
Transliteration Accuracy Testing (Singlish to Sinhala)

# IT3040-ITPM Assignment 1: Transliteration Accuracy Testing

**Student ID:** IT22073600  
**Module:** IT3040 - Information Technology Project Management (Year 3, Semester 1)  
**Project:** Option 1 - Transliteration Accuracy Testing (Singlish to Sinhala)

## 📌 Project Overview
This repository contains the automated test scripts required for Assignment 1. The objective is to evaluate the accuracy of the [Pixelssuite Chat Translator](https://www.pixelssuite.com/chat-translator) when converting chat-style Singlish input into Sinhala. 

The automation is built using **Python** and **Playwright**. It automatically feeds 50 specific negative test cases (covering 24 distinct Singlish linguistic rules) into the live application, extracts the actual transliterated output, and records the results into a formatted Excel spreadsheet.

## 📂 Repository Structure
* `test_automation.py` - The main Python Playwright automation script.
* `Assignment 1 - Test cases.xlsx` - The Excel dataset containing the 50 inputs, expected outputs, Singlish categories, rationales, and the dynamically generated actual outputs.
* `README.md` - Setup and execution instructions.

## ⚙️ Prerequisites
Before running the automation, ensure you have the following installed:
* **Python** (v3.8 or higher)
* **Git** (to clone the repository)
* **Microsoft Excel** (to view the output data)

## 🚀 Installation & Setup

**1. Clone the repository**
```bash
cd <IT22073600_ITPM>
