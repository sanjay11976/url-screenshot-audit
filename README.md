# url-screenshot-audit
A lightweight Python tool to check website availability and capture full-page screenshots using Playwright.

---

## 📦 Features

- ✔️ Double-click executable — no setup needed
- 🔎 Checks each website's availability
- 📸 Captures full-page screenshots of working sites
- 🧾 Logs failed or unreachable websites to `errors.log`
- 🗂 Saves screenshots in organized folders by date

---

## 🚀 How to Use

1. ✅ Place the following in the same folder:
   - `url-screenshot-audit.exe`
   - `urls.xlsx` (Excel file containing websites to check)

2. 🖱️ Double-click `url-screenshot-audit.exe`  
   The tool will:
   - Read websites from the Excel file
   - Try to visit each one
   - Save screenshots in a `/screenshots/` folder
   - Log any errors (timeouts, 404, bad URLs) in `errors.log`

---

## 📄 Input File: `urls.xlsx`

Make sure `urls.xlsx` has a single column titled **URL**:

| URL |
|-----|
| https://www.google.com |
| https://www.example.com |
| https://www.invalidsite.fake |

---

## 📁 Output Folders

- `screenshots/YYYY-MM-DD/` — Full-page screenshots of reachable sites
- `log/` — A text file listing any failed URLs with error messages

---

## ⚠️ Notes

- Internet connection is required
- Pop-up windows are hidden (runs headlessly)
- Make sure Excel file uses `.xlsx` format

---

## 📜 License

Free to use and modify for personal or business use.

---

## 🙌 Created By

**Accentiqa Team**  
Automated with ❤️ using Python & Playwright  
