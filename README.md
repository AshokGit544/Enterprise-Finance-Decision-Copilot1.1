

##Project Overview

This project builds an **Enterprise Finance Decision Copilot** that processes SAP FICO-style finance data and transforms it into **AI-ready, decision-driven insights

The system integrates invoices, payments, vendors, purchase orders, and policies into a unified dataset, applies data quality checks, detects risks, and generates **recommended actions with clear reasoning**. It also enables **semantic search using embeddings** to support intelligent query-based analysis.

## 🎯 Objective

To convert raw finance data into:

* Clean and reliable datasets
* Risk-aware decision outputs
* Retrieval-ready documents
* Semantic search-enabled insights
* Policy-aware decision intelligence

## ⚙️ Key Features

* SAP FICO-style data generation (vendors, invoices, payments, POs, policies)
* Data integration using common business key
* Data quality validation framework
* Risk detection (high amount, late payment, vendor risk, missing PO, duplicates)
* Decision recommendation engine with reasoning
* Retrieval-ready document creation
* Embedding generation using Sentence Transformers
* Semantic search for invoices and policies
* Decision Copilot for intelligent responses

## 🧠 How It Works (Simple Flow)

1. Generate enterprise finance datasets
2. Integrate all data into one unified view
3. Perform data quality checks
4. Create common business keys
5. Detect risks and assign flags
6. Generate recommended actions with reasons
7. Convert data into retrieval-ready text
8. Create embeddings for semantic understanding
9. Enable search and decision-based responses


## 📊 Results Summary

The pipeline processed **300 finance records** and created a fully integrated dataset using a common business key. It identified **4 data quality issues**, including missing vendor, invalid amount, missing description, and missing purchase order. The system generated **300 retrieval-ready documents** and **30 policy documents** for semantic search.

A decision intelligence layer evaluated all records and detected risks such as high invoice amount, late payment, missing PO, and duplicate invoices. Based on these conditions, the system automatically assigned actions like monitoring, analyst investigation, or escalation, along with clear reasoning for each decision.

This demonstrates how enterprise finance data can be transformed into **actionable, AI-ready insights for business decision-making**.

## 📂 Output Files

* `integrated_finance_view.csv` → Unified finance dataset
* `data_quality_issues.csv` → Identified data issues
* `retrieval_ready_documents.csv` → AI-ready invoice text
* `policy_retrieval_documents.csv` → Policy text data
* `decision_summary.csv` → Recommended actions and reasoning
* `invoice_embeddings.npy` → Invoice embeddings
* `policy_embeddings.npy` → Policy embeddings


## 🔍 Example Use Case

User Query:

```
high risk invoice with missing PO and late payment
```

System Output:

* Identifies relevant invoices
* Shows risk flags (late payment, missing PO, etc.)
* Recommends actions (investigate / escalate)
* Provides matching policies

---

## 🚀 Business Value

* Improves finance data reliability
* Enables faster decision-making
* Identifies risks early
* Supports audit and compliance
* Converts data into AI-ready insights

---

## 🏁 Conclusion

This project demonstrates how traditional finance data pipelines can be enhanced with **AI-driven decision intelligence and semantic search**, enabling organizations to move from data processing to **intelligent, actionable insights**.
