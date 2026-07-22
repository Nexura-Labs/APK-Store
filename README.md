graph TD
    HTML[html] --> HEAD[head]
    HTML --> BODY[body]

    HEAD --> META1[meta: UTF-8]
    HEAD --> META2[meta: viewport]
    HEAD --> TITLE[title: N Calculator]
    HEAD --> STYLE[style: CSS Glassmorphism]

    BODY --> CARD[div.card]
    
    CARD --> LOGO[img.logo]
    CARD --> H1[h1: N Calculator]
    CARD --> P[p: Description]
    CARD --> BTN[a.btn: Download APK]
    CARD --> FEAT[div.features]
    CARD --> SRC[a.source-link: View Source]

    FEAT --> UL[ul]
    UL --> LI1[li: Advanced Calc...]
    UL --> LI2[li: Ad-free...]
    UL --> LI3[li: MIT Licensed...]
    
