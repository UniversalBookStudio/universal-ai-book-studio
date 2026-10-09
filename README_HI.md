# Universal AI Book Studio — MVP Foundation

यह पहला working foundation/prototype है, final production app नहीं।

## इसमें क्या है
- Idea to Book, Manuscript to Book और Idea + Partial Content modes
- Book type, language, audience, publishing goal और design style selection
- Master Design Director से production plan बनाना
- बिना API key के deterministic planning
- वैकल्पिक Gemini API key के साथ AI-assisted planning
- TXT/MD upload और JSON plan download

## अभी बाकी है
यह अभी पूरा book-writing/publishing agent नहीं है। DOCX/PDF parsing, image generation, full manuscript drafting, PDF/EPUB export, page rendering और visual QC अगले stages हैं।

## Run
1. Python 3.10+
2. `pip install -r requirements.txt`
3. `streamlit run app.py`

Gemini key optional है। बिना key के local planning mode काम करेगा। Cloud AI की free usage unlimited होने की गारंटी नहीं है।
