# 랜덤 코드 연습 (Random Chord Practice)

랜덤한 코드(화음)를 일정한 간격으로 보여주는 연습용 웹사이트입니다.

## 사용법

`index.html`을 브라우저에서 열기만 하면 됩니다 (빌드·설치 불필요).

- **코드 종류**: Major, Minor, 7, maj7, m7, 6, m6, sus2, sus4, aug, dim, dim7, m7♭5, 9, maj9, m9, add9 중에서 연습할 종류를 체크리스트로 선택
- **간격**: 다음 코드로 넘어가는 시간을 1~60초로 설정
- **루트음 표기**: 혼용(B♭·E♭·F♯ 등 실전 표기) / 샾만 / 플랫만 선택
- **구성음 표시**: 코드 이름 아래에 구성음(예: F♯m7♭5 → F♯ A C E) 표시 여부 선택
- **시작/정지** 버튼으로 제어, 화면 클릭이나 스페이스바로 즉시 다음 코드
- 설정은 브라우저(localStorage)에 자동 저장됩니다

## 배포

`main` 브랜치에 푸시되면 GitHub Actions가 자동으로 GitHub Pages에 배포합니다:

<https://puzzling612.github.io/random_chord/>

첫 배포가 실패하면 저장소 **Settings → Pages**에서 Source를 **GitHub Actions**로 한 번 설정해 주세요.
