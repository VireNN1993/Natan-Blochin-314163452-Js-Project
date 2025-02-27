# פרויקט מסכם מודול JavaScript

## פרטים אישיים

- **שם הסטודנט:** נתן בלוחין
- **כתובת אימייל:** natanblohen10@gmail.com
- **GitHub:** [VireNN1993](https://github.com/VireNN1993)
- **LinkedIn:** [Natan Blochin](https://www.linkedin.com/in/natan-blochin-117800236/)

## תיאור כללי

פרויקט זה הינו אתר פורטפוליו אישי המציג עבודות מתקדמות ב-JavaScript. הפרויקט כולל את אתר הפורטפוליו המציג מידע אודותיי וכישוריי המקצועיים, וכן 9 פרויקטים אינטראקטיביים שפיתחתי. מטרת הפרויקט היא להדגים את יכולות התכנות והעיצוב שלי, תוך יישום הטכניקות והטכנולוגיות שנלמדו במהלך המודול.

## טכנולוגיות בשימוש

- **HTML5** - מבנה דפים סמנטי
- **CSS3** - עיצוב ואנימציות
- **JavaScript** - תכנות צד לקוח
- **TailwindCSS** - ספריית CSS לעיצוב
- **GSAP** - ספריית אנימציה
- **Rest API** - בפרויקטים שקשורים למידע חיצוני
- **localStorage** - לשמירת נתונים בצד הלקוח

## מבנה תיקיות הפרויקט

```
/
├── index.html             # דף הבית של הפורטפוליו
├── style.css              # קובץ עיצוב ראשי
├── modules/               # מודולים של JavaScript
│   ├── index.js           # קובץ JavaScript ראשי
│   ├── navigation.js      # ניהול ניווט
│   ├── projectManager.js  # ניהול פרויקטים
│   ├── formManager.js     # ניהול טפסים
│   ├── scrollManager.js   # ניהול גלילה
│   ├── themeManager.js    # ניהול ערכות נושא
│   ├── projectsData.js    # נתוני הפרויקטים
│   └── constants.js       # קבועים
├── Images/                # תיקיית תמונות
└── Projects/              # תיקיית פרויקטים
    ├── math-challenge/    # משחק מתמטיקה
    ├── HangMan Game/      # משחק איש תלוי
    ├── Pokemon Project/   # פרויקט פוקימון
    ├── Snake Game/        # משחק נחש
    ├── screen-builder/    # בונה מסכים
    ├── Contries Porject/  # פרויקט מדינות
    ├── Tic-Tac-Toe/       # משחק איקס עיגול
    ├── code-master/       # חידון תכנות
    └── Memory Game/       # משחק זיכרון
└── Downloads/             # תיקיית הורדות
```

## פירוט הפרויקטים

### 1. Math Challenge

משחק מתמטיקה אינטראקטיבי הכולל רמות קושי שונות וניקוד בזמן אמת. המשחק מאפשר לשחקנים לתרגל מיומנויות מתמטיות בסביבה משחקית ומהנה.

**טכנולוגיות:** HTML5, CSS3, JavaScript

### 2. Hangman Game

משחק איש תלוי קלאסי הכולל מאגר מילים נרחב. המשחק מאפשר לשחקנים לנחש את המילה הנסתרת אות אחר אות.

**טכנולוגיות:** HTML5, CSS3, JavaScript

### 3. Pokemon Project

מאגר פוקימונים מקיף עם אפשרויות חיפוש וסינון. הפרויקט משתמש ב-API חיצוני להצגת מידע מפורט על דמויות פוקימון.

**טכנולוגיות:** HTML5, CSS3, JavaScript, REST API

### 4. Snake Game

גרסה מודרנית של משחק הנחש הקלאסי, הכוללת תכונות מיוחדות. המשחק כולל בקרים תגובתיים לשולחן עבודה ולמובייל.

**טכנולוגיות:** HTML5, Canvas, JavaScript

### 5. Screen Builder

כלי ויזואלי ליצירת פריסות מסך עם פונקציונליות גרירה ושחרור. מאפשר למשתמשים לעצב ממשקים באופן ויזואלי ולשמור את הפריסות שלהם.

**טכנולוגיות:** HTML5, CSS3, JavaScript, localStorage

### 6. Countries API

פרויקט לחקר מידע על מדינות באמצעות REST API. התכונות כוללות פונקציונליות חיפוש, מועדפים והצגת מידע מפורט על מדינות.

**טכנולוגיות:** HTML5, CSS3, JavaScript, REST API

### 7. Tic-Tac-Toe Game

משחק איקס-עיגול קלאסי עם שלוש רמות קושי ומעקב אחר תוצאות. הרמה הקשה משתמשת באלגוריתם מיניטמקס ליריב בלתי מנוצח.

**טכנולוגיות:** HTML5, CSS3, JavaScript, אלגוריתם מיניטמקס

### 8. Code Master Quiz

משחק חידון תכנות המבוסס על "מי רוצה להיות מיליונר" עם 15 שאלות JavaScript מתקדמות וקווי חיים. בוחן את ידיעות הקידוד בפורמט כיפי.

**טכנולוגיות:** HTML5, CSS3, JavaScript

### 9. Memory Card Game

משחק זיכרון כיפי ומאתגר שבו השחקנים מתאימים זוגות של קלפים. כולל רמות קושי מרובות, טיימר ומערכת ניקוד גבוה.

**טכנולוגיות:** HTML5, CSS3, JavaScript

## פונקציונליות נוספת באתר הפורטפוליו

- **מעבר בין מצב כהה לבהיר** - אפשרות להחלפת ערכת הנושא של האתר
- **תפריט נייד מותאם** - ניווט נוח במכשירים ניידים
- **אנימציות גלילה** - אפקטים ויזואליים בעת גלילת העמוד
- **טופס יצירת קשר** - עם ולידציה וחיווי למשתמש
- **מודאלים לפרויקטים** - הצגת מידע מפורט על הפרויקטים
- **קו"ח להורדה** - אפשרות להוריד את קורות החיים

**© נתן בלוחין | כל הזכויות שמורות**
