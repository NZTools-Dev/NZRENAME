
# 📁 NZRENAME (Smart Media File Renamer)

**NZRENAME** is a powerful, offline utility designed to intelligently rename media files by leveraging **EXIF metadata** and **custom location databases (GPS coordinates)**.

<img width="1159" height="839" alt="Screenshot 1" src="https://github.com/user-attachments/assets/631b1c1f-5a3e-4fb5-a1f2-49ec2c36b1d2" />
<img width="1143" height="836" alt="Screenshot 2" src="https://github.com/user-attachments/assets/c8d6eb15-92ba-4cb1-9cc8-7de1d58dd643" />

---

## 🚀 Key Features

* **📍 GPS Reverse Geocoding:** Automatically converts GPS coordinates in photos to real-world administrative regions or landmark names using a built-in location database.
* **🧠 Smart Metadata Tags:** Easily batch-rename files using a wide array of metadata tags, including camera model, shooting date, resolution, and more.
* **⚡ Native Performance:** Built with Delphi for Windows, ensuring smooth and fast processing of thousands of files without UI lag.
* **🤝 Extensible Custom Database:** Manage your own custom location data via simple text files for personalized naming.

---

## 📥 Download & Installation

This is a **portable** application with no complex installation required.

1. Download the latest version from the Releases page.
2. Extract the archive and run `NZRENAME.exe` to get started.

---

## 💡 Quick Start

1. Drag and drop your files or folder into the program.
2. Enter your desired tag pattern in the input field (e.g., `[<P_CITY2>_<P_PLACE>]_<P_DATE>-<N>`).
3. Preview the changes and click **[Rename]**.

## 
---

## 📌 Notices & Tips

* **Shell Context Menu:** The Windows right-click shell integration is supported in the **Installer version**. If you want to use the right-click menu, please use the installer package. (The Portable version does not write to system registries.)
* **Language Setting:** If the language does not default to English, you can change it via the settings menu (`Settings` -> `English`).

---

## 📂 NZRENAME Explorer Context‑Menu – What Each Item Does  

When you right‑click a file or folder in Windows Explorer, the **“NZRENAME”** submenu appears. Below is a plain‑language guide for every option you’ll see.  

| Menu Item (Korean) | Menu Item (English) | When It Shows Up | What It Does (in simple terms) |
|-------------------|---------------------|------------------|--------------------------------|
| **NZRENAME 열기** | **Open NZRENAME** | Any selection (file, folder, or a mix) | Opens the full NZRENAME program with the selected items already loaded, so you can rename them however you like. |
| **두 파일 이름 맞교환** | **Swap File Names** | Exactly two files are selected | Exchanges the names of the two files. The contents stay the same, only the file names are swapped. |
| **같은 이름으로** | **Match File Names** | Exactly two files with *different* extensions are selected | Renames the second file so its base name matches the first file (extension stays unchanged). |
| **파일 목록 내보내기** | **Export File List** | Any selection | Saves a list of the selected items to a CSV or text file (you choose the location). Useful for keeping a record or processing the list elsewhere. |
| **폴더 안 파일 이름 바꾸기** | **Rename Files in Folder** | A *single* folder is selected (no files) | Opens NZRENAME and lets you rename every file **inside** that folder (sub‑folders are ignored). |
| **폴더 안 파일 이름 바꾸기 (하위 포함)** | **Rename Files in Folder (Include Subfolders)** | A *single* folder is selected | Same as above, but also renames files that are inside any sub‑folders. |
| **선택한 폴더 이름 바꾸기** | **Rename Selected Folders** | A *single* folder is selected | Lets you rename the folder itself (not the files inside it). |
| **폴더 만들고 넣기** | **Group into Folder** | Two or more items (files and/or folders) are selected | Creates a new folder (named after the first selected file) and moves all selected items into that folder. |
| **빠른 이름 바꾸기** (Favorite 1, 2, …) | **Quick Rename** (your saved presets) | Any selection *and* you have saved “Favorites” in the settings | Runs a pre‑configured rename preset instantly, without opening the full UI. Great for repetitive tasks. |
| **빠른 이름 바꾸기 (폴더)** (Favorite 1, 2, …) | **Quick Rename (Folder)** (your saved presets) | A folder is selected *and* you have saved “Favorites” | Same as the “Quick Rename” above but works in **folder mode** (asks whether to include sub‑folders). |

### How to Use the Menu

1. **Select what you want to work on** – one file, multiple files, one folder, or a mix.  
2. **Right‑click** → choose **`NZRENAME`** → pick the desired command.  
3. Follow any small prompts (e.g., “Include sub‑folders?” for quick‑rename on a folder).  

That’s it! The menu gives you fast access to the most common NZRENAME actions directly from Explorer.  

---

## ⌨️ Tag Cheat Sheet

| Tag | Description | Example |
| :--- | :--- | :--- |
| `<N>` | Original File Name | `IMG_0001` |
| `<E>` | Extension | `jpg` |
| `<P_DATE>` | Date Taken (EXIF) | `20260807` |
| `<P_CITY2>` | Location (City/District) | `Seoul_Gangnam` |
| `<P_ALT>` | GPS Altitude | `1288m` |

---

## 🛠️ Development & License

* **Built With:** Object Pascal (Delphi Community Edition)
* **License:** This is a free, offline utility.

---

## 🇰🇷 한국어 안내 (Korean Guide)

**NZRENAME**은 사진과 영상의 **EXIF 메타데이터 및 커스텀 장소 DB(위경도)**를 바탕으로, 파일 이름을 지능적으로 조합해 주는 오프라인 유틸리티 프로그램입니다.

### 🌟 주요 킬러 기능
* **GPS 위치 자동 변환:** 사진 속 위경도 좌표를 내장된 장소 DB와 매칭하여, 행정구역이나 랜드마크 이름으로 자동 변환합니다.
* **스마트 메타데이터 태그:** 촬영 날짜, 카메라 기종 등 다양한 태그를 조합하여 일괄 변경할 수 있습니다.
* **유저 맞춤형 DB 확장:** 텍스트 기반으로 나만의 커스텀 장소 데이터를 쉽게 추가하고 공유할 수 있습니다.

### 📌 꼭 확인해주세요!
* **우클릭 쉘 메뉴 안내:** 우클릭 메뉴 연동 기능은 **설치 버전(Installer)**에서 지원됩니다. 탐색기 우클릭 기능을 편하게 쓰고 싶다면 설치 버전을 이용해 주세요! (포터블 버전은 시스템 레지스트리를 건드리지 않습니다.)
* **라이선스:** 본 프로젝트는 자유롭게 사용할 수 있는 무료 오프라인 유틸리티입니다.
---
**Contact: https://nztool.blogspot.com/
