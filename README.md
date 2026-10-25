# 추론 모델 밑바닥부터 — 한국어 실습 노트북

유튜브 코난쌤(@conanssam) 시리즈 「추론 모델 밑바닥부터」에서 쓰는 한국어 주석판 실습 노트북입니다.
세바스찬 라슈카의 [reasoning-from-scratch](https://github.com/rasbt/reasoning-from-scratch)(Apache 2.0) 노트북을 한국어로 옮기고 주석을 달았습니다. 코드는 원본과 같습니다.

| 노트북 | 원본 장 | 영상 |
|---|---|---|
| [ch02_ko.ipynb](ch02_ko.ipynb) | 2장 사전학습된 LLM으로 글 생성하기 (KV 캐시·compile) | 1편 「같은 AI가 18배 빨라진 코드 3줄」 |
| [ch03_ko.ipynb](ch03_ko.ipynb) | 3장 추론 모델 평가하기 (채점기·MATH-500) | 2편 |
| [ch04_ko.ipynb](ch04_ko.ipynb) | 4장 추론 시간 확장 ① 샘플링과 다수결 | 3편 |
| [ch05_ko.ipynb](ch05_ko.ipynb) | 5장 추론 시간 확장 ② 점수 매기기와 스스로 고치기 | 4편 |

## 쓰는 법
```bash
git clone --depth 1 https://github.com/rasbt/reasoning-from-scratch.git
cd reasoning-from-scratch && uv sync
```
이 저장소의 `chNN_ko.ipynb`를 원본의 `chNN/01_main-chapter-code/` 폴더에 넣고 `uv run jupyter lab`으로 엽니다. 모델 가중치는 처음 실행할 때 내려받습니다.

## 출처와 라이선스
- 원본 코드·노트북: Copyright (c) Sebastian Raschka, Apache License 2.0 (LICENSE)
- 바꾼 내용: NOTICE 참고
- 책: *Build a Reasoning Model (From Scratch)*, Sebastian Raschka, Manning — 자세한 설명과 연습문제는 책을 권합니다.
