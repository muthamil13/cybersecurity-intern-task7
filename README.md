# Task 07 — Identify & Remove Suspicious Browser Extensions  

## 📌 Objective  
The goal of this task was to inspect all installed browser extensions, identify suspicious ones, review their permissions, and remove those that pose security risks. This helps improve browser performance and security awareness.  

## 🔍 Browser & Environment  
- **Browser:** Google Chrome  
- **OS:** Windows 10 (example, replace with your OS)  
- **Profile:** Default  
- **Date:** 2025-10-02  

## 🛠️ Steps Taken  
1. Opened `chrome://extensions/` to view all installed extensions.  
2. Enabled **Developer Mode** to see IDs and more details.  
3. Reviewed each extension’s description, permissions, and source.  
4. Compared permissions with the extension’s purpose (e.g., if “read and change all data on websites” is really necessary).  
5. Checked official Chrome Web Store listing and reviews for each extension.  
6. Identified potentially suspicious/unnecessary extensions.  
7. Disabled and then removed unwanted extensions.  
8. Restarted the browser and verified performance improvements.  
9. Documented the findings and steps in this repository.  

## 📂 Extensions Found (from `extention.txt`)  
| Extension Name                  | Publisher / Source       | Permissions | Status |
|---------------------------------|--------------------------|-------------|--------|
| Always active Window            | Chrome Web Store         | Read & change data on **all sites** | ⚠️ Suspicious – unnecessary, removed |
| Copyfish 🐟 Free OCR Software   | Chrome Web Store         | Notifications, read clipboard, site access | Allowed – safe for OCR use |
| Enable Copy Paste & Right Click | Chrome Web Store         | Read & change data on **all sites** | ⚠️ Suspicious – unnecessary, removed |
| Google Docs Offline             | Installed by Default     | Access to docs.google.com & drive.google.com | ✅ Safe – kept |

## ⚠️ Suspicious Extensions Identified & Removed  
1. **Always active Window** – Spoofs visibility state, requires full site access without clear need.  
2. **Enable Copy Paste & Right Click** – Broad “read and change all data” access, which is risky for a simple copy-paste bypass.  

## ✅ Safe Extensions  
- **Copyfish Free OCR** – Clear functionality (OCR), permissions reasonable.  
- **Google Docs Offline** – Installed by default, used for offline Docs/Drive, safe.  

## 📷 Screenshots (if included)  
- `screenshots/before_extensions_list.png` – All extensions before removal.  
- `screenshots/suspicious_extension_detail.png` – Permissions page of removed extension.  
- `screenshots/after_extensions_list.png` – Extensions after cleanup.  

## 🔐 Key Learnings  
- Always check what permissions an extension requests and if they match its purpose.  
- “Read and change all your data on websites” should raise suspicion unless absolutely required.  
- Remove extensions you don’t actively use — fewer extensions mean fewer risks.  
- Prefer official store listings with positive reviews and active developer support.  
