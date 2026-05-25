# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## 개요

GitHub Pages 정적 사이트 저장소(`itsmesolrr.github.io`)입니다. 별도의 빌드 과정 없이 파일을 그대로 서빙합니다.

## 로컬 실행

저장소 루트에서 아래 명령어로 로컬 서버를 실행합니다:

```bash
python3 -m http.server 8080
```

브라우저에서 `http://localhost:8080/<파일명>.html` 로 접속합니다.

## 배포

`main` 브랜치에 푸시하면 GitHub Pages가 자동으로 `https://itsmesolrr.github.io/` 에 배포합니다.

```bash
git add <파일>
git commit -m "커밋 메시지"
git push
```

## 기술 스택

- 순수 HTML / CSS / JS (프레임워크, 빌드 도구 없음)
- GitHub CLI (`gh`) 설치 및 `itsmesolrr` 계정으로 인증 완료

## 행동 지침

- 가정이 있으면 명시한다
- 불확실하면 진행 전에 먼저 묻는다
- 옵션이 여러 개면 설명 없이 바로 제시한다
- 배포(git push) 전에 반드시 허락을 받는다
