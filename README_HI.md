# Universal AI Book Studio v0.5.0

## इस अपडेट में
- Basic PDF export जोड़ा गया।
- Hindi/Bengali PDF के लिए session-only Unicode TTF font upload विकल्प।
- EPUB package की ZIP/XML structure check।
- EPUB metadata में चुनी गई language का उपयोग।
- Manual editing, outline editing, preliminary QC और EPUB/DOCX/HTML/MD/TXT/JSON exports जारी।
- Gemini API integration को नहीं बदला गया।

## महत्वपूर्ण सीमाएँ
- PDF अभी basic typesetting है, print-ready प्रमाणित नहीं। Hindi/Bengali conjunct shaping, page breaks और font rendering की PDF देखकर जाँच जरूरी है।
- EPUB structure check, official EPUBCheck या वास्तविक e-reader परीक्षण का विकल्प नहीं है।
- Image generation, वास्तविक page-by-page visual QC, KDP preflight और मजबूत content-lock enforcement अभी बाकी हैं।
- API key को GitHub, screenshots या public repository में न रखें।

## अपडेट
`app.py`, `requirements.txt`, `README_HI.md`, `CHANGELOG_HI.md` को repository में replace करके commit करें।
