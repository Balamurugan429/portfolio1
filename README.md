# Ex01 Portfolio (HTML Only)

## Date: 02-11-2026
**Student Name:** Balamurugan P  
**Register / Roll No:** Saveetha Engineering College  
**Department:** B.E. Computer Science and Engineering  
**Institution:** Saveetha Engineering College, Chennai &bull; Tamil Nadu, India  
**GitHub Repository:** [https://github.com/Balamurugan429/portfolio2](https://github.com/Balamurugan429/portfolio2)  

---

## AIM
To design and develop a complete personal Portfolio web page using **pure HTML only (without external, internal, or inline CSS)**, utilizing semantic markup, structural tables, definition lists, media elements, anchor navigation, and interactive form elements.

---

## ALGORITHM

### STEP 1: HTML Document Foundation
Initialize the standard HTML5 document skeleton with `<!DOCTYPE html>`, `<html>`, `<head>`, and `<body>`. Set the character encoding to `UTF-8` and configure the viewport meta tag for device accessibility.

### STEP 2: Header & Profile Media
Create a structured `<header>` section with personal name, departmental affiliation, institution details, and an optimized profile image (`profile.png`) within `<figure>` and `<figcaption>` tags.

### STEP 3: Anchor Navigation Bar
Design a central `<nav>` bar containing internal anchor links (`#about`, `#education`, `#research`, `#projects`, `#skills`, `#certifications`, `#experience`, `#contact`) enabling smooth in-page navigation without scripting.

### STEP 4: About Me Section
Incorporate personal summary, academic background, current CGPA (7.92 / 10 at Saveetha Engineering College), and a profile specification data table.

### STEP 5: Academic Credentials
Construct a structured tabular representation (`<table>`, `<thead>`, `<tbody>`, `<tr>`, `<th>`, `<td>`) detailing degree qualifications, institutions, durations, and grades.

### STEP 6: Flagship Research Presentation
Document the flagship research project (*Explainable, Extraction-Aware Ensemble Learning for Groundwater Level Prediction*) with component weight breakdowns, R² scores, and interactive `<details>` / `<summary>` tags for feature importance rankings.

### STEP 7: Software & ML Projects Catalog
Build a structured projects table cataloging 6 applied machine learning and natural language processing applications with technologies used, descriptions, and direct code links.

### STEP 8: Technical Skills Matrix
Organize technical competencies into structured domain categories (Programming Languages, AI & ML, Data Science, Databases & BI, Core Computer Science) using tabular layouts.

### STEP 9: Certifications & Verification Records
List verified industry credentials (including Microsoft SQL Certification ID: `31679-4064293-291517` from Intellipaat) using ordered lists (`<ol>`) and `<small>` metadata.

### STEP 10: Career & Internship Milestones
Detail career milestones (ApproTech Solutions Internship, Lead Student Researcher, and Saveetha Academic journey) in a chronological table.

### STEP 11: Interactive Contact & Inquiry Form
Implement a semantic HTML `<form>` inside `<fieldset>` with `<legend>`, featuring labeled input fields (`text`, `email`, `<select>`, `<textarea>`, `submit`, and `reset` buttons).

### STEP 12: Footer & Open Source Attribution
Add a semantic `<footer>` section containing copyright notices, institutional details, MIT license information, and a "Back to Top" navigation anchor.

### STEP 13: Layout & Rendering Verification
Open `index.html` in web browsers to inspect tag nesting, table cell alignments, image rendering, anchor target functionality, and form submission flows.

### STEP 14: Deployment & Version Control
Initialize Git version control, commit all source files, set up remote tracking to `https://github.com/Balamurugan429/portfolio2`, and deploy via GitHub.

---

## PROGRAM

### File: `index.html`
*Refer to `index.html` in this repository for the full HTML source code.*  
Features pure semantic HTML elements:
- Headers and navigation: `<header>`, `<nav>`, `<h1>`–`<h4>`, `<hr>`
- Tabular data presentation: `<table>`, `<caption>`, `<thead>`, `<tbody>`, `<tr>`, `<th>`, `<td>`
- Lists: `<ul>`, `<ol>`, `<li>`, `<details>`, `<summary>`
- Media: `<figure>`, `<figcaption>`, `<img>`
- Forms: `<form>`, `<fieldset>`, `<legend>`, `<label>`, `<input>`, `<select>`, `<option>`, `<textarea>`
- Semantic footer: `<footer>`

---

## OUTPUT

1. **Header & Navigation**: Displays Balamurugan P's title, Saveetha Engineering College affiliation, profile photo, and clickable jump navigation links.
2. **About Me**: Brief personal introduction along with a structured 2-column profile specification table.
3. **Academic Background**: Clean HTML table detailing B.E. CSE (CGPA 7.92), HSC, and SSLC records.
4. **Flagship Research Section**: Hydrogeological prediction research with an ensemble weights table (XGBoost 45%, LightGBM 35%, Random Forest 20%, Combined R² = 0.964, RMSE = 0.41m) and expandable SHAP feature attribution rankings.
5. **Projects Catalog**: 6 machine learning projects (Fake News Detection, Heart Disease Prediction, Smart AI Chatbot, Movie Recommendation, Resume Ranking, and Lung Cancer Diagnostic Vision) in a tabular format.
6. **Skills & Certifications**: Categorized technical competencies and verified Intellipaat certification records.
7. **Contact Form**: Semantic form with inputs for name, email, inquiry type dropdown, and inquiry message with Submit and Reset buttons.
8. **Footer**: MIT license attribution, academic copyright, and jump-to-top anchor.

---

## RESULT
The program for creating a personal Portfolio using pure HTML only (without CSS) is executed and verified successfully.
