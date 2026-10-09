# Universal AI Book Studio v0.5.2

## इस अपडेट में
- हिंदी/बंगाली/Hinglish PDF के लिए बिना Unicode TTF फ़ॉन्ट के डाउनलोड रोकता है, ताकि खराब बॉक्स वाली PDF न बने।
- PDF रेंडरिंग के लिए FPDF2 और HarfBuzz text shaping जोड़ा गया।
- EPUB और HTML में चुनी गई भाषा का metadata/lang tag जोड़ा गया।
- Manual chapter selector बदलने पर पुराने input का गलत text दिखने की समस्या कम की; चुने गए chapter की saved सामग्री preload होती है।
- Gemini API logic बदला नहीं गया।

## Hindi PDF कैसे बनाएं
1. ऐप में ऊपर `PDF font (optional)` पर टैप करें।
2. Unicode `.ttf` font upload करें जो आपकी भाषा के अक्षर support करता हो (Hindi के लिए Noto Sans Devanagari; Bengali के लिए Noto Sans Bengali)।
3. फिर `Download PDF` दबाएँ।
4. PDF खोलकर अक्षर, मात्राएँ, page breaks और layout जाँचें।

Font को GitHub repository में न डालें, जब तक license और redistribution अधिकार स्पष्ट न हों।

## सीमाएँ
- यह update syntax और code-path review के आधार पर है; live Streamlit runtime test और generated PDF visual test अभी आवश्यक हैं।
- Visual page-by-page QC, image generation और Amazon KDP certification शामिल नहीं हैं।
- API key को GitHub या सार्वजनिक चैट में न डालें।
