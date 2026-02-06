# Agent 코딩 가이드

## 사전 준비

### 1. Claude Code 설치 확인

```bash
claude --version
```

### 2. GitHub CLI 설치 및 인증

```bash
# 설치
brew install gh

# 인증
gh auth login
```

### 3. 플러그인 설정

```bash
# code-simplifier 플러그인 설치
claude plugin install code-simplifier@claude-plugins-official
```

## 실행 방식

```bash
claude -p "프롬프트 내용" --dangerously-skip-permissions
```

## 작업 방식

1. **작업 요청 접수**: main branch에서 pull 받고 새 작업 branch 생성
2. **작업 진행**: claude code로 코드 수정
3. **작업 완료**: 커밋 후 GitHub Pull Request 생성, 확인 가능한 PR URL 공유
