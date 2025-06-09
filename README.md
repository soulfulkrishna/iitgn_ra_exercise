# iitgn_ra_exercise

This repository contains the deliverables for the Research Associateship exercise at the Department of Computer Science & Engineering, IIT Gandhinagar.

**Name:** Krishna Bhatia  
**LLM Used:** Groq Playground with meta-llama/llama-4-scout-17b-16e-instruct  

## Overview

Leveraging a Large Language Model to translate natural-language questions into pandas code, this project analyzes the UCI Household Power Consumption dataset. All seven required queries are posed in plain English, auto-translated by the LLM into executable Python, and verified in a Jupyter Notebook.

## Summary of Tasks Completed

1. **Average active power consumption in March 2007**  
2. **Hour of the day with highest power usage on December 25, 2006**  
3. **Comparison of global active power on weekdays vs. weekends**  
4. **Identification of days when consumption exceeded 5 kWh**  
5. **Trend plot of energy usage for January 1–7, 2007**  
6. **Daily average voltage for February 1–7, 2007**  
7. **Correlation analysis between global active power and sub-metering values**  

## Repository Structure

<pre markdown> ```text . ├── README.md ├── household_power_consumption.txt # Raw dataset from UCI ├── llm_queries_results.ipynb # Notebook with: │ ├── Data loading and preprocessing │ ├── LLM-generated pandas code │ ├── Verified outputs & metrics │ └── Matplotlib visualizations └── llm_queries_prompts.ipynb # Natural-language prompts ``` </pre>
