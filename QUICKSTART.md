# 🚀 Agent AQ Agent - Quick Start Guide

**Get started with automated browser testing in under 5 minutes!**

---

## ⚡ Quick Setup

### 1. Install Dependencies

```bash
pip install -r requirements.txt
playwright install chromium
```

### 2. Start the Server

```bash
python app.py
```

### 3. Open Dashboard

Visit: **http://localhost:5000**

---

## 🎯 Your First Test

### Step 1: Open Agent Settings Tab
- You'll see the configuration form by default

### Step 2: Enter Test Instructions
```
Task: Go to youtube.com and search for 'AI tutorial'
Browser: Google Chrome
Mode: Headless
Recording: Off
```

### Step 3: Run Test
- Click **"▶️ Run Agent"**
- Watch the 5-step process animation:
  1. 🔍 Parsing instructions
  2. 💻 Generating Playwright code
  3. ✅ Validating code
  4. 🚀 Executing test
  5. 📊 Generating report

### Step 4: View Results
- Automatically switches to **Run Agent** tab
- See test status (✅ Passed / ❌ Failed)
- View execution steps with screenshots
- Expand to see generated Playwright code
- Download reports (JSON, PDF)

---

## 📝 Example Tests

### Google Search
```
Go to google.com and search for 'Playwright'
```

### Amazon Product Search
```
Navigate to amazon.com, search for 'laptop', wait 3 seconds
```

### Form Filling
```
Go to example.com/form, fill name field with 'John', click submit
```

---

## 🎨 Dashboard Features

### Agent Settings Tab
- Quick example buttons
- Task description textarea
- Browser, Mode, Recording dropdowns
- Run Agent button

### Run Agent Tab
- Test execution results
- Step-by-step breakdown
- Generated Playwright code
- Download buttons

### Recordings Tab
- View all recorded sessions
- Download recordings as JSON
- Event timeline with screenshots

### Analyzer Tab  
- Generate PDF/HTML/JSON reports
- View available reports
- Download any format

### History Tab
- View past test executions
- Clear history

---

## 🔧 Configuration Options

### Browsers
- **Google Chrome** (chromium)
- **Firefox**
- **Microsoft Edge** (msedge)

### Modes
- **Visible** - See browser actions
- **Headless** - Run in background (faster)

### Recording
- **On** - Capture session with screenshots
- **Off** - Skip recording

---

## 💡 Tips for Success

1. **Be Specific** - Use clear action words (click, type, search)
2. **Add Waits** - Include "wait 2 seconds" for dynamic content
3. **Use Recordings** - Enable recording for debugging
4. **Check Code** - Review generated Playwright code
5. **Export Reports** - Save results as PDF for documentation

---

## 🚨 Common Issues

**Browser not found?**
```bash
playwright install chromium
```

**Port already in use?**
- Close other applications using port 5000
- Or change port in app.py

**Test failing?**
- Try visible mode to see what's happening
- Add wait times for slow-loading pages
- Check the generated Playwright code

---

## 📚 Next Steps

- Read the full [README.md](README.md)
- Explore the [API Endpoints](#api-endpoints)
- Check [Project Structure](#project-structure)
- Contribute on GitHub

---

**Made with ❤️ by Bindu**

[⬆ Back to README](README.md)
