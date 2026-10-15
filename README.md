# 온결 피부과 랜딩 페이지

온결 피부과 콘셉트의 한국어 정적 랜딩 페이지입니다. 진료 철학, 진료 분야, 방문 안내, 자주 묻는 질문을 한 페이지에 담았습니다.

## 실행 방법

`dist/index.html`을 브라우저에서 열면 바로 확인할 수 있습니다. 로컬 HTTP 서버를 사용하려면 프로젝트 폴더에서 다음 명령을 실행하세요.

```powershell
py -m http.server 4173 --directory dist
```

그다음 브라우저에서 `http://127.0.0.1:4173/`을 여세요. Python 실행기가 `py`가 아니라면 `python -m http.server 4173 --directory dist`를 사용할 수 있습니다.

## 수정 전 확인

페이지의 병원명, 전화번호, 주소, 진료 시간은 실제 병원 정보로 교체해야 하는 예시입니다. 실제 사용 전 `dist/index.html`의 안내 문구와 연락처를 확인하세요.

## 배포 설정

`.openai/hosting.json`은 Sites 프로젝트 ID와 정적 파일 경로(`dist`)를 지정합니다.

