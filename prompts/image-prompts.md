# GPT 이미지 생성 프롬프트

정식 그림을 만들 때 쓰는 프롬프트 모음이에요. `art/svg/`의 임시 그림을 참고 이미지로 함께 넣으면 형태가 잘 유지돼요.

## 공통 스타일 (모든 프롬프트 앞에 붙이기)

```
Cute-but-spooky chibi game monster icon, 3/4 front view, centered, full body,
thick dark brown outline, flat cel shading with one soft shadow tone,
big readable silhouette, one exaggerated signature feature,
limited palette, plain transparent background, no text, no frame,
consistent style across a 47-monster roster, 512x512
```

## 지역별 색 팔레트

| 지역 | 주색 | 보조색 |
|---|---|---|
| 안개 숲 | 이끼 초록, 나무 갈색 | 안개 회색 |
| 저주받은 사막 | 모래 황토 | 터키석 청록 |
| 망령의 바다 | 심해 남색, 청록 | 창백한 하늘색 |
| 서리 무덤 | 얼음 하늘색, 흰색 | 남색 |
| 불타는 화산 | 용암 빨강, 주황 | 숯 검정 |

## 등급 표현 규칙 (그림 한 장으로 등급 구분)

- 몸 그림은 같게 두고, 테두리 빛과 오라로 등급을 표현해요.
- F~E 없음 · D~C 파란 테두리 · B~A 금색 테두리 · S~SR 주황 오라 · SSR 무지개 오라 · 각성 ★ 눈이 빛남

## 요괴별 프롬프트

`[공통 스타일]` 뒤에 아래 문장을 붙여 쓰세요. 실제 다른 게임의 캐릭터 생김새를 따라 하지 않도록 `original design` 을 꼭 넣어주세요.

### 00 떠돌이 유령 (세계 곳곳)

- 특징: 하얀 천을 뒤집어쓴 둥근 유령, 텅 빈 검은 눈
- 프롬프트: `original design inspired by 세계 곳곳 folklore creature "떠돌이 유령", signature features: 하얀 천을 뒤집어쓴 둥근 유령, 텅 빈 검은 눈`

### 01 강시 (중국)

- 특징: 청나라 관복과 모자, 이마의 노란 부적, 앞으로 뻗은 두 팔
- 프롬프트: `original design inspired by 중국 folklore creature "강시", signature features: 청나라 관복과 모자, 이마의 노란 부적, 앞으로 뻗은 두 팔`

### 02 도깨비 (한국)

- 특징: 붉은 피부, 노란 외뿔, 송곳니 웃음, 징 박힌 방망이
- 프롬프트: `original design inspired by 한국 folklore creature "도깨비", signature features: 붉은 피부, 노란 외뿔, 송곳니 웃음, 징 박힌 방망이`

### 03 카사오바케 (일본)

- 특징: 보라색 낡은 우산 몸통, 커다란 외눈, 길게 내민 혀, 나막신 한 짝
- 프롬프트: `original design inspired by 일본 folklore creature "카사오바케", signature features: 보라색 낡은 우산 몸통, 커다란 외눈, 길게 내민 혀, 나막신 한 짝`

### 04 레시 (슬라브)

- 특징: 나뭇잎 옷, 나무껍질 얼굴, 사슴뿔 같은 나뭇가지, 빛나는 눈
- 프롬프트: `original design inspired by 슬라브 folklore creature "레시", signature features: 나뭇잎 옷, 나무껍질 얼굴, 사슴뿔 같은 나뭇가지, 빛나는 눈`

### 05 구울 (아라비아)

- 특징: 구부정한 회녹색 몸, 찢어진 망토, 붉은 눈과 송곳니
- 프롬프트: `original design inspired by 아라비아 folklore creature "구울", signature features: 구부정한 회녹색 몸, 찢어진 망토, 붉은 눈과 송곳니`

### 06 미라 (이집트)

- 특징: 온몸을 감은 붕대, 틈새로 빛나는 노란 외눈
- 프롬프트: `original design inspired by 이집트 folklore creature "미라", signature features: 온몸을 감은 붕대, 틈새로 빛나는 노란 외눈`

