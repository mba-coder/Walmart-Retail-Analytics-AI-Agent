# Walmart Retail Analytics AI Agent

## Overview

This project demonstrates how AI-assisted analytics can transform retail sales data into actionable business insights.

Using Walmart's historical weekly sales dataset, I developed an AI-powered analytics agent capable of answering business questions related to:

* Sales Performance
* Inventory Risk Detection
* Store Performance Monitoring
* Holiday Impact Analysis
* Economic Factor Analysis

The agent converts natural language business questions into automated analytical workflows and returns executive-friendly recommendations.

---

## Business Problem

Retail managers and inventory planners often spend significant time manually analyzing reports to understand:

* Why sales increased or decreased
* Which stores are underperforming
* Potential stockout or overstock risks
* Holiday demand impacts
* External economic influences

The goal of this project was to create an AI-assisted decision-support tool that automates these analyses and provides business-focused recommendations.

---

## Features

### Sales Diagnostics

Examples:

* Why did Store 20 sales decrease this week?
* Why did Store 15 sales increase?

Metrics:

* Week-over-Week (WoW) Sales Change
* Year-over-Year (YoY) Sales Change
* Rolling 4-Week Trends
* Rolling 12-Week Trends

---

### Inventory Optimization

The dataset does not contain actual inventory levels.

To address this, statistical anomaly detection was implemented using Z-score analysis to identify:

* Potential Stockout Risk
* Potential Overstock Risk

Examples:

* Which stores have stockout risk?
* Which stores are overstocked?

---

### Store Performance Monitoring

Stores are classified into:

* Top Tier
* Average
* Underperforming

Based on:

* Total Sales
* Average Weekly Sales
* Sales Volatility
* Negative Sales Weeks

Examples:

* Which stores are underperforming?
* Show me the top stores.

---

### Holiday Impact Analysis

Measures:

* Holiday Sales Lift
* Average Holiday Sales
* Average Non-Holiday Sales

Example:

* What is the holiday impact on sales?

---

### Economic Factor Analysis

Evaluates relationships between:

* Fuel Prices
* CPI
* Unemployment
* Temperature

Example:

* How did fuel prices impact sales?

---

## AI Usage

Generative AI was used throughout the project to:

* Accelerate Python development
* Generate analytical frameworks
* Assist with data cleaning workflows
* Create natural language question-answering logic
* Generate business insight templates

My role focused on:

* Defining the business problem
* Designing KPIs and analytical logic
* Validating outputs
* Refining business recommendations
* Structuring the AI-assisted workflow

---

## Sample Questions

* Why did Store 20 sales decrease this week?
* Which stores are underperforming?
* Which stores are overstocked?
* Which stores have stockout risk?
* What is the holiday impact?
* How did fuel prices impact sales?

---

## Technologies Used

* Python
* Pandas
* NumPy
* Jupyter Notebook
* Generative AI
* Statistical Analysis

---

## Future Enhancements

* Power BI Dashboard
* Streamlit Web Application
* GPT Integration
* Sales Forecasting
* Executive Summary Generation
* Regional Performance Analysis

---

## Business Value

The solution demonstrates how AI-assisted analytics can reduce manual reporting effort and provide faster, data-driven decision support for retail operations teams.
