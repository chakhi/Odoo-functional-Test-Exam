# Odoo 19 Functional Certification — Free Practice Exam

A free, open-source practice app for the **Odoo 19 Functional Certification**. It is a single static page with no backend, no sign-up and no tracking.

## Features

- **Exam mode** works like the real test. It is timed (45 s per question, so 120 questions take 90 min) and scored **+1 / −0.5 / 0** (correct / wrong / blank), with a **70%** pass mark. You can flag questions and jump between them using the question grid.
- **Practice mode** has no timer and shows the answer and an explanation right after each question.
- Results include a breakdown by area, a review of your mistakes and a **"Retry my mistakes"** button.
- You can filter by area: Sales, CRM, Purchase, Inventory, Manufacturing, Accounting, Project, HR, Website, Marketing, Point of Sale, Services and General.
- Answer order is shuffled on every attempt. The app works on mobile and supports dark mode. Your attempt history is saved locally in your browser.

## Run it

Open `index.html` in a browser, or enable **GitHub Pages** (Settings ▸ Pages ▸ Deploy from branch `main`, folder `/`).

## Contribute questions

Questions live in [`questions.js`](questions.js), one array per question:

```js
["Module", "Question text?", ["Option A", "Option B", "Option C", "Option D"], correctIndex, "Why this is the right answer."],
```

Pull requests with new or corrected questions are welcome. Please write original questions only; don't copy them from paid courses or from the official exam.

## Disclaimer

This is a community study aid. It is not affiliated with or endorsed by Odoo S.A. The questions are original and are not taken from the official exam. Take the official certification on [odoo.com](https://www.odoo.com/slides/odoo-19-functional-certification-502).

## License

MIT
