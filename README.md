# Team Policy Manager

🎯 **팀 정책 문서 협업 관리를 위한 Git 기반 Starter Kit**

개발자들과 함께 정책을 정의하고 수정하며, 확정된 정책 문서를 버전 관리하는 시스템입니다.

## ✨ 주요 기능

- 📝 **마크다운 기반 정책 작성** - 개발자 친화적인 문서 작성
- 🔄 **Git 기반 버전 관리** - 모든 변경 이력 자동 추적
- 🔍 **Pull Request 리뷰** - 정책 변경에 대한 검토 및 승인
- 📋 **정책 템플릿** - 일관된 정책 문서 작성
- 🔗 **정책 간 참조** - 관련 정책 링크 및 참조

## 📦 기술 스택

- Git (버전 관리)
- Markdown (문서 작성)
- GitHub/GitLab (협업 플랫폼)

## 🚀 빠른 시작

### 1. Repository 클론

```bash
git clone https://github.com/yaygee/team-policy-manager.git
cd team-policy-manager
```

### 2. 새 정책 작성

```bash
# 정책 템플릿 복사
cp docs/templates/policy-template.md docs/policies/새로운-정책.md

# 편집
code docs/policies/새로운-정책.md
```

### 3. 변경사항 커밋

```bash
git add docs/policies/새로운-정책.md
git commit -m "feat: 새로운 정책 추가"
git push origin main
```

### 4. Pull Request 생성

1. GitHub에서 새 브랜치 생성
2. 정책 작성 후 커밋
3. Pull Request 생성
4. 팀원 리뷰 후 병합

## 📁 프로젝트 구조

```
team-policy-manager/
├── docs/
│   ├── policies/          # 정책 문서
│   │   └── example-policy.md
│   ├── templates/         # 정책 템플릿
│   │   └── policy-template.md
│   └── archives/          # 과거 버전 (선택)
├── README.md
└── CONTRIBUTING.md
```

## 📝 정책 작성 가이드

### 정책 문서 구조

```markdown
# 정책 제목

## 개요
- **작성일**: YYYY-MM-DD
- **작성자**: 이름
- **상태**: 초안 | 검토중 | 승인됨

## 목적
이 정책의 목적을 설명합니다.

## 적용 범위
누구에게, 어떤 상황에 적용되는지 설명합니다.

## 정책 내용
구체적인 정책 내용을 작성합니다.

## 관련 정책
- [관련 정책 1](./related-policy.md)
```

## 🤝 기여 방법

자세한 내용은 [CONTRIBUTING.md](./CONTRIBUTING.md)를 참고하세요.

## 📄 라이선스

MIT License

---

**Made with ❤️ for better team collaboration**
