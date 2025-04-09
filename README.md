# 🚀 Logic-Phantom 기술 블로그

개발의 흔적을 기록하고 지식을 나누는 공간,  
**Logic-Phantom의 개인 기술 블로그**입니다.

[Gatsby](https://www.gatsbyjs.com/) 기반으로 구축되었으며, GitHub Pages를 통해 배포되고 있습니다.

> 📍 블로그 주소: [https://logic-phantom.github.io](https://logic-phantom.github.io)

---

## ✨ 블로그 특징

- Gatsby + GitHub Pages를 활용한 정적 블로그
- Markdown 기반의 간편한 글 작성
- 개발자 친화적인 UI와 다크모드 지원
- 카테고리/태그 기반의 정리된 글 구조
- SEO 최적화 & 퍼포먼스 중심 구성

---

## 🛠 사용 기술

| 영역         | 기술 스택               |
|--------------|--------------------------|
| 프론트엔드   | React, Gatsby            |
| 배포         | GitHub Pages             |
| 스타일링     | Sass, Styled Components  |
| 글 포맷      | Markdown (.md)           |
| CI/CD        | GitHub Actions           |

---

## 📁 프로젝트 구조

```bash
logic-phantom.github.io/
├── content/            # 블로그 글 (Markdown)
├── src/
│   ├── components/     # 공통 UI 컴포넌트
│   ├── pages/          # 라우트 페이지
│   └── templates/      # 포스트 템플릿
├── static/             # 정적 파일 (이미지 등)
├── gatsby-config.js    # Gatsby 설정
├── gatsby-node.js      # Node API 설정
├── package.json
└── README.md