### 07 모래 진 (아라비아)

- 특징: 터번, 소용돌이 모래 꼬리, 청록색으로 빛나는 눈
- 프롬프트: `original design inspired by 아라비아 folklore creature "모래 진", signature features: 터번, 소용돌이 모래 꼬리, 청록색으로 빛나는 눈`

### 08 갓파 (일본)

- 특징: 머리 위 접시, 노란 부리, 등껍질, 녹색 피부
- 프롬프트: `original design inspired by 일본 folklore creature "갓파", signature features: 머리 위 접시, 노란 부리, 등껍질, 녹색 피부`

### 09 물귀신 (한국)

- 특징: 젖은 긴 검은 머리카락이 얼굴을 덮음, 머리카락 사이 빛나는 한쪽 눈, 물방울
- 프롬프트: `original design inspired by 한국 folklore creature "물귀신", signature features: 젖은 긴 검은 머리카락이 얼굴을 덮음, 머리카락 사이 빛나는 한쪽 눈, 물방울`

### 10 세이렌 (그리스)

- 특징: 붉은 긴 머리, 청록 물고기 꼬리, 조개 장식
- 프롬프트: `original design inspired by 그리스 folklore creature "세이렌", signature features: 붉은 긴 머리, 청록 물고기 꼬리, 조개 장식`

### 11 설녀 (일본)

- 특징: 흰 기모노, 창백한 피부, 긴 검은 머리, 얼음 결정
- 프롬프트: `original design inspired by 일본 folklore creature "설녀", signature features: 흰 기모노, 창백한 피부, 긴 검은 머리, 얼음 결정`

### 12 드라우그 (북유럽)

- 특징: 뿔 달린 투구, 해골 얼굴, 푸르게 빛나는 눈, 낡은 갑옷
- 프롬프트: `original design inspired by 북유럽 folklore creature "드라우그", signature features: 뿔 달린 투구, 해골 얼굴, 푸르게 빛나는 눈, 낡은 갑옷`

### 13 예티 (히말라야)

- 특징: 하얀 털 덩어리 몸, 푸른 회색 얼굴, 작은 송곳니
- 프롬프트: `original design inspired by 히말라야 folklore creature "예티", signature features: 하얀 털 덩어리 몸, 푸른 회색 얼굴, 작은 송곳니`

### 14 살라만더 (유럽)

- 특징: 주황 도마뱀, 등에 타오르는 불꽃
- 프롬프트: `original design inspired by 유럽 folklore creature "살라만더", signature features: 주황 도마뱀, 등에 타오르는 불꽃`

### 15 헬하운드 (영국)

- 특징: 검은 사냥개, 불꽃 갈기와 꼬리, 붉은 눈
- 프롬프트: `original design inspired by 영국 folklore creature "헬하운드", signature features: 검은 사냥개, 불꽃 갈기와 꼬리, 붉은 눈`

### 16 잭오랜턴 (아일랜드)

- 특징: 주황 호박, 노랗게 빛나는 삼각 눈과 톱니 입
- 프롬프트: `original design inspired by 아일랜드 folklore creature "잭오랜턴", signature features: 주황 호박, 노랗게 빛나는 삼각 눈과 톱니 입`

### 17 텐구 (일본)

- 특징: 붉은 얼굴과 긴 코, 검은 날개, 작은 검은 모자
- 프롬프트: `original design inspired by 일본 folklore creature "텐구", signature features: 붉은 얼굴과 긴 코, 검은 날개, 작은 검은 모자`

### 18 바바 야가 (슬라브)

- 특징: 보라 망토의 노파, 큰 코, 절구에 탄 모습, 빗자루
- 프롬프트: `original design inspired by 슬라브 folklore creature "바바 야가", signature features: 보라 망토의 노파, 큰 코, 절구에 탄 모습, 빗자루`

### 19 뱀파이어 (루마니아)

- 특징: 검은 망토와 붉은 높은 깃, 창백한 피부, 송곳니
- 프롬프트: `original design inspired by 루마니아 folklore creature "뱀파이어", signature features: 검은 망토와 붉은 높은 깃, 창백한 피부, 송곳니`

### 20 구미호 (한국·중국)

