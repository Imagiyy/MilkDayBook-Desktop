# 🥛 Milk Day Book — Desktop & Mobile Applications
### பால் உற்பத்தியாளர்கள் கூட்டுறவு சங்கம் தினசரி குறிப்பேடு (Desktop & Android App)

[![Release](https://img.shields.io/badge/Release-v1.0.0-emerald.svg?style=for-the-badge&logo=github)](https://github.com/Imagiyy/MilkDayBook-Desktop/releases/tag/v1.0.0)
[![Platform](https://img.shields.io/badge/Platforms-Windows%20%7C%20Linux%20%7C%20Android-blue.svg?style=for-the-badge)](https://github.com/Imagiyy/MilkDayBook-Desktop/releases)
[![Offline](https://img.shields.io/badge/Offline-100%25%20Offline%20First-green.svg?style=for-the-badge&logo=offline)](https://github.com/Imagiyy/MilkDayBook-Desktop)
[![Languages](https://img.shields.io/badge/Languages-தமிழ்%20%7C%20English-orange.svg?style=for-the-badge)](https://github.com/Imagiyy/MilkDayBook-Desktop)
[![License](https://img.shields.io/badge/License-MIT-purple.svg?style=for-the-badge)](LICENSE)

An official, standalone, offline-first accounting suite built specifically for **Primary Milk Producers Cooperative Societies (MPCS / ஆவின் தொடக்க பால் உற்பத்தியாளர்கள் கூட்டுறவு சங்கங்கள்)**. Supports comprehensive daily milk procurement, union dispatches, local sales, cash book maintenance under standard cooperative account heads, multi-society management, and dynamic headings.

---

## 📥 Download Desktop & Mobile Apps (Releases v1.0.0)

Direct standalone downloads available from [GitHub Releases v1.0.0](https://github.com/Imagiyy/MilkDayBook-Desktop/releases/tag/v1.0.0):

| Platform | Format | File Name | Size | Direct Download & Instructions |
| :--- | :--- | :--- | :--- | :--- |
| **Windows** | **Lite Portable (.exe)** | `Milk.Day.Book.Lite.1.0.0.exe` | **⚡ 718 KB** | [⬇ Download Ultra-Lite EXE](https://github.com/Imagiyy/MilkDayBook-Desktop/releases/download/v1.0.0/Milk.Day.Book.Lite.1.0.0.exe)<br>**Super-Lightweight Standalone**. Uses Windows built-in Edge engine. No install needed! |
| **Windows** | **Portable (.exe)** | `Milk.Day.Book.1.0.0.exe` | **114 MB** | [⬇ Download Portable EXE](https://github.com/Imagiyy/MilkDayBook-Desktop/releases/download/v1.0.0/Milk.Day.Book.1.0.0.exe)<br>Self-contained Electron portable with bundled Chromium. |
| **Windows** | **Installer (.exe)** | `Milk.Day.Book.Setup.1.0.0.exe` | **129 MB** | [⬇ Download Installer EXE](https://github.com/Imagiyy/MilkDayBook-Desktop/releases/download/v1.0.0/Milk.Day.Book.Setup.1.0.0.exe)<br>Standard installer with Desktop & Start Menu shortcuts. |
| **Linux** | **AppImage** | `Milk.Day.Book-1.0.0.AppImage` | **137 MB** | [⬇ Download AppImage](https://github.com/Imagiyy/MilkDayBook-Desktop/releases/download/v1.0.0/Milk.Day.Book-1.0.0.AppImage)<br>Universal standalone executable. `chmod +x` & run. |
| **Linux** | **Debian (.deb)** | `milk-day-book_1.0.0_amd64.deb` | **108 MB** | [⬇ Download .deb](https://github.com/Imagiyy/MilkDayBook-Desktop/releases/download/v1.0.0/milk-day-book_1.0.0_amd64.deb)<br>Ubuntu / Debian / Mint package. `sudo dpkg -i`. |
| **Linux** | **Tarball (.tar.gz)** | `milk-day-book-1.0.0.tar.gz` | **131 MB** | [⬇ Download Tarball](https://github.com/Imagiyy/MilkDayBook-Desktop/releases/download/v1.0.0/milk-day-book-1.0.0.tar.gz)<br>Extract and run `./milk-day-book`. |
| **Android** | **APK (.apk)** | `MilkDayBook.apk` | **4.4 MB** | [⬇ Download APK](https://github.com/Imagiyy/MilkDayBook-Desktop/releases/download/v1.0.0/MilkDayBook.apk)<br>Android phones & tablets (Android 8.0+). |

---

## 🌟 Key Features / முக்கிய சிறப்பம்சங்கள்

### 1. 🏢 Multi-Society Management (பல்வேறு கூட்டுறவு சங்கங்கள்)
- Manage and maintain independent day books for multiple dairy societies within one app.
- Switch seamlessly between societies with a dedicated switcher modal.
- Society-isolated databases: each society has its own financial years, cash transactions, and reports.

### 2. ➕ Dynamic Custom Heads (+ Add Heading)
- Need to record 2 to 3 custom headings manually at the end of Credit or Debit sections?
- Click the sleek **+** button under **Other Credit Receipts (Custom Heads)** or **Other Debit Expenses (Custom Heads)** to add unlimited custom heads.
- Custom headings carry forward full audit validation and custom title/narration tracking.
- Real-time badge counter indicates active custom heads.

### 3. 🧮 Formula Calculation in Milk Amount Fields
- Directly type mathematical formulas in milk procurement or sales amount inputs:
  - `=100 x 32` → Evaluates to `₹3,200.00`
  - `=120.5 * 34.5` → Evaluates to `₹4,157.25`
  - `=50 + 20 * 30` → Evaluates according to operator precedence
- Live preview displays the evaluated result while typing; evaluates permanently on blur or Enter.

### 4. 🌐 Complete Bilingual Support (இருமொழி இடைமுகம்)
- Instant 1-click toggle between **தமிழ் (Tamil)** and **English**.
- Conforms to standard cooperative accounting terminology (*உள்ளூர் விற்பனை, மாட்டுத் தீவனம், பால் பட்டுவாடா, விடுபட்டவை, வங்கி செலுத்துகை, முதலியன*).

### 5. 🔒 100% Offline-First & Zero-Telemetry
- Runs completely offline without internet or external cloud dependency.
- All records are saved securely inside IndexedDB (Dexie.js) on your local hard drive.
- Fresh install starts with a pristine **zero-data clean state** (no unwanted mock transactions).

### 6. 📅 Financial Year Management (1 April – 31 March)
- Full 365 days (366 days for leap years, including 29 February).
- Automated cash carry-forward: `Closing Balance = Opening Balance + Total Credit - Total Debit`.
- **Cascade Recalculation Engine**: Editing any previous day automatically recalculates subsequent opening and closing balances across the entire financial year.
- Lock & finalize financial years to prevent unauthorized edits.

### 7. 📑 Audit-Ready PDF & Excel Reports
- **Daily Day Book Sheet**: Generates high-resolution printable PDF day books.
- **Annual Reconciliation Certificate**: Full 46-head annual summary with milk summary and audit reconciliation status.
- **Excel/CSV Export**: Complete annual financial ledger exported with UTF-8 BOM encoding for perfect Tamil rendering in Microsoft Excel.
- **Backup & Restore**: Export encrypted JSON backups and restore on any other computer or mobile device.

---

## 🚀 How to Run the Desktop App

### Linux (AppImage)
```bash
# 1. Make executable
chmod +x "Milk Day Book-1.0.0.AppImage"

# 2. Run
./"Milk Day Book-1.0.0.AppImage"
```

### Linux (Debian / Ubuntu)
```bash
sudo dpkg -i milk-day-book_1.0.0_amd64.deb
```

### Windows
1. Download `Milk Day Book 1.0.0.exe` (Portable) or `Milk Day Book Setup 1.0.0.exe`.
2. Double-click the file to launch.
3. No configuration or external dependencies needed!

---

## 💻 Building from Source

### Prerequisites
- [Node.js](https://nodejs.org/) (v18 or higher)
- npm (v9 or higher)

### Setup & Run
```bash
# 1. Clone repository
git clone https://github.com/Imagiyy/MilkDayBook-Desktop.git
cd MilkDayBook-Desktop

# 2. Install dependencies
npm install

# 3. Run in Development Mode
npm run desktop:dev

# 4. Package Linux Desktop App (AppImage, deb, tar.gz)
npm run desktop:build:linux

# 5. Package Windows Desktop App (portable exe, nsis setup)
npm run desktop:build:win

# 6. Build Android APK
npm run build:apk
```

---

## 🛠️ Technology Stack
- **Framework**: [Electron](https://www.electronjs.org/) + [React 18](https://react.dev/) + [TypeScript](https://www.typescriptlang.org/)
- **Build System**: [Vite](https://vitejs.dev/) + [electron-builder](https://www.electron.build/)
- **Database**: [Dexie.js](https://dexie.org/) (IndexedDB wrapper)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/) + [Lucide React](https://lucide.dev/)
- **PDF Generation**: [jsPDF](https://github.com/parallax/jsPDF) + [jspdf-autotable](https://github.com/simonbengtsson/jsPDF-AutoTable)
- **Mobile Engine**: [Capacitor](https://capacitorjs.com/)

---

## 📄 License
This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

Developed with ❤️ for Dairy Farmers & Primary Milk Producers Cooperative Societies.
