# Canoo_Research

## Overview
This repository contains the Python notebook `main.ipynb` used for the 2024 Internship Assignment Coding Challenge, focusing on AI/ML Engineering for an internship at Lizmotors Mobility Pvt Ltd.

## Project Description
The project involves using Google's Gemini Pro AI model to gather and analyze information on various aspects of Canoo, a company in the automobile industry. The notebook `main.ipynb` includes a Python script designed to perform the following tasks:

### 1. Set Up Environment
   - Installation of the latest version of the `google-generativeai` package.

### 2. Python Script
   - Import necessary libraries including `json` and `google.generativeai`.
   - Configuration of the Gemini Pro API key.
   - Definition of a function `query_gemini_pro` to interact with the Gemini Pro model.
   - Creation of prompts related to Canoo's industry information, competitor analysis, market trends, and financial performance.
   - Collection and storage of responses from the Gemini Pro model in a JSON file (`gemini_pro_responses.json`).

### 3. Summary of Steps
   - Detailed explanation of the steps taken in the script, from setting up the environment to collecting and saving responses.

### 4. Challenges and Solutions
   - Discussion of potential challenges such as API key security, error handling, rate limiting, API response validation, and dependency management, along with proposed solutions.

## Usage
Replace the placeholder API key in the script with a valid Gemini Pro API key to use the notebook.