- 특징: 크림색 여우, 부채처럼 펼친 아홉 꼬리, 푸른 여우불
- 프롬프트: `original design inspired by 한국·중국 folklore creature "구미호", signature features: 크림색 여우, 부채처럼 펼친 아홉 꼬리, 푸른 여우불`

### 21 추파카브라 (라틴아메리카)

- 특징: 회녹색 마른 몸, 등의 가시, 커다란 검은 눈
- 프롬프트: `original design inspired by 라틴아메리카 folklore creature "추파카브라", signature features: 회녹색 마른 몸, 등의 가시, 커다란 검은 눈`

### 22 만티코어 (페르시아)

- 특징: 사자 몸과 갈기, 전갈 꼬리
- 프롬프트: `original design inspired by 페르시아 folklore creature "만티코어", signature features: 사자 몸과 갈기, 전갈 꼬리`

### 23 스핑크스 (이집트·그리스)

- 특징: 사자 몸, 파란·금색 줄무늬 두건을 쓴 사람 얼굴
- 프롬프트: `original design inspired by 이집트·그리스 folklore creature "스핑크스", signature features: 사자 몸, 파란·금색 줄무늬 두건을 쓴 사람 얼굴`

### 24 진의 왕 (아라비아)

- 특징: 푸른 연기 꼬리, 금관, 팔짱
- 프롬프트: `original design inspired by 아라비아 folklore creature "진의 왕", signature features: 푸른 연기 꼬리, 금관, 팔짱`

### 25 루살카 (슬라브)

- 특징: 긴 초록 머리, 창백한 물빛 몸, 머리의 수련 꽃
- 프롬프트: `original design inspired by 슬라브 folklore creature "루살카", signature features: 긴 초록 머리, 창백한 물빛 몸, 머리의 수련 꽃`

### 26 우미보즈 (일본)

- 특징: 파도 위로 솟은 거대한 검은 둥근 머리, 노랗게 빛나는 큰 눈
- 프롬프트: `original design inspired by 일본 folklore creature "우미보즈", signature features: 파도 위로 솟은 거대한 검은 둥근 머리, 노랗게 빛나는 큰 눈`

### 27 켈피 (스코틀랜드)

- 특징: 해초 갈기를 단 청록 말, 물방울
- 프롬프트: `original design inspired by 스코틀랜드 folklore creature "켈피", signature features: 해초 갈기를 단 청록 말, 물방울`

### 28 크라켄 (북유럽)

- 특징: 분홍빛 둥근 머리와 여러 개의 촉수, 노란 눈
- 프롬프트: `original design inspired by 북유럽 folklore creature "크라켄", signature features: 분홍빛 둥근 머리와 여러 개의 촉수, 노란 눈`

### 29 크람푸스 (알프스)

- 특징: 말린 염소뿔, 털북숭이 몸, 길게 늘어진 붉은 혀, 쇠사슬
- 프롬프트: `original design inspired by 알프스 folklore creature "크람푸스", signature features: 말린 염소뿔, 털북숭이 몸, 길게 늘어진 붉은 혀, 쇠사슬`

### 30 서리 트롤 (북유럽)

- 특징: 등에 얼음 가시, 큰 코와 엄니, 푸른 회색 피부
- 프롬프트: `original design inspired by 북유럽 folklore creature "서리 트롤", signature features: 등에 얼음 가시, 큰 코와 엄니, 푸른 회색 피부`

### 31 늑대인간 (유럽)

- 특징: 회색 늑대 머리의 사람, 뾰족 귀, 보름달
- 프롬프트: `original design inspired by 유럽 folklore creature "늑대인간", signature features: 회색 늑대 머리의 사람, 뾰족 귀, 보름달`

### 32 요툰 (북유럽)

- 특징: 얼음 결정 왕관, 흰 수염, 하늘색 거인
- 프롬프트: `original design inspired by 북유럽 folklore creature "요툰", signature features: 얼음 결정 왕관, 흰 수염, 하늘색 거인`

### 33 불가사리 (한국)

