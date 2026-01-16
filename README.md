# Xperion Wiki Content

이 레포지토리는 Xperion Wiki의 문서 콘텐츠를 저장합니다.

## 디렉토리 구조

```
xperion-wiki-content/
├── content/          # 위키 문서 저장 폴더
│   ├── {slug}.md    # 마크다운 문서들
│   └── ...
└── README.md
```

## 문서 형식

모든 문서는 Markdown 형식으로 작성되며, YAML Frontmatter를 포함합니다:

```markdown
---
title: 문서 제목
category: characters/player
author: 작성자
status: active
summary: 문서 요약
tags:
  - 종족/엘프
  - 클래스/팔라딘
created: 2026-01-08T00:00:00
updated: 2026-01-08T00:00:00
---

# 문서 내용

여기에 마크다운 내용을 작성합니다.
```

## 관련 프로젝트

- **메인 프로젝트**: https://github.com/ginger1541/xperion-wiki
- **프론트엔드 배포**: https://frontend-beta-ivory-83.vercel.app
- **백엔드 API**: http://34.29.153.88

---

**자동 생성**: Xperion Wiki System
**최종 업데이트**: 2026-01-16
