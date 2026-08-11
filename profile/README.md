<div align="center">
  <img src="https://images.squarespace-cdn.com/content/v1/607861b10c0e3b4816f56581/3eea3ca7-58ca-402d-9edf-b8e9e72eca3c/lightning.png?format=300w" alt="Photon Commerce">

  <h1>Photon Commerce</h1>
  <p><strong>Managed AI Agents for Document Data Extraction</strong></p>

  <p>
    <a href="https://www.photoncommerce.com"><img src="https://img.shields.io/badge/SOC%202-Compliant-blue?style=for-the-badge" alt="SOC 2"></a>
    &nbsp;&nbsp;
    <a href="https://www.photoncommerce.com"><img src="https://img.shields.io/badge/GDPR-Attested-blue?style=for-the-badge" alt="GDPR"></a>
    &nbsp;&nbsp;
    <a href="https://www.photoncommerce.com/pricing"><img src="https://img.shields.io/badge/Accuracy-99%25%2B-00C853?style=for-the-badge" alt="Accuracy"></a>
    &nbsp;&nbsp;
    <a href="https://www.photoncommerce.com/platform"><img src="https://img.shields.io/badge/Languages-25%2B-FF6D00?style=for-the-badge" alt="Languages"></a>
  </p>

  [Website](https://www.photoncommerce.com) &nbsp;·&nbsp; [API Docs](https://apidocs.photoncommerce.com) &nbsp;·&nbsp; [Pricing](https://www.photoncommerce.com/pricing) &nbsp;·&nbsp; [Free Trial](https://app.photoncommerce.com) &nbsp;·&nbsp; [Try in Claude](https://claude.ai/directory/connectors/photoncommerce) &nbsp;·&nbsp; [Try in ChatGPT](https://chatgpt.com/plugins/plugin_asdk_app_696685b735588191b9f25f976cfda7b2)
</div>

---

## What We Do

Photon Commerce provides **Managed AI Agents** that extract structured data from financial and trade documents with 99.9%+ accuracy.

We eliminate manual data entry for finance, operations, and compliance teams.

---

## Document Types

| Document | Key Extracted Fields |
|----------|---------------------|
| **Invoices** | Vendor, Bill To, line items, amounts, PO numbers, due dates, GL codes |
| **Receipts** | Merchant, items, totals, taxes, payment method, date |
| **Bank Statements** | Transactions, balances, account details, fraud indicators |
| **Bills of Lading** | Shipment details, carrier, consignee, cargo description |
| **Remittances** | Payment references, invoice matches, amounts |
| **Purchase Orders** | Line items, pricing, delivery terms, vendor info |
| **Checks & Stubs** | Payer, Payee, LAR, CAR, MICR details: routing/account/check numbers |
| **Insurance Statements** | Policy details, coverage, claims data |
| **Tax Forms** | Entity details, amounts, classification codes |
| **Custom Documents** | Any structured or semi-structured document |

100+ standardized fields per document &nbsp;·&nbsp; 25+ languages &nbsp;·&nbsp; Handwriting, barcodes, tables, and stamps supported

---

## How It Works

```
Document In → Photon Engine (AI + OCR + NLP) → Managed Agents → Structured Data Out
```

## Simple to Start. Powerful to Scale.

*Plug in, send an email, or just log in.*

**1. API** — integrate directly into your existing systems

```python
import requests

response = requests.post(
    "https://api.photoncommerce.com/api/pro",
    headers={
        "CLIENT-ID":     "YOUR_CLIENT_ID",
        "AUTHORIZATION": "apikey YOUR_USERNAME:YOUR_API_KEY",
        "PASSWORD":      "YOUR_PASSWORD",
        "SECRET-KEY":    "YOUR_SECRET_KEY",
    },
    params={"doctype": "invoice"},
    files={"pdf": open("invoice.pdf", "rb")},
)
photon_key = response.json()["photon_key"]  # use to retrieve results
```

**2. Email** — no integration required

Forward any document to **[ai@photoncommerce.com](mailto:ai@photoncommerce.com)** and receive structured JSON back in your inbox. Works with CC/BCC rules for fully automated inbox workflows.

**3. Web App & Mobile App** — no code needed

Upload documents, review extractions, and manage workflows at **[app.photoncommerce.com](https://app.photoncommerce.com)**.

---

## Processing Tiers

Multiple tiers available from seconds to 24 hours, with 99.9%+ accuracy and Managed Agents included. Pay only for what you extract.

[View current pricing and start your free trial →](https://www.photoncommerce.com/pricing)

---

## Output Formats

JSON &nbsp;·&nbsp; CSV &nbsp;·&nbsp; XML &nbsp;·&nbsp; XLSX &nbsp;·&nbsp; EDI (810, 820, 850) &nbsp;·&nbsp; cXML &nbsp;·&nbsp; Peppol &nbsp;·&nbsp; ISO 20022 &nbsp;·&nbsp; OASIS UBL &nbsp;·&nbsp; Proprietary ERP formats

---

## Integrations

**ERP & Accounting:** QuickBooks · Xero · SAP Ariba · NetSuite · Oracle · Bill.com · Coupa  
**Finance & Banking:** Brex · Plaid · Yodlee · Federal Reserve FedNow  
**E-Commerce:** Amazon Vendor Central · Shopify  
**Automation:** UIPath · Microsoft · NVIDIA  
**E-Invoicing:** Chorus Pro · Taulia · Tungsten · Transcepta · Basware

Integration takes 1 day to 1 week depending on workflow complexity.

---

## Compliance & Security

- SOC 2 Type II certified
- GDPR attested
- HIPAA compliant
- End-to-end encryption at rest and in transit
- Role-based access control
- Personal data identification and scrubbing on request

---

## Repositories

| Repo | Description |
|------|-------------|
| [`photon-invoice`](https://github.com/Photon-Commerce/photon-invoice) | Extract structured data from invoices — Python, cURL, and more |
| [`photon-receipt`](https://github.com/Photon-Commerce/photon-receipt) | Extract structured data from receipts — Python, cURL, and more |
| [`photon-statement`](https://github.com/Photon-Commerce/photon-statement) | Extract structured data from statements — Python, cURL, and more |


---

## Get Started

| | |
|-|-|
| **Try in Claude**  | [Photon Commerce on Claude](https://claude.ai/directory/connectors/photoncommerce) |
| **Try in ChatGPT** | [Photon Commerce on ChatGPT](https://chatgpt.com/plugins/plugin_asdk_app_696685b735588191b9f25f976cfda7b2) |
| **API Docs** | [apidocs.photoncommerce.com](https://apidocs.photoncommerce.com) |
| **Free Trial** | [app.photoncommerce.com](https://app.photoncommerce.com) |
| **Email Integration** | [ai@photoncommerce.com](mailto:ai@photoncommerce.com) |
| **Pricing** | [photoncommerce.com/pricing](https://www.photoncommerce.com/pricing) |
| **Contact** | [developers@photoncommerce.com](mailto:developers@photoncommerce.com) |
| **LinkedIn** | [linkedin.com/company/photoncommerce](https://www.linkedin.com/company/photoncommerce) |