- 특징: 쇠 갑옷 같은 회색 곰 몸, 코끼리 코, 등의 쇠가시
- 프롬프트: `original design inspired by 한국 folklore creature "불가사리", signature features: 쇠 갑옷 같은 회색 곰 몸, 코끼리 코, 등의 쇠가시`

### 34 이프리트 (아라비아)

- 특징: 불꽃으로 된 몸, 검은 뿔, 빛나는 눈
- 프롬프트: `original design inspired by 아라비아 folklore creature "이프리트", signature features: 불꽃으로 된 몸, 검은 뿔, 빛나는 눈`

### 35 오니 (일본)

- 특징: 푸른 피부, 두 개의 뿔, 호랑이 무늬 허리띠, 쇠몽둥이
- 프롬프트: `original design inspired by 일본 folklore creature "오니", signature features: 푸른 피부, 두 개의 뿔, 호랑이 무늬 허리띠, 쇠몽둥이`

### 36 타라스크 (프랑스)

- 특징: 가시 등껍질, 사자 머리, 거북 다리
- 프롬프트: `original design inspired by 프랑스 folklore creature "타라스크", signature features: 가시 등껍질, 사자 머리, 거북 다리`

### 37 저승사자 (한국)

- 특징: 넓은 챙의 검은 갓, 검은 도포, 창백하고 무표정한 얼굴
- 프롬프트: `original design inspired by 한국 folklore creature "저승사자", signature features: 넓은 챙의 검은 갓, 검은 도포, 창백하고 무표정한 얼굴`

### 38 해태 (한국)

- 특징: 노란 사자 몸, 청록 곱슬 갈기, 이마의 외뿔, 방울
- 프롬프트: `original design inspired by 한국 folklore creature "해태", signature features: 노란 사자 몸, 청록 곱슬 갈기, 이마의 외뿔, 방울`

### 39 기린 (중국)

- 특징: 비늘 무늬 사슴 몸, 외뿔, 다리의 불꽃, 청록 갈기
- 프롬프트: `original design inspired by 중국 folklore creature "기린", signature features: 비늘 무늬 사슴 몸, 외뿔, 다리의 불꽃, 청록 갈기`

### 40 메두사 (그리스)

- 특징: 뱀 머리카락, 녹색 피부, 금빛 눈
- 프롬프트: `original design inspired by 그리스 folklore creature "메두사", signature features: 뱀 머리카락, 녹색 피부, 금빛 눈`

### 41 케르베로스 (그리스)

- 특징: 머리가 셋인 검은 개, 붉은 눈
- 프롬프트: `original design inspired by 그리스 folklore creature "케르베로스", signature features: 머리가 셋인 검은 개, 붉은 눈`

### 42 미노타우로스 (그리스)

- 특징: 황소 머리, 큰 뿔, 코뚜레, 양날 도끼
- 프롬프트: `original design inspired by 그리스 folklore creature "미노타우로스", signature features: 황소 머리, 큰 뿔, 코뚜레, 양날 도끼`

### 43 펜리르 (북유럽)

- 특징: 거대한 청회색 늑대, 끊어진 쇠사슬, 푸르게 빛나는 눈
- 프롬프트: `original design inspired by 북유럽 folklore creature "펜리르", signature features: 거대한 청회색 늑대, 끊어진 쇠사슬, 푸르게 빛나는 눈`

### 44 요르문간드 (북유럽)

- 특징: 자기 꼬리를 무는 거대한 녹색 바다뱀
- 프롬프트: `original design inspired by 북유럽 folklore creature "요르문간드", signature features: 자기 꼬리를 무는 거대한 녹색 바다뱀`

### 45 야마타노오로치 (일본)

- 특징: 하나의 몸에서 뻗은 여러 개의 보라색 뱀 머리
- 프롬프트: `original design inspired by 일본 folklore creature "야마타노오로치", signature features: 하나의 몸에서 뻗은 여러 개의 보라색 뱀 머리`

### 46 봉황 (동아시아)

- 특징: 붉고 금빛인 새, 길게 늘어진 세 가닥 꼬리(빨강·청록·금색)
- 프롬프트: `original design inspired by 동아시아 folklore creature "봉황", signature features: 붉고 금빛인 새, 길게 늘어진 세 가닥 꼬리(빨강·청록·금색)`
