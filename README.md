# 🎯 Hack Hurdles - Slide Master Editor  

A feature-rich slide editor, tested manually using **Agile methodology**.

## 📌 Project Overview  
Hack Hurdles - Slide Master Editor is a **web-based** slide editor designed for smooth text formatting, slide management, and content customization.

## 🎯 Objective  
- Ensure a **seamless** slide editing experience.  
- Conduct **manual testing** to validate core functionalities.  
- Follow **Agile testing practices** for defect tracking.

## 🚀 Features  
✅ Create, edit, and delete slides dynamically  
✅ Apply rich text formatting (bold, italic, underline)  
✅ Save, load, and manage slides  
✅ Cross-browser compatibility  

## 🛠️ Tech Stack & Tools  
- **Testing:** **Manual Testing**   
- **Bug Tracking:** Jira, Google Sheets 
- **Methodology:** Agile  

## 📂 Agile Testing Approach  
1️⃣ **Sprint Planning** → Define user stories, prioritize test cases.  
2️⃣ **Development & Testing** → Manually test each feature.  
3️⃣ **Daily Scrum** → Identify issues, track defects.  
4️⃣ **Sprint Review** → Review bug fixes and improve strategy.  

## 📌 Manual Testing Documentation  
### 📑 Test Plan  
- **Scope:** Validate core functionalities manually.  
- **Testing Types:** Functional, UI/UX, Cross-browser.  
- **Test Environment:** Chrome, Firefox, Edge, Mobile.  
📌 **[View Test Plan](docs/TestPlan.md)**  

### ✅ Test Scenarios & Test Cases  
| **Test Scenario** | **Description** | **Expected Outcome** |
|------------------|----------------|------------------|
| Text Formatting | Apply bold, italic, and underline | Formatting applies correctly |
| Slide Creation | Add a new slide | Slide appears in the list |
| Slide Deletion | Remove a slide | Slide disappears |
📌 **[Full Test Cases](docs/TestCases.md)**  

### 🐞 Bug Report  
| **Bug ID** | **Feature** | **Description** | **Steps to Reproduce** | **Severity** |
|-----------|------------|-----------------|------------------------|-------------|
| **Bug_001** | Background Color | System allows invalid color codes | 1. Open editor <br> 2. Select `#XYZ123` <br> 3. No error message displayed | **Medium** |
| **Bug_002** | Image Upload | No error for unsupported image format | 1. Upload `.tiff` <br> 2. Apply filter <br> 3. No error displayed | **High** |
📌 **[Bug Report Document](docs/BugReport.md)**  

## 🔧 Setup & Installation  
```sh
git clone https://github.com/vikashh01/hack-hurdles.git
cd hack-hurdles
# hack-hurdles
