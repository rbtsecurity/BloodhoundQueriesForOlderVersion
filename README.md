## 📁 File Structure

The repository includes pre-built custom query JSON files, ready to be used directly in BloodHound.

```
/
├── README.md                          # Usage instructions and query overview
├── customqueries-adcs.json           # ADCS-specific queries (ESC1–ESC9)
├── customqueries-full-ad-plus-az.json # Combined AD, ADCS, and Azure queries
```

### 📄 File Descriptions

* **`customqueries-adcs.json`**
  Contains queries focused on Active Directory Certificate Services (ADCS) abuse paths, including ESC1 through ESC9.

* **`customqueries-full-ad-plus-az.json`**
  A comprehensive collection of BloodHound Cypher queries combining:

  * Active Directory attack paths
  * ADCS privilege escalation techniques
  * Azure and hybrid cloud enumeration

> 🔧 To use these files, simply rename the one you want to `customqueries.json` and place it in the appropriate directory for your OS. See the instructions below.

---

### 🛠 How to Use These Queries in BloodHound

You can load the included custom Cypher queries into BloodHound by placing the `customqueries.json` file in the correct location based on your OS.

#### 📂 File Paths by OS

* **🔹 Linux:**
  `~/.config/bloodhound/customqueries.json`

* **🔹 Windows:**
  `C:\Users\[USERNAME]\AppData\Roaming\BloodHound\customqueries.json`

* **🔹 macOS:**
  `/Users/[USERNAME]/Library/Application Support/bloodhound/customqueries.json`

---

### 📘 Additional Notes

* These queries will show up directly in the **Custom Queries** section of the BloodHound GUI.
