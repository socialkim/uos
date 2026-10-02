# 서울시립대 수업 포털 (socialkim.github.io/uos)

```
uos/
├── index.html, courses.json      ← 수업 목록 (학기 추가 시 courses.json 한 줄)
└── aibiz-2026-2/                 ← AI실무활용과 스마트비즈니스 2026년 2학기
    ├── index.html, course.json   ← 학기 포털 (16주 흐름 · 패들릿)
    ├── 260911/index.html         ← 수업 날짜(YYMMDD) 폴더 = 실습 페이지
    └── 261002/index.html …
```

## 매주
github.com/socialkim/uos → `aibiz-2026-2` 폴더로 들어가기 → Add file → Upload files → 날짜 폴더(예: `261016`)째 끌어다 놓기 → Commit.
포털 버튼은 자동으로 켜진다.

## 지난 학기 자료 넣기
1. `과목-연도-학기` 폴더를 만들고(예: `prompt-2026-1`) 날짜 폴더들을 넣는다.
2. 학기 포털이 필요하면 `aibiz-2026-2/index.html`과 `course.json`을 복사해 계획만 바꾼다.
3. `courses.json`에 한 줄 추가 (`"current": false`).
