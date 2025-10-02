# Task 7: Identify and Remove Suspicious Browser Extensions

## 🔐 Objective
Conduct an audit of browser extensions, identify suspicious or unused extensions, remove them, and document the process.

---

## 🧭 Environment
- Browser: Mozilla Firefox
- OS: Linux (Kali)

---

## 🛠 Steps Performed
1. Opened Firefox Add-ons Manager (`about:addons`).
2. Listed all installed extensions and reviewed details for each (developer, last updated, permissions, reviews).
3. Checked permissions and online reviews for suspicious indicators.
4. Uninstalled extensions deemed suspicious or unused.
5. Restarted browser and verified normal operation.

---

## ⚠️ Extensions Reviewed

### 1. `QuickTranslate Pro`
- **Developer:** FastTools Labs  
- **Permissions:** Read and change all your data on all websites; access clipboard  
- **Why suspicious:** Requests broad host access and clipboard permissions without clear need. Recent reviews mention unexpected popups.  
- **Action taken:** Removed  

---

### 2. `MegaDownload Helper`
- **Developer:** Unknown Publisher  
- **Permissions:** Manage downloads; access files you download; read browsing history  
- **Why suspicious:** Unknown publisher and excessive access to downloads and history. Could intercept or alter downloaded files.  
- **Action taken:** Removed  

---

### 3. `Rainbow Theme Switcher`
- **Developer:** Colorful Co.  
- **Permissions:** Access to browser tabs only  
- **Why flagged:** Only tab access — but unused by the user.  
- **Action taken:** Disabled  

---

### 4. `AdCleaner Lite`
- **Developer:** AdCleaner Inc.  
- **Permissions:** Read and change all your data on websites; inject scripts into pages  
- **Why suspicious:** Performs script injection and broad data access. Reviews reported redirects and affiliate link insertions.  
- **Action taken:** Removed  

---

### 5. `CryptoMiner Helper`
- **Developer:** MinerSoft  
- **Permissions:** Run background processes; use CPU  
- **Why suspicious:** Required background CPU usage. Could be performing cryptomining.  
- **Action taken:** Removed  

---

## ✅ Summary of Actions
- Removed: `QuickTranslate Pro`, `MegaDownload Helper`, `AdCleaner Lite`, `CryptoMiner Helper`  
- Disabled: `Rainbow Theme Switcher`  
- Restarted the browser and confirmed normal performance.

---

## 🔒 Recommendations & Best Practices
1. Only install extensions with minimal permissions.
2. Prefer extensions from verified or well-known developers.
3. Regularly review and remove unused or outdated extensions.
4. Monitor browser behavior and CPU/network usage.
5. Report suspicious extensions through the browser store.

-
