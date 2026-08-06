# 📂 NZRENAME (스마트 미디어 파일 리네이머)

> 사진과 영상의 **EXIF 메타데이터 및 커스텀 장소 DB(위경도)**를 바탕으로, 파일 이름을 지능적으로 조합해 주는 오프라인 유틸리티 프로그램입니다.


<img width="1159" height="839" alt="스크린샷 2026-08-06 214210" src="https://github.com/user-attachments/assets/631b1c1f-5a3e-4fb5-a1f2-49ec2c36b1d2" />
<img width="1143" height="836" alt="스크린샷 2026-08-06 220012" src="https://github.com/user-attachments/assets/c8d6eb15-92ba-4cb1-9cc8-7de1d58dd643" />


---

## 🚀 주요 킬러 기능 (Key Features)

* **📍 GPS 위치 자동 변환 (역지오코딩):** 사진 속 위경도 좌표를 내장된 장소 DB와 매칭하여, 실제 행정구역(시/도/군)이나 랜드마크 이름으로 자동 변환합니다.
* **🧠 스마트 메타데이터 태그:** 카메라 기종, 촬영 날짜, 해상도 등 다양한 태그를 조합하여 일괄 변경할 수 있습니다.
* **⚡ 초고속 네이티브 성능:** Delphi Community Edition 기반으로 제작되어 수만 장의 파일도 UI 멈춤 없이 쾌적하게 처리합니다.
* **🤝 유저 맞춤형 장소 DB 확장:** 텍스트 기반으로 나만의 커스텀 장소 데이터를 쉽게 추가하고 공유할 수 있습니다.

---

## 📥 다운로드 및 설치 (Download & Installation)

복잡한 설치 과정이 없는 **무설치 포터블(Portable)** 버전입니다.

1. [Releases 페이지 링크]에서 최신 버전을 다운로드하세요.
2. 압축을 해제한 후 `NZRENAME.exe`를 실행하면 바로 사용할 수 있습니다.

---

## 💡 사용 방법 (Quick Start)

1. 프로그램을 실행하고 파일을 드래그 앤 드롭하거나 폴더를 불러옵니다.
2. 상단 입력창에 원하는 태그 조합을 입력합니다. *(예: `[<P_CITY2>_<P_PLACE>]_<P_DATE>-<N>`)*
3. 미리보기로 바뀔 이름을 확인한 뒤 **[이름 바꾸기]** 버튼을 누릅니다.

---

## 📌 꼭 확인해주세요! (Notice & Tips)

* **우클릭 쉘 컨텍스트 메뉴 안내:** 
  포터블(무설치) 버전의 특성상 우클릭 메뉴 바로 가기를 쓰시려면 환경에 따라 추가 설정이 필요할 수 있습니다. 
  * 💡 **Win 11 꿀팁:** 윈도우 11 유저라면 파일 선택 후 **`Shift + 우클릭`**을 하시면 편리하게 이용하실 수 있습니다.
* **Global Users (English Language Guide):** 
  * If you are an English-speaking user downloading the **Portable version**, please make sure to change the language setting to English (`Language/English.ini` or via the settings menu) for the best experience!

---

## ⌨️ 주요 태그 가이드 (Tag Cheat Sheet)

| 태그 | 설명 | 예시 |
| :--- | :--- | :--- |
| `<N>` | 원본 파일 이름 | `IMG_0001` |
| `<E>` | 확장자 | `jpg` |
| `<P_DATE>` | 촬영 날짜 (EXIF) | `20260807` |
| `<P_CITY2>` | 촬영 지역 (시/도) | `강원_원주시` |
| `<P_ALT>` | GPS 고도 (해발) | `1288m` |

---

## 🛠️ 개발 환경 (Built With)

* **Language:** Object Pascal (Delphi Community Edition)
* **Architecture:** Core DLL Engine + VCL Frontend

---

## 📄 라이선스 (License)

이 프로젝트는 자유롭게 사용할 수 있는 무료 오프라인 유틸리티입니다.
