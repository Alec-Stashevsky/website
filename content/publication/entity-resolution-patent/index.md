---
abstract: Technologies for machine learning-based entity understanding and resolution are disclosed. Data for training an entity resolution model is collected to learn semantic relationships associated with entity names. The entity names are provided in a domain of documents that follow semantic conventions differently from natural language semantic conventions. The data includes entries each specifying an entity name and a label. The entity resolution model is trained using the data to learn and generalize the semantic relationships and is deployed to serve requests for resolving an entity name from text extract from a document image.
authors:
- Alec Stashevsky
- Melanie Riley
- Peter Campbell
date: "2026-10-13T00:00:00Z"
featured: true
publication: 'U.S. Patent No. 12,762,345 B2, assigned to Fetch Rewards, LLC'
publication_types:
- "8"
publishDate: "2026-10-13T00:00:00Z"
summary: Granted patent for a machine learning system that learns the semantics and conventions of a specific domain, such as retail receipts, to accurately resolve messy, OCR'd entity names to a canonical entity, with a human-in-the-loop interface to continuously refine the model.
tags: ["Patent", "Machine Learning"]
title: "Entity Understanding and Resolution System"
url_pdf: "/publication/entity-resolution-patent/US12762345.pdf"
links:
 - name: "View on Google Patents"
   url: https://patents.google.com/patent/US20260148001A1
   icon_pack: fas
   icon: file-contract
---

<a href="https://patents.google.com/patent/US12762345B2"><p style="text-align:center">View the full patent here!</p></a>

<br>

Conventional entity resolution models, including pretrained sentence transformers, are trained on natural language and struggle with domains like retail receipts, where text is abbreviated, visually structured, and prone to OCR errors. The system disclosed here instead trains a model directly on domain-specific data (e.g., canonical retailer names and their known variants) so it learns the semantic relationships particular to that domain, builds a fast approximate-nearest-neighbor search index over the learned embeddings, and pairs the model with a human-in-the-loop interface so an evaluator can confirm or correct outputs and continuously refine the model over time.
