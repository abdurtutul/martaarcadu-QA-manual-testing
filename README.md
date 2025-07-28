# 🧪 Martaarcadu – QA Testing Report

This repository documents the QA efforts for the **Martaarcadu** project, developed by DevSparrow. As part of the QA process, I conducted **functional**, **UI/UX**, and **API** testing based on the SRS/SRE documentation and Figma design files. Bugs were logged in a collaborative Google Sheet and shared with the development team for resolution.

---

## 📲 Project Overview

**Project Name:** Martaarcadu  
**Role:** Software Quality Assurance (SQA)  
**Type:** Mobile Application  
**Tools Used:** Postman, JIRA, Charles Proxy, Figma, Google Sheets, Android Studio

---

## 📁 Project Files

| File | Description |
|------|-------------|
| 🔗 [Figma Design File](https://www.figma.com/design/mSCzYLH5GdddWSbXysvvpF/martaarcadu-%7C%7C-Devsparrow-%7C%7C--FO11A4A362D87?node-id=804-24216&p=f&t=xiANmYyxIR96wPnJ-0) | Full UI design reference |
| 🔗 [Figma Prototype Preview](https://www.figma.com/proto/mSCzYLH5GdddWSbXysvvpF/martaarcadu-%7C%7C-Devsparrow-%7C%7C--FO11A4A362D87?node-id=23783-2540&p=f&t=WLe29Wmg1TCk8SyL-1&scaling=scale-down&content-scaling=fixed&page-id=15694%3A374&starting-point-node-id=23783%3A762) | Interactive prototype |
| 📄[Bug Report Sheet](https://docs.google.com/spreadsheets/d/14C6RpQTsvguC7ouuWNqBF4ZKVkqx8qP1-EV4dquON2c/edit?gid=359680536) *(recommended: Ctrl + Click to open in a new tab)*| QA bug tracking and reporting |
| 📦 APK – [apk file ](https://github.com/abdurtutul/martaarcadu-QA-manual-testing/blob/main/app-release.apk) | App build for Client Requirement |

---

## ✅ QA Contributions

- Analyzed **Figma design** and **SRS/SRE** documentation to validate implementations.
- Executed **manual functional testing** across multiple modules.
- Verified user interface and user experience consistency with Figma.
- Performed **API testing** using Postman.
- 🔗 Click here to open the [Bug Report Sheet](https://docs.google.com/spreadsheets/d/14C6RpQTsvguC7ouuWNqBF4ZKVkqx8qP1-EV4dquON2c/edit?gid=359680536) *(recommended: Ctrl + Click to open in a new tab)*

---

## 🐞 Sample Bug Log Format

| Bug ID | Module | Feature | Bug Type (Flutter/UI/Backend) | Bug Title | Bug Description | Steps to Reproduce | Actual Result | Expected Result | Issue Labels | Severity | Attachment | Dev Status | Testers | Remark | Re-testing | Date |
|--------|--------|---------|-------------------------------|-----------|------------------|---------------------|----------------|------------------|---------------|----------|-------------|-------------|---------|--------|-------------|------|
| #001   | Login  | OTP     | Flutter                       | OTP Crash | App crashes on wrong OTP input | 1. Go to login screen<br>2. Enter invalid OTP<br>3. Tap Continue | App crashes | Error message should appear | Crash, Bug | High | Screenshot.png | Fixed | Tutul | Confirmed | ✅ | 2025-07-25 |
| #002   | Profile | Edit Info | UI                          | Misaligned Text | Text overlaps with button | Navigate to Profile > Edit | Text and button overlap | Proper alignment | UI | Medium | - | In Progress | Tutul | UI issue | ❌ | 2025-07-26 |

> 🔍 *You can find the full list in the [Bug Report Sheet](https://docs.google.com/spreadsheets/d/14C6RpQTsvguC7ouuWNqBF4ZKVkqx8qP1-EV4dquON2c/edit?gid=359680536).*

---

## 🚀 How to Test

1. Download the latest APK from the release section or provided link.
2. Install it on a real Android device or emulator.
3. Use the [Figma preview](https://www.figma.com/proto/mSCzYLH5GdddWSbXysvvpF/martaarcadu-%7C%7C-Devsparrow-%7C%7C--FO11A4A362D87?node-id=23783-2540&p=f&t=WLe29Wmg1TCk8SyL-1) to guide UI expectations.
4. Compare app behavior with the design and documentation.
5. Log any bugs in the shared sheet or issue tracker.
---
## 🖼️ App Screenshots

<div style="display: flex; overflow-x: auto; gap: 10px;">
  <img src="https://github.com/abdurtutul/martaarcadu-QA-manual-testing/blob/main/screenshots/Wlcome.png?raw=true" width="200" alt="Welcome" />
   <img src="https://github.com/abdurtutul/martaarcadu-QA-manual-testing/blob/main/screenshots/home.png" width="200" alt="Welcome" />
  <img src="https://github.com/abdurtutul/martaarcadu-QA-manual-testing/blob/main/screenshots/profile.png?raw=true" width="200" alt="Profile 1" />
  <img src="https://github.com/abdurtutul/martaarcadu-QA-manual-testing/blob/main/screenshots/message.png?raw=true" width="200" alt="Message" />
</div>

---
## 👤 QA by

**Md Abdur Rahaman Tutul**  
[GitHub](https://github.com/abdurtutul) | [LinkedIn](https://www.linkedin.com/in/md-abdur-rahaman-tutul-a13012210/)
