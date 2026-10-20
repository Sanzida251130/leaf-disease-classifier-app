```markdown
# 🌿 Leaf Disease Recognition & Care Guide App

An AI-powered mobile application built using **MIT App Inventor**, **PersonalImageClassifier**, and **Google Sheets API**. The app captures leaf images using the device camera, accurately identifies plant diseases using on-device machine learning, and retrieves scientific details, descriptions, and treatment guidelines directly from a cloud spreadsheet.

---

## 📱 Features

- **Real-Time Classification:** Captures plant images and identifies leaf diseases using a trained Image Classifier model (`model.mdl`).
- **Dynamic Cloud Database:** Connects asynchronously to Google Sheets via API to fetch up-to-date disease records.
- **Detailed Insights:** Displays:
  - Common Disease Name
  - Scientific Name / Causative Organism
  - Detailed Description
  - Recommended Action / Recovery Guidelines

---

## 🛠️ Built With

- **[MIT App Inventor](https://appinventor.mit.edu/):** Low-code mobile development platform.
- **[PersonalImageClassifier Extension](https://classifier.appinventor.mit.edu/):** On-device computer vision & ML extension.
- **Google Sheets API:** Asynchronous cloud database for disease information management.

---

## 📊 Spreadsheet Setup Guide

To ensure proper data retrieval, set up your Google Sheet columns as follows:

| Column A | Column B | Column C | Column D |
| :--- | :--- | :--- | :--- |
| **Label** | **Scientific_Name** | **Description** | **Action** |
| Healthy leaf | Miracle leaves | Maintaining healthy, vibrant plant leaves requires... | Watering Consistently, Providing Proper Sunlight... |
| Lea spot | Curvularia oryzae | Leaf spot is a common plant disease caused by... | Prune Affected Leaves, Sanitize Tools... |
| Leaf blast | Magnaporthe oryzae | Managing leaf blast requires an integrated approach... | Increase Flood Depth, Split Nitrogen... |
| Rust disease | Puccinia triticina erikss | Leaf rust is a fungal disease that thrives in... | Remove Infected Leaves, Dispose, Don’t... |
| Yellow leaf | Chlorosis | Overwatering, lack of nutrients, or root damage. | Identify the Location, Prune Dead Leaves... |

> **Note:** Ensure your Google Sheet tab is named `Sheet1` and shared with **"Anyone with the link can view"** or shared directly with your Google Service Account email.

---

## 📸 Screenshots

| Designer Layout | Block Architecture | Live App |
| :---: | :---: | :---: |
| <img src="https://github.com/user-attachments/assets/421130d0-b4f2-494f-ab58-cf5663f57ee6" width="300" /> | <img src="https://github.com/user-attachments/assets/c98c9dd4-eb68-4295-8b28-5a1e3620cc98" width="300" /> | <img src="https://github.com/user-attachments/assets/d017cd9c-b794-4b4e-be7c-5e7f8cb4de08" width="150" /> <img src="https://github.com/user-attachments/assets/66a16c17-dfd8-4f1c-b025-dc54101d5d55" width="150" /> |

---

## 🚀 How to Import and Run

1. Download the `.aia` file from this repository: `Leaf_Disease_Classifier.aia`.
2. Open [MIT App Inventor](https://ai2.appinventor.mit.edu/) in your web browser.
3. Click **Projects > Import project (.aia) from my computer...** and upload `Leaf_Disease_Classifier.aia`.
4. Update the **SpreadsheetID** property under the `Spreadsheet1` component with your own Google Sheet ID.
5. Connect your device via **MIT AI2 Companion** to test the app live!

---

## 🎓 Academic Disclaimer & Usage

This repository and its source code were created as part of an **Academic Research / Coursework Project**. All rights reserved by the author. This repository is made publicly available strictly for educational, demonstration, and research evaluation purposes. Commercial redistribution or modification without attribution is prohibited.
```
