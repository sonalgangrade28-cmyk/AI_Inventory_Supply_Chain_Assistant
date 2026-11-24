
# 📦 AI Inventory & Supply Chain Assistant

## 1. Project Overview

The AI Inventory & Supply Chain Assistant is a web-based application developed using Python, Streamlit, and Google Gemini AI.

The application helps businesses manage inventory efficiently, monitor stock levels, identify low-stock products, generate reorder recommendations, and obtain AI-powered supply chain insights.

It uses Generative AI to analyze inventory information and provide intelligent business recommendations through an interactive AI chatbot.

## 2. Project Objectives

- To simplify inventory management through automation.
- To identify products that require immediate restocking.
- To calculate inventory value and monitor stock availability.
- To generate intelligent reorder recommendations.
- To provide AI-powered inventory and supply chain insights.
- To support better business decisions and reduce stock shortages.

## 3. Technologies Used

| Technology | Purpose |
|---|---|
| Python | Backend programming |
| Streamlit | Web application development |
| Google Gemini AI | Generative AI and business recommendations |
| Pandas | Data processing and analysis |
| NumPy | Numerical operations |
| Plotly | Interactive charts and visualizations |
| OpenPyXL | Excel file processing |
| CSV | Inventory dataset management |

## 4. Key Features

### 4.1 Interactive Dashboard
- Total number of products.
- Total available stock quantity.
- Total inventory value.
- Low-stock product count.
- Inventory analytics and visualizations.

### 4.2 Inventory Management
- Upload inventory data through CSV or Excel.
- View all product records.
- Search products by name.
- Calculate stock value automatically.

### 4.3 Low Stock Alerts
- Identify products below their reorder level.
- Display stock shortage information.
- Highlight products requiring attention.

### 4.4 Smart Reorder Recommendations
- Calculate suggested purchase quantities.
- Identify products requiring replenishment.
- Generate downloadable reorder reports.

### 4.5 AI Inventory Assistant
Powered by Google Gemini AI.

Users can ask questions such as:
- Which products need immediate reordering?
- Which category has the highest inventory value?
- What are the major inventory risks?
- Which suppliers provide low-stock products?
- How can inventory management be improved?

### 4.6 AI Demand Planning
- Generate product-level demand planning assessments.
- Identify potential stock shortage risks.
- Obtain replenishment suggestions.
- Receive supplier planning recommendations.

Note: Accurate demand forecasting requires historical sales and demand data.

### 4.7 Reports and Downloads
- Download complete inventory reports.
- Export low-stock reports.
- Generate Excel reports.
- Download reorder recommendations.

## 5. Project Folder Structure

```text
AI_Inventory_Supply_Chain_Assistant/
│
├── app.py
├── requirements.txt
├── README.md
├── .env
├── .gitignore
│
├── data/
│   └── inventory.csv
│
└── modules/
    ├── __init__.py
    ├── inventory.py
    ├── analytics.py
    └── ai_assistant.py
```

## 6. Dataset Description

The application uses an inventory dataset containing the following fields:

| Column | Description |
|---|---|
| Product Name | Name of the product |
| Category | Product category |
| SKU | Unique product identification |
| Quantity | Available stock quantity |
| Unit Price | Price per unit |
| Supplier | Supplier name |
| Reorder Level | Minimum stock threshold |
| Warehouse Location | Storage location |

Sample product categories include:
- Personal Care
- Food and Beverages
- Home Care
- FMCG Products

## 7. Installation and Setup

### Step 1: Clone or Download the Project

Download the project folder to your computer.

### Step 2: Install Required Libraries

Open the terminal and execute:

```bash
pip install -r requirements.txt
```

### Step 3: Configure Gemini API Key

Create a `.env` file in the project directory.

Add your Google Gemini API key:

```env
GEMINI_API_KEY=your_actual_api_key
```

Get your API key from:

https://aistudio.google.com/apikey

### Step 4: Run the Application

Execute the following command:

```bash
python -m streamlit run app.py
```

### Step 5: Open the Application

Open your browser and visit:

http://localhost:8501

## 8. Application Workflow

1. Upload inventory data using CSV or Excel.
2. The system processes inventory records using Python and Pandas.
3. Inventory KPIs and analytics are generated.
4. Low-stock products are identified automatically.
5. Reorder quantities are calculated.
6. Google Gemini AI analyzes inventory information.
7. Users receive AI-powered business recommendations.
8. Reports can be downloaded for further analysis.

## 9. Future Scope

The application can be enhanced with the following functionalities:

- Machine Learning-based demand forecasting.
- Supplier performance evaluation.
- Automated purchase order generation.
- Real-time inventory tracking.
- Warehouse management integration.
- Database connectivity using MySQL or SQLite.
- User authentication and role-based access.
- Advanced inventory optimization.
- Automated stock shortage notifications.

## 10. Expected Outcomes

The proposed system aims to:

- Improve inventory visibility.
- Reduce manual inventory monitoring.
- Minimize stock shortage risks.
- Improve replenishment planning.
- Support supplier-related decisions.
- Provide intelligent business insights.

## 11. Project Conclusion

The AI Inventory & Supply Chain Assistant demonstrates how Generative AI can be integrated into inventory and supply chain management.

By combining Python, Streamlit, and Google Gemini AI, the application provides an interactive platform for inventory analysis, stock monitoring, reorder recommendations, and AI-assisted business decision-making.

The project highlights the practical application of Generative AI in improving operational efficiency and supporting data-driven business decisions.

---

## 12. Developer Information

**Project Name:** AI Inventory & Supply Chain Assistant

**Project Type:** MBA Generative AI Project

**Development Language:** Python

**AI Model:** Google Gemini

**Frontend Framework:** Streamlit

**Domain:** Inventory Management and Supply Chain Analytics
