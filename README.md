# 🌟 Introduce-me 기획안
> **개인 포트폴리오 웹사이트**  
> 역량을 시각적으로 어필하여 취업 및 협업 기회 창출을 위한 인터랙티브 포트폴리오

[![GitHub Stars](https://img.shields.io/github/stars/yiseol/Introduce-me_prototype?style=flat-square)](https://github.com/yiseol/Introduce-me_prototype)
[![GitHub Issues](https://img.shields.io/github/issues/yiseol/Introduce-me_prototype?style=flat-square)](https://github.com/yiseol/Introduce-me_prototype/issues)
[![GitHub License](https://img.shields.io/github/license/yiseol/Introduce-me_prototype?style=flat-square)](https://github.com/yiseol/Introduce-me_prototype/blob/main/LICENSE)

## 📋 목차
- [프로젝트 개요](#-프로젝트-개요)
- [주요 기능](#-주요-기능)
- [기술 스택](#-기술-스택)
- [페이지 구성](#-페이지-구성)
- [사이트맵](#-사이트맵)
- [설치 및 실행](#-설치-및-실행)
- [브라우저 호환성](#-브라우저-호환성)
- [개발 일정](#-개발-일정)
- [라이센스](#-라이센스)

## 🎯 프로젝트 개요

### 목적
- 역량을 시각적으로 어필하여 취업 및 협업 기회 창출
- 경력 및 활동을 간편하게 확인하는 서비스 제공

### 대상 사용자
- 📋 **채용 담당자 및 면접관**
- 🤝 **협업 희망자 및 동업자**

## ✨ 주요 기능

- 🎬 **웹사이트 인트로 애니메이션**: 임팩트 있는 첫 인상 제공
- 🎨 **다양한 애니메이션 효과**: 호버, 페이드, 슬라이드 애니메이션
- 📱 **반응형 디자인**: 모든 디바이스에서 최적화된 경험
- 🎯 **풀페이지 레이아웃**: 섹션별 풀스크린 디자인
- 📄 **PDF 다운로드**: 이력서 PDF 제공

## 🛠 기술 스택

### Frontend
- ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
- ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
- ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

### Animation & Design
- CSS Animation & Keyframes
- CSS Transitions
- Transform Effects

### Version Control
- ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
- ![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)

## 📄 페이지 구성

### 🏠 메인 페이지 (index.html)
- **인트로 애니메이션**: 웹사이트 진입 시 텍스트 애니메이션
- **풀페이지 메뉴 카드**: 각 섹션별 대형 카드 레이아웃
- **호버 효과**: 카드 확대, 그림자 강화, 광선 효과

### 📖 서브 페이지
| 페이지 | 파일명 | 주요 기능 |
|--------|--------|-----------|
| **자기소개** | `Introduce-myself.html` | 기본정보 섹션, 성장과정 타임라인 |
| **활동내역** | `Activity.html` | 인턴십, 대회, 수상경력 타임라인 |
| **자격증** | `Certifination.html` | 3×2 그리드 자격증 카드 레이아웃 |
| **프로젝트** | `Project.html` | 5개 프로젝트 풀페이지 상세 소개 |
| **이력서** | `Resume.html` | 이력서 미리보기 및 PDF 다운로드 |

## 🗺 사이트맵

```
├── 📁 Main Page (index.html)
│   ├── 🧭 Header Navigation
│   ├── 🎬 Intro Animation
│   ├── 🏠 Home Section
│   ├── 👤 Introduce Section Preview
│   ├── 🏆 Activity Section Preview
│   ├── 📜 Certificate Section Preview
│   ├── 💼 Project Section Preview
│   └── 📄 Resume Section Preview
│
├── 📁 자기소개 (Introduce-myself.html)
│   ├── 🧭 Header Navigation
│   ├── 👤 기본 프로필 섹션
│   └── ⏰ 성장과정 타임라인
│
├── 📁 활동내역 (Activity.html)
│   ├── 🧭 Header Navigation
│   └── 🏆 활동 타임라인 (6개 활동)
│
├── 📁 자격증 (Certifination.html)
│   ├── 🧭 Header Navigation
│   └── 📜 자격증 카드 그리드
│
├── 📁 프로젝트 (Project.html)
│   ├── 🧭 Header Navigation
│   └── 💼 프로젝트 상세 섹션 (5개 프로젝트)
│
└── 📁 이력서 (Resume.html)
    ├── 🧭 Header Navigation
    ├── 📋 이력서 헤더
    ├── 👤 인적사항
    ├── 💼 경력 및 경험
    └── 🛠 기술 스택
```

## 🚀 설치 및 실행

### 1. 저장소 클론
```bash
git clone https://github.com/yiseol/Introduce-me_prototype.git
cd Introduce-me_prototype
```

### 2. 웹 브라우저에서 실행
```bash
# 로컬에서 직접 실행
open index.html

# 또는 Live Server 사용 (VS Code Extension)
# Live Server로 index.html 실행
```

### 3. GitHub Pages로 배포
이 프로젝트는 GitHub Pages를 통해 자동 배포됩니다.
- URL: `https://yiseol.github.io/Introduce-me_prototype/`

## 🎨 애니메이션 효과

### 홈페이지
- 🎬 **인트로 애니메이션**: 텍스트 페이드 인/아웃 효과
- ✨ **메뉴 카드 호버**: 확대, 그림자 강화, 광선 효과
- 🌊 **부드러운 전환**: CSS Transition 활용

### 서브페이지
- 📈 **상승 효과**: 섹션 박스 호버 시 상승 애니메이션
- 🎯 **호버 애니메이션**: 모든 버튼과 링크에 반응형 효과
- 🔄 **그림자 변화**: 동적 그림자 효과

## 📱 반응형 지원

| 디바이스 | 해상도 | 최적화 |
|----------|--------|--------|
| 📱 **모바일** | 320px ~ 768px | ✅ 완료 |
| 💻 **데스크톱** | 768px ~ 1024px | ✅ 완료 |
| 📟 **태블릿** | 1024px 이상 | ✅ 완료 |

## 🌐 브라우저 호환성

![Chrome](https://img.shields.io/badge/Chrome-4285F4?style=flat-square&logo=googlechrome&logoColor=white)
![Firefox](https://img.shields.io/badge/Firefox-FF7139?style=flat-square&logo=firefox&logoColor=white)
![Safari](https://img.shields.io/badge/Safari-000000?style=flat-square&logo=safari&logoColor=white)
![Edge](https://img.shields.io/badge/Edge-0078D4?style=flat-square&logo=microsoftedge&logoColor=white)

> 모든 최신 브라우저에서 완벽하게 동작합니다.

## 📅 개발 일정

### Phase 1: 기본 구조 (9~10주차) ✅
- [x] Home page 디자인 수정
- [x] 인트로 애니메이션 업그레이드
- [x] 폰트 추가

### Phase 2: 콘텐츠 개발 (11~12주차) ✅
- [x] Introduce, Activity, Certificate page 디자인 수정
- [x] Footer 추가

### Phase 3: 고도화 (13~14주차) ✅
- [x] Project, Resume page 디자인 수정
- [x] 반응형 지원 디자인 최적화
- [x] 브라우저 테스트

### Phase 4: 최종 완성 (15주차) 🔄
- [x] 코드 리팩토링 최적화
- [x] README 문서 최종 작성
- [x] 최종 검토

## 🎯 주요 컴포넌트

### 네비게이션 구조
- **왼쪽**: "INTRODUCE-ME" 로고 (홈페이지 이동)
- **오른쪽**: 5가지 메뉴 (Introduce, Activity, Certificates, Projects, Resume)
- **동작**: 모든 메뉴 클릭 시 해당 페이지로 직접 이동

### 레이아웃 컴포넌트
- 🧭 **헤더 네비게이션** (모든 페이지 공통)
- ⏰ **타임라인 컴포넌트** (자기소개, 활동)
- 🎴 **카드 레이아웃** (자격증, 프로젝트)
- 📐 **반응형 그리드** (모든 페이지)

## 📁 프로젝트 구조

```
introduce-me_prototype/
├── 📄 index.html              # 메인 홈페이지
├── 📁 css/
│   └── 🎨 styles.css          # 통합 스타일시트
├── 📁 pages/
│   ├── 👤 Introduce-myself.html
│   ├── 🏆 Activity.html
│   ├── 📜 Certifination.html
│   ├── 💼 Project.html
│   └── 📄 Resume.html
├── 📁 assets/
│   └── 📋 README.md           # PDF 파일 사용 안내
└── 📖 README.md               # 프로젝트 문서
```

Made with ❤️ by [yiseol](https://github.com/yiseol)

</div>
