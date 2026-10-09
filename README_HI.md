# Universal AI Book Studio — MVP v0.2.0

मोबाइल से इस्तेमाल के लिए Streamlit आधारित शुरुआती पुस्तक-निर्माण कार्यशाला।

## अभी क्या काम करता है
- Idea / manuscript / partial-content input
- Local production plan और starter outline
- वैकल्पिक Gemini API से outline और अध्याय का draft
- अध्याय-वार draft editing
- Markdown, TXT, HTML और editable DOCX export
- Content protection निर्देश और verification markers

## अभी क्या नहीं है
- Print-ready PDF/EPUB production
- Actual page layout/rendering and visual QC
- Image generation, source research automation, KDP preflight certification
- API key के बिना पूर्ण AI manuscript generation

## चलाना
`pip install -r requirements.txt`
`streamlit run app.py`

Gemini AI features के लिए UI में अपनी API key डालें। API usage पर provider की limits/charges लागू हो सकती हैं। API key को GitHub में कभी commit न करें।

यह MVP है; AI drafts को प्रकाशन से पहले तथ्य-जाँच, संपादन और दृश्य निरीक्षण चाहिए।
