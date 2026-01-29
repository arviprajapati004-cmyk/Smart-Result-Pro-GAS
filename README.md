# 🚀 Smart Result Pro - School Management System
**An advanced Google Apps Script based solution for Gujarat Primary Schools (Std 6 to 8).**

## 🌟 Features
- **Admin Dashboard:** Central hub for all school activities.
- **Student Register:** Manage student profiles, DISE numbers, and bank details.
- **Marks Entry:** Simplified entry for Trimasik, Satrant, and Swa-adhyayan exams.
- **Patrak-B & C:** Automated personality development and annual summary registers.
- **Bulk PDF Generation:** Print Result Cards and Patrak-G in batches (Roll No range).
- **Student Portal:** Students can login via DISE number to view/download results.
- **Analytics:** Visual insights into school performance, rankings, and category-wise data.

## 🛠️ Tech Stack
- **Backend:** Google Apps Script (JavaScript)
- **Frontend:** HTML5, CSS3 (Gradients & Glassmorphism), Bootstrap 5
- **Database:** Google Sheets
- **Reporting:** Google Docs Template & PDF Blobs

## 🚀 Installation Guide
1. **Copy the Spreadsheet:** Create a Google Sheet with tabs: `Student_Info`, `Marks_Entry`, `School_Config`, `Calculations`, `PatrakB_Marks`, `PatrakB_Total`.
2. **Open Script Editor:** Go to `Extensions` > `Apps Script`.
3. **Add Files:** Copy the provided `.gs` and `.html` files into the editor.
4. **Deploy:** Click `Deploy` > `New Deployment`. Select `Web App`. 
   - Execute as: `Me`
   - Who has access: `Anyone` (for Student Portal) or `Anyone with Google Account`.

## 📁 Project Structure
- `Code.gs` - Server-side logic & Routing
- `MainDashboard.html` - Premium UI Dashboard
- `StudentRegister.html` - Student Master Data
- `ResultViewer.html` - Individual Report Card Preview
- `Analysis.html` - Performance Analytics Dashboard
- `PatrakC.html` - Annual Summary Register
