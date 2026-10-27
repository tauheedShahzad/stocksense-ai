# StockSense AI

### An AI-Based Inventory Verification and Demand Forecasting System with LLM-Powered Agent Integration

## Overview

StockSense AI is an intelligent inventory management and analysis system designed to support stock monitoring, inventory verification, anomaly detection, and demand forecasting. The system combines traditional inventory management functionality with machine learning techniques and a Large Language Model (LLM)-powered agent to provide a more accessible and data-driven approach to inventory management.

The proposed system will enable users to manage product records, monitor stock movements, identify unusual inventory activities, and estimate future demand using historical data. An interactive dashboard will present key inventory information, while the integrated AI agent will allow users to retrieve inventory insights and interact with the system through natural-language queries.

## Objectives

- Develop a centralized system for managing inventory records and stock transactions.
- Monitor available stock quantities and identify products requiring replenishment.
- Apply machine learning techniques to flag unusual inventory movements for further review.
- Forecast future product demand using historical inventory data.
- Provide an interactive dashboard for inventory monitoring and analysis.
- Integrate an LLM-powered agent to support natural-language queries and generate inventory summaries.
- Evaluate the system through functional testing and experiments using simulated inventory data.

## Key Features

### 1. Inventory Management
Maintain product information, track stock quantities, and record stock-in and stock-out transactions. Transaction history will support inventory verification and stock movement analysis.

### 2. Inventory Anomaly Detection
Use suitable data analysis and machine learning techniques to identify potentially unusual stock movements. The system will generate alerts for review rather than treating detected anomalies as confirmed errors.

### 3. Demand Forecasting
Analyse historical inventory or sales data to estimate future product demand. Forecasting results will support inventory planning and replenishment decisions.

### 4. Interactive Dashboard
Provide a dashboard displaying inventory summaries, current stock levels, low-stock alerts, unusual stock activity, and demand forecasting results.

### 5. LLM-Powered Inventory Assistant
Integrate an existing Large Language Model to allow users to ask inventory-related questions in natural language. The assistant will use predefined application functions to retrieve relevant information, explain system-generated results, and summarise inventory insights.

### 6. Low-Stock Monitoring
Compare available stock quantities against defined minimum stock levels and highlight products that may require replenishment.

## Technology Stack

- **Programming Language:** Python
- **Web Application Framework:** Streamlit
- **Data Processing:** Pandas
- **Machine Learning:** Scikit-learn
- **Database:** SQLite
- **AI Integration:** Existing Large Language Model (LLM) through a compatible API or interface
- **Development and Testing:** Simulated inventory datasets

## System Architecture

The proposed system will consist of the following components:

1. **Data Layer:** Stores product records and inventory transactions in an SQLite database.
2. **Inventory Management Module:** Handles stock records, stock movements, and quantity updates.
3. **Analytics and Machine Learning Module:** Processes inventory data for anomaly detection and demand forecasting.
4. **Dashboard Module:** Displays inventory summaries, alerts, and analytical results.
5. **LLM Agent Module:** Connects natural-language queries with predefined application functions and presents relevant inventory information.

The application will handle stock calculations and database operations, while the LLM agent will assist with information retrieval and explanations.

## Implementation Approach

The system will be developed incrementally, beginning with inventory management and database functionality. Data processing and analytical components will then be implemented, followed by dashboard development and LLM agent integration.

Simulated inventory data will be used to support development and testing. Appropriate methods will be selected for anomaly detection and demand forecasting based on the available data and project requirements. Functional testing will be conducted to verify core operations and assess the behaviour of the analytical components.

## Project Scope

StockSense AI is an individual undergraduate Final Year Project focused on developing a practical inventory management prototype. The project will demonstrate how inventory tracking, machine learning-based analysis, demand forecasting, and LLM-powered interaction can be integrated into a single application.

The implementation will remain focused on a manageable academic scope. The project will use an existing LLM rather than training a language model from scratch. The accuracy and usefulness of anomaly detection and forecasting will depend on the quality and availability of the underlying data.

## Expected Outcomes

The project is intended to deliver an integrated prototype that supports inventory record management, stock monitoring, anomaly alerts, demand estimation, dashboard-based analysis, and natural-language interaction through an LLM-powered agent.

The resulting system will demonstrate the potential of combining conventional inventory management with machine learning and language-model capabilities to support inventory-related decision-making.

## Academic Information

- **Degree Program:** BS Information Technology
- **Project Type:** Individual Final Year Project
