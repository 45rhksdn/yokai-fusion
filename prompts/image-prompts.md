# GPT 이미지·3D 생성 프롬프트

정식 그림을 만들 때 쓰는 프롬프트 모음이에요. `art/demons-3d.png`의 3D 모델 그림을 참고 이미지로 함께 넣으면 형태가 잘 유지돼요.

## 공통 스타일 (모든 프롬프트 앞에 붙이기)

```
Stylized dark-fantasy game demon character, Ars Goetia inspired, 3/4 front view, centered, full body,
thick dark brown outline, flat cel shading with one soft shadow tone,
big readable silhouette, one exaggerated signature feature,
limited palette, plain transparent background, no text, no frame,
consistent style across a 72-demon roster, 512x512
```

## 지역별 색 팔레트

| 지역 | 주색 | 보조색 |
|---|---|---|
| 무너진 솔로몬 신전 | 대리석 흰색, 금색 | 촛불 주황 |
| 잿빛 황야 | 재 회색, 검정 | 뼈 아이보리 |
| 유황 사막 | 유황 노랑, 황토 | 청록 |
| 피의 바다 | 핏빛 진홍 | 검정 |
| 얼어붙은 코키토스 | 얼음 하늘색 | 남색 |
| 불타는 심연 | 용암 빨강, 주황 | 숯 검정 |
| 판데모니움 | 흑요석 보라, 검정 | 금색 |

## 등급 표현 규칙 (그림 한 장으로 등급 구분)

- 몸 그림은 같게 두고, 테두리 빛과 오라로 등급을 표현해요.
- F~E 없음 · D~C 파란 테두리 · B~A 금색 테두리 · S~SR 주황 오라 · SSR 무지개 오라 · 각성 ★ 눈이 빛남

## 악마별 프롬프트

`[공통 스타일]` 뒤에 붙여 쓰세요. 모습은 `docs/monsters.md`의 '모습' 칸을 영어로 옮겨 넣으면 돼요. 예:

- 바알: `three heads (toad, crowned man, cat) on a giant spider body, king of the east`
- 파이몬: `crowned king with feminine face riding a dromedary, trumpets`
- 아스타로트: `fallen angel riding an infernal dragon, holding a viper`

다른 게임의 악마 디자인(예: 다른 작품 속 같은 이름의 캐릭터)을 따라 하지 않도록 `original design` 을 꼭 넣어주세요.
