# מדריך תקלות Siemens SIMOVERT MASTERDRIVES

אפליקציה מקומית לטכנאים: אומרים בקול את קוד התקלה, והאפליקציה מציגה על המסך את
הסיבה והפתרון מתוך המדריך הרשמי של Siemens (Operating Instructions 6SE7087-6JK60).

## איך להפעיל

**הדרך הפשוטה – לחיצה כפולה:**

פשוט פותחים את `index.html` ב-Google Chrome (או Edge).
אין צורך בהתקנה, בשרת או בחיבור לאינטרנט. כל 226 קודי התקלה משובצים בתוך הקובץ.

> הערה: חובה להשתמש ב-Chrome או Edge. זיהוי הדיבור מבוסס על Web Speech API
> ולא עובד ב-Firefox או Safari.

## שימוש

1. לוחצים על כפתור המיקרופון ומאשרים הרשאת מיקרופון בדפדפן.
2. אומרים את קוד התקלה **באנגלית**, לדוגמה:
   - `"F zero zero one"` → F001
   - `"F six"` → F006
   - `"F twenty"` → F020
   - `"A fifteen"` → A015
   - `"FF zero one"` → FF01
3. האפליקציה מציגה על המסך את שם התקלה, הסיבה (Cause) והפתרון (Counter-measure).
4. יש גם שדה להקלדה ידנית כגיבוי.

## מה בתוך האפליקציה

- `index.html` – האפליקציה המלאה (HTML + CSS + JS + נתונים).
- `faults.json` – קובץ הנתונים הגולמי (לא נדרש להפעלה, נשמר לצורך עריכה עתידית).
- `README.md` – קובץ זה.

## העברה לאחרים

מספיק לשלוח את הקובץ `index.html` בלבד. האפליקציה עצמאית לחלוטין.

## מקור

Siemens SIMOVERT MASTERDRIVES Vector Control – Frequency Converter (AC-AC) Chassis Type
Operating Instructions, Edition AE (05.2006), Order No. 6SE7087-6JK60.
