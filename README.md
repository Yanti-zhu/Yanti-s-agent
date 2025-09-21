##Yanti's AI Agent

Sales Analyst AI Agent (Databricks)
📌 Overview

This project is a Sales Analyst AI Agent built in Databricks. It uses natural language queries and translates them into SQL function calls, providing data-driven sales insights such as revenue trends, customer purchases, and top-selling products.

The agent was designed as part of my personal portfolio to demonstrate how AI orchestration and data engineering can be combined to build intelligent, query-driven business tools.

🔧 Features

System Prompt Design >> guides the agent to prefer function calls over guesses for accuracy.

Reusable SQL Functions:

fn_monthly_revenue >> monthly revenue trends.

fn_customer_purchases >> purchase history for customers.

fn_query_sales >> sales data with customer/product details.

fn_top_products_by_year >> top-N products by year.

fn_top_months_by_year >> highest revenue months per year.

fn_customer_by_year >> top customers by revenue.

Agent Orchestration >> dynamically picks the right function, runs it, and summarises results.

Playground Integration >> deployed in Databricks Playground for interactive Q&A.

🛠️ Tech Stack

Databricks: Playground, SQL functions, Delta tables
AI Concepts: Prompt engineering, function calling, agent orchestration
Data Engineering: Schema design, parameterised queries

✅ Outcome

Built a working AI agent that answers business sales questions in natural language.
Demonstrates how AI + SQL functions can deliver reliable insights at scale.
Serves as a portfolio project showcasing applied skills in Databricks, AI, and product thinking.