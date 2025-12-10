# Example: Node.js Extract Endpoint

POST /extract
- Accepts multipart/form-data file
- Calls Google Vision OCR
- Sends OCR text to OpenAI GPT-5.1 for extraction
- Returns structured JSON with confidence
- Includes error handling, retry, logging

Example cURL:
curl -X POST -F "file=@biodata.jpg" https://yourdomain.com/extract
