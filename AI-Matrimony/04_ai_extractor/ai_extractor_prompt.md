# AI Biodata Extraction Microservice

Task: Convert JPG/PDF biodata into structured JSON.

Input:
- File (image/pdf), optional WhatsApp text, language hint

Output:
- JSON schema with confidence scores for fields like name, gender, dob, height, education, income, preferences

Requirements:
- OCR (Tesseract/Azure/Google Vision)
- LLM (OpenAI GPT-5.1 multimodal)
- Confidence < 0.7 → flag for review
