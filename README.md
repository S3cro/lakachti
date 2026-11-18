# לקחתי\שכחתי?

רשימת קניות פשוטה שרצה כולה בדפדפן. אין שרת, אין משתמשים — הנתונים נשמרים בדפדפן של כל מכשיר (localStorage).

## העלאה ל-GitHub Pages (חינם)

1. ב-GitHub: **New repository** → שם, למשל `lakachti` → **Public** → Create.
2. **Add file → Upload files** → גררו את כל הקבצים:
   `index.html`, `manifest.webmanifest`, `sw.js`, `icon.svg`, `icon-192.png`, `icon-512.png`, `README.md` → **Commit changes**.
3. **Settings → Pages** → Source: **Deploy from a branch** → Branch: `main`, תיקייה `/ (root)` → **Save**.
4. אחרי דקה-שתיים האתר זמין בכתובת:
   `https://<שם-המשתמש>.github.io/lakachti/`

עדכון גרסה: מעלים שוב את `index.html` (Upload files מחליף). בטלפון לוחצים 🔄 באפליקציה.

## בטלפון

- **אייפון (Safari):** שיתוף → "הוסף למסך הבית".
- **אנדרואיד (Chrome):** ⋮ → "הוסף למסך הבית" / "התקן אפליקציה".

התקנה למסך הבית חשובה: באייפון, Safari עלול למחוק נתונים של אתרים שלא נפתחו 7 ימים — אפליקציה שהותקנה למסך הבית לא נמחקת.

## חשוב לדעת

- הנתונים שמורים רק במכשיר ובדפדפן שבהם נוצרו. ניקוי נתוני גלישה = מחיקה. גבו מדי פעם: ⋯ → "גיבוי מלא לקובץ".
- **שיתוף קישור** שולח עותק של הרשימה בתוך הקישור עצמו (לא עובר דרך שרת). תמונות מהמצלמה לא נכנסות לקישור — לשיתוף עם תמונות השתמשו ב"ייצוא לקובץ".
- תמונות מוקטנות אוטומטית כדי לחסוך מקום (בדפדפן יש בערך 5MB).

## Features

Multiple lists · check off items · amount, note, link and photo per item · presets (save/load via dropdown) · share link / text / JSON file · import · full backup/restore · light / dark / auto theme · offline (service worker) · installable PWA.
