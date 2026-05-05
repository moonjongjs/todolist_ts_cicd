# TO DO LIST (할일) 개발 제작

**풀스택 웹 개발자 문선종 입니다.**
**이프로젝트는 아래와 같은 툴과 방식으로 제작 되었습니다.**

---

React + TypeScript 기반의 **Todo List 웹 애플리케이션**으로,  
**Redux Toolkit**을 활용한 상태 관리, **커스텀 UI 컴포넌트**,  
그리고 **GitHub Actions CI/CD 자동 배포** 기능을 구현했습니다.  

본 프로젝트는 포트폴리오 목적으로 제작되었으며,  
**프론트엔드 개발 → 지속적 통합(CI) → 자동 배포(CD)** 까지  
엔드 투 엔드(End-to-End) 개발 과정을 구현하고자 했습니다. 

---

## 📜 License
본 프로젝트는 **CC BY-NC 4.0 (저작자표시-비영리 4.0 국제 라이선스)**를 따릅니다.  
즉, 출처를 표시하면 개인적/교육적 사용은 가능하지만,
**상업적 사용은 금지**됩니다.  
자세한 내용은 [LICENSE](./LICENSE) 파일을 참고하세요.  

---

## 🚀 Features
- **React + TypeScript** - 리액트 + 타입스크립트 기반 프론트엔드 개발
- **CI/CD with GitHub Actions** - 자동 배포 파이프라인 구축
- **Redux Toolkit Store** - 리덕스 툴킷을 활용한 상태 관리
- **Todo List 커스텀 개발** - CRUD 기능 구현
- **LocalStorage persistence** – 새로고침 후에도 데이터 유지
- **Custom Carousel & Pagination** – 커스텀 캐러셀 & 페이지네이션 개발 제작
- **캐러셀 슬라이드 기능 개발 구현** – 커스텀 캐러셀 슬라이드 개발 제작
- **페이지네이션 UI/UX 커스텀**  – 페이지네이션 UI/UX 개발 제작
- **Responsive Web Design (RWD)** – 반응형 UI Desktop, Tablet, Mobile 지원

---

## 🛠️ Tech Stack
- **Frontend**: React, TypeScript, Redux Toolkit
- **Styling**: SCSS, Responsive Web Design (Flex/Grid)
- **Build & Deploy**: GitHub Actions (CI/CD)
- **State Persistence**: LocalStorage
- **Hosting**: [Dothome Hosting](https://moonjong.dothome.co.kr)

---

## 📋 Project Features

### ✅ TO DO LIST 기능
- 할일 등록 (Create)
- 할일 수정 (Update)
- 할일 삭제 (Delete)
- 할일 완료 체크 (Complete)
- 전체 할일 목록 조회 (Read)

### 🔄 정렬 기능
- 만료일 빠른순 정렬
- 만료일 늦은순 정렬
- 최근 추가 항목순
- 오래된 추가 항목순

### 🔍 검색 기간 필터
- 전체기간
- 오늘
- 이번 주 / 지난 주 / 다음 주
- 이번 달 / 지난 달 / 다음 달
- 3개월 이내 / 6개월 이내
- 올해 / 지난 해 / 내년
- 만료된 항목만 조회

### 📝 검색 조건 필터
- 할일 내용 검색
- 만료된 항목 필터
- 완료된 항목 필터
- 삭제된 항목 필터

### 💻 반응형 (RWD) UI/UX
- 데스크탑(Desktop) 화면 지원
- 태블릿(Tablet) 화면 지원
- 모바일(Mobile) 화면 지원

---

## 📦 Installation
```bash
git clone https://github.com/moonjongjs/todolist_ts_cicd.git
cd todolist_ts_cicd
npm install
npm start
```

## Demo
[Live Demo](https://moonjongjs.github.io/todolist_ts_cicd)

## Screenshots
반응형 UI 지원 (데스크탑 / 태블릿 / 모바일)

### Desktop
<img width="1916" alt="Desktop Screenshot" src="https://github.com/user-attachments/assets/d3190621-7ee4-4846-a839-f2075193f18b" />

### Tablet
<img width="680" alt="Tablet Screenshot" src="https://github.com/user-attachments/assets/3620eb53-6ca7-47e1-ad2d-12cb2c7cbb05" />

### Mobile
<img width="320" alt="Mobile Screenshot" src="https://github.com/user-attachments/assets/5173d621-780f-4336-9198-45ba957eea3f" />
