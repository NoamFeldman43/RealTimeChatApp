# יישום צ'אט בזמן אמת
זהו יישום צ'אט בזמן אמת שנבנה באמצעות Node.js, React.js, Firebase ו-Socket.io. היישום מאפשר למשתמשים להתחבר עם Google, לשלוח ולקבל הודעות בזמן אמת ולראות ממשק צ'אט אינטראקטיבי.

## מאפיינים
הודעות בזמן אמת: הודעות נשלחות ומתקבלות מיד בין משתמשים מחוברים באמצעות Socket.io.
אימות עם Google: משתמשים יכולים להתחבר באמצעות Google עם Firebase Authentication.
מסד נתונים של Firestore: ההודעות נשמרות ונשלפות ממסד נתונים של Firestore.
ממשק רספונסיבי: ממשק הצ'אט בנוי עם React ומעוצב להיות ידידותי למשתמש.
גלילה אוטומטית של הודעות: תיבת הצ'אט מתגלגלת אוטומטית כדי להציג את ההודעה האחרונה.

## טכנולוגיות בשימוש
Backend: Node.js, Express.js, ו-Socket.io לניהול תקשורת בזמן אמת בין לקוחות.
Frontend: React.js לממשק המשתמש.
Firebase:
Authentication לחיבור עם Google.
Firestore לשמירה ושליפה של הודעות.
Socket.io: לתקשורת בזמן אמת בין הלקוח לשרת.

## דרישות מוקדמות
ודא שיש לך את הכלים הבאים מותקנים במחשב המקומי שלך:

Node.js (גרסה 14 ומעלה)
npm (מנהל חבילות של Node)
חשבון Firebase: יש צורך בפרויקט Firebase עם Firestore ו-Google Authentication מופעלים.
 
## כיצד להתחיל
### שכפול הריפוזיטוריה
### התקנת התלויות
בצע את הפקודה הבאה בתיקיות הפרונטאנד והבקאנד כדי להתקין את כל החבילות הדרושות:
-- npm install
### הגדרת Firebase
צור פרויקט Firebase והפעל את Firestore ואת Google Authentication. החלף את הקוד בקובץ App.js עם פרטי הפרויקט שלך מ-Firebase:
-- const firebaseConfig = {
--   apiKey: "your-api-key",
--  authDomain: "your-auth-domain",
--  projectId: "your-project-id",
--  storageBucket: "your-storage-bucket",
--  messagingSenderId: "your-messaging-sender-id",
--  appId: "your-app-id",
--  measurementId: "your-measurement-id"
-- };

### הפעלת היישום

-- node index.js

-- npm start
בהצלחה🥇
