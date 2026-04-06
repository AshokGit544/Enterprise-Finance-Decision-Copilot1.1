# Enterprise Finance Decision Copilot

An AI-powered system that transforms raw finance data into **risk-aware decisions, semantic search insights, and explainable outputs**.

---

##  Objective

Convert finance data into:

- Clean and validated datasets  
- Risk-based decision outputs  
- Semantic search insights  
- Explainable decision summaries  

---

## How It Works

1. Generate finance datasets (invoices, vendors, payments, policies)  
2. Integrate data using a common business key  
3. Perform data quality checks  
4. Detect risks (high amount, late payment, missing PO, etc.)  
5. Generate recommended actions with reasons  
6. Create embeddings for semantic search  
7. Retrieve relevant results  
8. Produce decision explanations  

---

## Results Summary

- Total Records Processed: **300**  
- Data Quality Issues: **4**  
- Retrieval Documents: **300**  
- Policy Documents: **30**  
- Decision Outputs: **300**

---

##  Data Quality Issues

| Invoice ID | Issue |
|-----------|------|
| INV00004 | Missing vendor_id |
| INV00008 | Invalid amount |
| INV00011 | Missing description |
| INV00026 | Missing po_id |

---

## Decision Output 

| Invoice | Action | Reason |
|--------|-------|--------|
| INV00001 | Escalate | high amount + late payment |
| INV00002 | Investigate | high amount + late payment |
| INV00003 | Monitor | late payment |

---

##  Semantic Search Example

**Query:**  
`high risk invoice with missing po and late payment`

**Top Results:**

- INV00226 → Score: 0.50  
- INV00182 → Score: 0.50  
- INV00278 → Score: 0.50  

---

## 🤖 Decision Copilot Output
