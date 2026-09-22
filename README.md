# 📐 CSS Grid — מדריך אינטראקטיבי 

מדריך לימודי מקיף המציג את עקרונות העבודה עם CSS Grid (רשת דו-ממדית) לעומת Flexbox, כולל שליטה בשורות ובעמודות, שימוש ביחידות גמישות, מיקום פריטים, יישורים ויצירת פריסות רספונסיביות אוטומטיות.

---

## 📌 תוכן עניינים
1. [על הפרויקט](#-על-הפרויקט)
2. [מבנה הקבצים בפרויקט](#-מבנה-הקבצים-בפרויקט)
3. [נושאי הלימוד המודגמים](#-נושאי-הלימוד-המודגמים)
4. [דוגמאות קוד מרכזיות](#-דוגמאות-קוד-מרכזיות)
5. [העלאה ל-GitHub והרצה ב-GitHub Pages](#-העלאה-ל-github-והרצה-ב-github-pages)

---

## 📖 על הפרויקט

שלא כמו Flexbox שעובד בעיקר במימד אחד (שורה או טור), CSS Grid מאפשר לבנות מבנה דו-ממדי מלא של שורות ועמודות במקביל.  
פרויקט זה מכיל עמוד תפריט ראשי (`index.html`) המקשר ל-10 דפי הדגמה מעשיים, שבהם כל קונספט מוצג בצורה מוחשית בעזרת צבעי רקע מובחנים והסברים ברורים.
<img width="1900" height="427" alt="image" src="https://github.com/user-attachments/assets/26374e1c-3d98-480f-94dc-4ef700a32732" />

---
 index.html                           # עמוד התפריט הראשי והניווט
├── 01-setup.html                         # מבנה בלוקים רגיל לפני הפעלת Grid

<img width="1495" height="786" alt="image" src="https://github.com/user-attachments/assets/b2f008ac-e9bf-4d91-97fe-330922d9f7bf" />

├── 02-create-grid.html                   # יצירת רשת, שורות, עמודות ו-gap
<img width="1441" height="575" alt="image" src="https://github.com/user-attachments/assets/83f604af-082a-411a-ada6-e33cb9a5d6e4" />

├── 03-fractional-units.html              # חלוקה יחסית עם יחידות fr ו-repeat
<img width="1407" height="686" alt="image" src="https://github.com/user-attachments/assets/848cf6d1-269a-40a4-9965-135aa60e8fef" />

├── 04-grid-items-position.html           # הזזת פריטים עם grid-column, grid-row ו-span
<img width="1412" height="718" alt="image" src="https://github.com/user-attachments/assets/8c980c41-7a36-41e5-8fd0-717b9f12e0ad" />

├── 05-grid-template-areas.html           # בניית שלד אתר שלם (Layout)
<img width="1405" height="736" alt="image" src="https://github.com/user-attachments/assets/4373bb1e-dcf8-4f17-8cbc-ab01d82d790b" />

├── 06-aligning-grid-items.html           # יישור פריטים בתוך התא (justify/align-items)
<img width="1316" height="678" alt="image" src="https://github.com/user-attachments/assets/d5df4aa0-09c8-403f-a82b-9b8c2c600219" />

├── 07-align-self-justify-self.html       # דריסת יישור לפריט בודד
<img width="1333" height="767" alt="image" src="https://github.com/user-attachments/assets/53270ad6-2d28-4450-9226-52917879d908" />

├── 08-justify-content-align-content.html # הזזת כל הרשת בתוך המכולה
<img width="1392" height="760" alt="image" src="https://github.com/user-attachments/assets/c5ce06ca-2b80-4f9c-9055-6de2d4dd3833" />

├── 09-min-max-minmax.html                # עבודה עם min-content, max-content ו-minmax
<img width="1840" height="426" alt="image" src="https://github.com/user-attachments/assets/d6dbc651-b420-40eb-93a8-b6215af45cd0" />

├── 10-auto-fill-auto-fit.html            # רספונסיביות אוטומטית ללא Media Queries
<img width="1785" height="357" alt="image" src="https://github.com/user-attachments/assets/7dba74c7-dea0-4a09-beeb-86a47c9873f9" />

## 📁 מבנה הקבצים בפרויקט

```text
├── index.html                           # עמוד התפריט הראשי והניווט
├── 01-setup.html                         # מבנה בלוקים רגיל לפני הפעלת Grid

<img width="1495" height="786" alt="image" src="https://github.com/user-attachments/assets/b2f008ac-e9bf-4d91-97fe-330922d9f7bf" />

├── 02-create-grid.html                   # יצירת רשת, שורות, עמודות ו-gap
<img width="1441" height="575" alt="image" src="https://github.com/user-attachments/assets/83f604af-082a-411a-ada6-e33cb9a5d6e4" />

├── 03-fractional-units.html              # חלוקה יחסית עם יחידות fr ו-repeat
<img width="1407" height="686" alt="image" src="https://github.com/user-attachments/assets/848cf6d1-269a-40a4-9965-135aa60e8fef" />

├── 04-grid-items-position.html           # הזזת פריטים עם grid-column, grid-row ו-span
<img width="1412" height="718" alt="image" src="https://github.com/user-attachments/assets/8c980c41-7a36-41e5-8fd0-717b9f12e0ad" />

├── 05-grid-template-areas.html           # בניית שלד אתר שלם (Layout)
<img width="1405" height="736" alt="image" src="https://github.com/user-attachments/assets/4373bb1e-dcf8-4f17-8cbc-ab01d82d790b" />

├── 06-aligning-grid-items.html           # יישור פריטים בתוך התא (justify/align-items)
<img width="1316" height="678" alt="image" src="https://github.com/user-attachments/assets/d5df4aa0-09c8-403f-a82b-9b8c2c600219" />

├── 07-align-self-justify-self.html       # דריסת יישור לפריט בודד
<img width="1333" height="767" alt="image" src="https://github.com/user-attachments/assets/53270ad6-2d28-4450-9226-52917879d908" />

├── 08-justify-content-align-content.html # הזזת כל הרשת בתוך המכולה
<img width="1392" height="760" alt="image" src="https://github.com/user-attachments/assets/c5ce06ca-2b80-4f9c-9055-6de2d4dd3833" />

├── 09-min-max-minmax.html                # עבודה עם min-content, max-content ו-minmax
<img width="1840" height="426" alt="image" src="https://github.com/user-attachments/assets/d6dbc651-b420-40eb-93a8-b6215af45cd0" />

├── 10-auto-fill-auto-fit.html            # רספונסיביות אוטומטית ללא Media Queries
<img width="1785" height="357" alt="image" src="https://github.com/user-attachments/assets/7dba74c7-dea0-4a09-beeb-86a47c9873f9" />


