# הפינה של אבי הגדול

דף נחיתה סטטי לעסק של אבי בצומת האלה.

## מבנה

- `public/index.html` - הדף הראשי
- `public/styles.css` - עיצוב רספונסיבי
- `public/assets` - תמונת הדוכן והלוגו
- `netlify.toml` - פריסה ב-Netlify
- `firebase.json` - פריסה ב-Firebase Hosting

## תצוגה מקומית

פתחו את `public/index.html` בדפדפן, או הגישו את תיקיית `public` עם שרת סטטי.

## פריסה

Netlify:

```bash
netlify deploy --prod --dir public
```

Firebase Hosting:

```bash
firebase deploy --only hosting
```

אם אין פרויקט Firebase פעיל במחשב, בחרו פרויקט עם:

```bash
firebase use --add
```
