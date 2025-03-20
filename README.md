# 📝 Summarize the New Documents from Google Drive and Save Summary in Google Sheet

## 📄 Template Description
This smart automation workflow, developed by the **AI team at WeblineIndia**, streamlines content management by automatically fetching the latest Google Doc from your Google Drive, summarizing its content using an AI model, and storing the summary in a Google Sheet.

It eliminates the need for manual document reading, saving time and effort while maintaining a well-organized record of summaries for easy future reference.

---

## ✅ Workflow Steps

### 1. Fetch the Most Recent Document from Google Drive
- **What It Does:** Identifies and fetches the most recently added Google Doc file.
- **How to Set It Up:**
  - Use the **Google Drive Node**.
  - Set the action to **"List Files"**.
  - Filter by file type **`.doc`** and **sort by date** (newest first).
  - Retrieve the **File ID** and **metadata** (file name, created date).

---

### 2. Extract Content from the Document
- **What It Does:** Extracts the full text content from the selected Google Doc.
- **How to Set It Up:**
  - Use the **Google Docs Node**.
  - Set the operation to **"Get Content"**.
  - Pass the **File ID** fetched from the previous step to extract the document's text.

---

### 3. Summarize the Document Using an AI Model
- **What It Does:** Feeds the extracted content to an AI model and generates a concise summary.
- **How to Set It Up:**
  - Use an **AI Model Node** (like OpenAI's ChatGPT).
  - Provide the **document text** as input.
  - Use a well-crafted **prompt** to instruct the model to generate a meaningful summary.
  - Capture the AI-generated summary.

---

### 4. Store the Summarized Content in Google Sheets
- **What It Does:** Logs the document summary and important metadata into a Google Sheet.
- **How to Set It Up:**
  - Use the **Google Sheets Node**.
  - Append a new row with:
    - Original Document Name
    - AI-generated Summary
    - Date Added (from metadata)

---

## 📊 Outcome

✅ Automatic summarization of newly added Google Docs  
✅ Easy access to concise document summaries in a Google Sheet  
✅ Improved productivity and simplified document management  
✅ A central repository of summaries for future reference and analysis

---



## 🚀 Benefits
✅ Saves time on manual document reading and summarizing  
✅ Organized record of all summaries with document references  
✅ Enhances productivity and streamlines content management  
✅ AI-driven insights from lengthy documents within seconds

---

## 📌 Example Use Cases
- Content teams summarizing research papers or articles
- Legal teams summarizing contracts and agreements
- Marketing teams summarizing campaign reports
- Business analysts generating quick insights from reports

---
## 🌐 About WeblineIndia
**WeblineIndia** specializes in delivering **custom AI solutions and automation workflows** that simplify business operations and enhance productivity.

Need help setting this up or building something similar? Reach out to our experts!

---