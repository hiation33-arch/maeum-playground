# 마음 놀이터

색채심리 타로, 감정 기록, 손가락 체조 게임 — 잠깐 멈춰 나를 들여다보고 쉬어가는 작은 웹 도구를 모은 페이지입니다.

**바로가기 → https://hiation33-arch.github.io/maeum-playground/**

카드를 누르면 각 도구가 새 탭에서 열립니다.

---

## 도구 목록

| 도구 | 하는 일 | 링크 |
|---|---|---|
| **컬러 타로** | 마음에 끌리는 색 5장으로 색채심리 기반 오늘의 타로 | [열기](https://hiation33-arch.github.io/color-tarot/) |
| **류위닝 타로** | 컬러 타로와 같은 방식, 결과에 류위닝 사진·문구가 함께 나오는 팬 버전 | [열기](https://hiation33-arch.github.io/liu-yuning-tarot/) |
| **Emotion Journey** | 100여 개의 감정 단어를 고르고 내려놓으며 지금 내 감정을 만나는 여정 | [열기](https://hiation33-arch.github.io/emotion-journey/) |
| **손가락 체조 게임** | 천천히 따라 하는 손가락 체조 리듬 게임 (시니어용) | [열기](https://hiation33-arch.github.io/senior-gesture-game/) |
| **나를 닮은 꽃** | 질문 5개로 지금 나를 닮은 꽃과 꽃말·오늘의 한마디를 찾는 감성 테스트 | [열기](https://claude.ai/artifact/RjtWC8yobC2qivRgRGvUAB) |

---

## 사용 안내

1. **놀이터 페이지**를 연다 → https://hiation33-arch.github.io/maeum-playground/
2. 해보고 싶은 도구의 카드를 누른다 (새 탭에서 열림).
3. 타로: 끌리는 색을 5장 고르면 결과가 나옴.
4. Emotion Journey: 감정 단어를 고르고 추리며 6단계로 진행 (5~10분).
5. 손가락 체조: "시작하기"를 누르고 화면을 천천히 따라 함.
6. 나를 닮은 꽃: "시작하기"를 누르고 질문 5개에 답하면 꽃 결과가 나옴 ("결과 복사하기"로 공유 가능).
7. 놀이터로 돌아올 때는 브라우저 **뒤로 가기**.

---

## 새 도구 추가하기

1. `thumbs/`에 화면 캡처 이미지를 넣는다 (`새도구.png`).
2. `index.html`의 `<ul class="grid">` 안, "다음 도구 자리" `<li>` **앞에** 카드 `<li>`를 복사해 붙이고 링크·설명·이미지 경로를 바꾼다.
3. 세로로 긴 모바일 화면 캡처는 `<div class="thumb center">` 로 지정한다.
4. 마스트헤드의 `도구` 숫자와 `업데이트` 날짜를 갱신한다.
5. commit & push → 1~2분 뒤 자동 배포.

---

관련: [프롬프트 도구함](https://hiation33-arch.github.io/prompt-toolkit/)

made by hiation
