---
title: Harmoney OCR
emoji: 🧾
colorFrom: blue
colorTo: green
sdk: docker
pinned: false
license: mit
app_port: 7860
---

# Harmoney OCR Service

Flask backend service untuk OCR struk belanja menggunakan PaddleOCR + Groq Llama Vision.

Bagian dari project Harmoney - Smart Financial Management App.

## Endpoints

- `POST /scan-receipt` - Upload image, return parsed receipt data

## Tech Stack

- Flask + Gunicorn
- PaddleOCR 2.7.3 (OCR engine)
- Groq Llama 4 Vision (LLM parsing)

## Environment Variables

- `GROQ_API_KEY` - Set via Hugging Face Secrets