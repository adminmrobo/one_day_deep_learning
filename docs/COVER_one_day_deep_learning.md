# 표지·장면 지시문 — 「하루에 다 끝내는 딥러닝 서머리 노트 · 오후반」

페이지 바탕은 하얀색입니다. 지금 표지와 교시 머리 그림은 코드로 그린 도감 카드입니다(신경망 도감 `neural_network_atlas`의 세포 색과 그리기 방식 + 캐릭터 팩 표정). 공유 미리보기와 썸네일은 **모아 버전**입니다(`assets/og_one_day_dl_pm.jpg` 1200×630, `assets/thumb_one_day_dl_pm.webp` 600×400). 머신러닝 편(오전반, 시아)과 짝을 이룹니다.

아래는 그림 생성 도구로 일러스트 표지를 따로 받고 싶을 때 쓰는 지시문입니다. 흰 바탕 페이지에 맞게 밝은 장면으로 적었습니다. 받은 그림은 같은 `data-img` 자리에 넣습니다.

## 0. 모아 버전 표지 (오후반) — 머신러닝 편과 짝

| 항목 | 내용 |
|---|---|
| 키 · 판 | cover_one_day_dl_pm · L (16:9, 1920 이상) |
| 짝 | 머신러닝 편 `cover_one_day_ml_am`(오전반, 하품하는 시아, 기준 그림 「05_Yawning」) |
| 그림체 | 기준 그림과 같은 부드러운 애니메이션 일러스트 (픽셀아트 아님) |
| 장소 (앵커) | 같은 고층 사무실의 **오후**. 창밖 도시에 기울어진 햇빛, 오전반보다 따뜻한 빛 |
| 캐릭터 포즈 | 모아 혼자: 의자에 앉아 한 손으로 입을 가리고 크게 하품, 다른 손에는 형광펜 |
| 글자 자리 | 오른쪽 3분의 1은 밝고 단순하게 비움. 제목은 그림에서 떨어뜨려 오른쪽 칸 안쪽에 둠 |
| 대체 글 (alt) | 오후의 밝은 사무실. 창밖으로 도시가 보이는 책상에서 인턴 모아가 한 손으로 입을 가리고 크게 하품합니다. 다른 손에는 형광펜을 들고 있고, 책상에는 모니터와 공책이 놓여 있습니다 |

**지금 상태:** 이 그림체의 모아 그림이 아직 없습니다. 임시로 캐릭터 팩의 졸린 모아(`images/moa/E17_sleepy.png`)와 신경망 구조 그림으로 표지를 만들었습니다. 아래 요청문으로 그림을 받으면 바꿉니다.

**참고 이미지 (함께 올리기):** ① 기준 그림 「05_Yawning」(하품하는 시아) ② 모아 기본 그림 `images/moa/E13_neutral.png` ③ 졸린 모아 `images/moa/E17_sleepy.png`

**Genspark에 붙여 넣기 ↓**
```
첨부한 첫 번째 그림(하품하는 흑발 메이드)과 같은 그림체·같은 장소·같은 구도로, 인물만 두 번째·세 번째 참고 그림의 인물(모아)로 바꾼 표지 그림 1장을 만들어 줘.
- 비율 16:9, 가로 1920px 이상
- 인물은 모아 한 명만. 흑발 인물은 넣지 말 것
- 그림 안에 글자·숫자·로고를 넣지 말 것 (모니터와 서류는 빈 화면이나 뜻 없는 선으로)
- 인물은 왼쪽 절반에, 오른쪽 3분의 1은 밝고 단순하게 비워 둘 것 (제목을 얹을 자리)
- 아래 영어 프롬프트를 그대로 써 줘

Wide 16:9 illustration in exactly the same soft anime illustration style and colour palette as the first attached image: the same bright high-rise office with large windows and a hazy city skyline, but in the afternoon, with slightly warmer, lower sunlight.
One character only: a gentle young woman with long ash-beige wavy hair, a white frilled maid headband with a white ribbon over her left ear, amber-brown eyes, a red and navy plaid bow tie, a camel knit cardigan over a white blouse and a white frilled apron. She sits on an office chair at the desk, covering a big yawn with her right hand, eyes half closed and slightly teary, her left hand loosely holding a highlighter pen over an open notebook on her lap.
Desk on the right: one monitor with a blank dark screen, a small stack of blank papers, an open notebook, one takeaway cup. No readable text anywhere.
Composition: the character sits in the left half of the frame, face and hands away from the edges; the right third of the image stays bright, pale and uncluttered so a title can be placed over it.
Mood: sleepy but warm, an intern worn out from cramming the day before a quiz.
No text, no letters, no numbers, no logos, no real brands, no cigarettes, no alcohol.
```

**점검:** 모아: 애쉬 베이지 웨이브, 왼쪽 귀 위 리본 달린 흰 프릴 머리띠, 호박색 눈, 체크 리본, 카멜 가디건 · 좌우 반전 금지 · 읽히는 글자 없음 · 오른쪽 3분의 1이 비어 있는가.

## 1. 글 표지 (첫 화면 배경)

| 항목 | 내용 |
|---|---|
| 키 · 판 | cover_one_day_dl · L (16:9, 1920 이상) |
| 장소 (앵커) | 낮의 밝은 연구실, 흰 벽과 흰 책상, 시험 전날 자습 분위기 (생활·현장 앵커) |
| 주제 은유 | 책상 위에 펼친 스프링 노트 열한 장과, 벽 모니터의 신경망 도식 |
| 캐릭터 포즈 | 시아·모아: 가운데 책상에 나란히 앉아 노트를 봄(시아는 검지를 세워 순서를 짚고, 모아는 형광펜을 듦) / 조수 하루: 뒤에서 물음표가 뜬 얼굴로 수식 카드를 듦 / 초파리 연구원: 왼쪽에서 돋보기로 노트의 숫자를 들여다봄 / 주판봇: 오른쪽에서 주판을 튕김 / 박사: 뒤쪽 칠판 앞에서 뒤집어 든 시험지를 들고 미소 |
| 대체 글 (alt) | 밝은 연구실. 인턴 시아와 모아가 책상에서 노트를 보고, 조수 하루와 초파리 연구원, 주판봇이 곁에서 돕고, 박사가 칠판 앞에서 시험지를 들고 있습니다 |
| 앞 표지와 다른 점 | 인턴 두 명이 가운데 주인공. 박사는 뒤로 물러나 출제자로 섬 |

**참고 이미지 (함께 올리기):** 박사·조수·초파리 연구원·주판봇·시아·모아 기본 그림 6장 (기준: GitHub `adminmrobo/fruitfly-lab-expressions`의 각 E13). 미공개 X1~X3는 표지에 넣지 않습니다.

**Genspark에 붙여 넣기 ↓**
```
웹페이지 맨 위에 거는 표지 그림 1장을 만들어 줘.
- 비율 16:9, 가로 1920px 이상
- 첨부한 참고 이미지의 여섯 캐릭터(박사, 조수 하루, 초파리 연구원, 주판봇, 인턴 시아, 인턴 모아)를 같은 그림체·같은 외형으로, 모두 등장
- 그림 안에 글자·숫자·로고를 넣지 말 것
- 얼굴과 손은 가장자리에서 떨어진 가운데 영역에, 배경은 흰색에 가깝게, 왼쪽 아래 구석은 비워 둘 것
아래 영어 프롬프트를 그대로 써 줘.

Website top cover illustration, wide 16:9.
Match the art style, proportions and colors of the attached reference images exactly (16-bit RPG style pixel art, bold dark outline, 2–3 tone shading, small highlights).
Scene: a bright, clean research lab in daylight on the day before a quiz, plain white walls and a white floor, soft even lighting, very light gray shadows, a light wooden study desk in the center with open spiral notebooks. The background stays almost pure white so the picture blends into a white web page.
All characters together:
  calm girl maid intern with long straight jet-black hair and side-swept bangs, no headdress, gray eyes, small silver drop earrings, charcoal-black long-sleeved maid dress with a large gray bow and long white frilled apron, sitting at the center desk on the left, raising one index finger while reading a notebook;
  gentle girl maid intern with long ash-beige wavy hair, white frilled maid headband with a ribbon over the left ear, amber-brown eyes, red and navy plaid bow tie, camel knit cardigan, white frilled apron, sitting at the center desk on the right, holding a highlighter pen and smiling;
  girl researcher with long pink hair with two round buns and a navy streak, blue eyes, white lab coat over lavender hoodie, jeans, standing just behind the desk holding a blank flash card with a puzzled look;
  anthropomorphic fruit fly researcher, black body, big red compound eyes, blue helmet with a gold stripe and pink and blue cables, white lab coat over a black vest, black gloves, transparent wings, on the left facing right, inspecting a notebook page with a magnifying glass;
  boxy beige retro CRT-monitor robot, dark green screen face with mint pixel eyes and mouth, short antenna topped with a red-brown abacus bead, gray segmented arms, two small tank treads, on the right facing left, flicking beads on a wooden abacus;
  chibi scientist, thin teal rectangular glasses, spiky black hair with one white streak, small ponytail at the back, white lab coat over black vest and tie, standing at the back near a chalkboard, holding a face-down sheet of paper with a gentle smile.
Visual metaphor of the topic: a white wall board shows a simple neural network diagram drawn with flat colored circles joined by thin gray lines — yellow circles on the left, green circles in the middle, orange circles on the right.
Composition: keep every face and hand inside the central safe area (12% margin left and right, 10% top, 18% bottom); keep the bottom-left corner white and simple; no dark or colored backdrop anywhere.
Mood: focused, warm, a little nervous, friends helping each other study.
No text, no letters, no numbers, no logos, no weapons, no cigarettes, no alcohol, no blood, no real brands.
```

**고칠 때 (같은 대화에서):** `Same characters, same art style and composition. Change only: {고칠 점}. Still no text.`

**점검:** 시험 결과 암시 없음 · 현미경·해부 소품 없음 · 박사·조수·시아·모아 좌우 반전 금지 · 주판봇은 베이지 상자형(흰 둥근 로봇 금지) · 시아는 머리 장식 없음, 모아는 흰 프릴 머리띠.

## 2. 교시 머리 장면 (7장, 3:2, 1200×800)

표지를 먼저 받아 그림체를 확인한 뒤, 표지를 참고 그림으로 함께 올려 3~4장씩 요청합니다. 모든 장면은 "흰 바탕의 밝은 연구실, 가운데 흰 칠판의 신경망 구조 그림, 양옆에 캐릭터" 구도입니다. 구조 그림의 색은 신경망 도감과 같게 합니다(입력 노랑, 은닉 초록, 출력 주황, 기억 파랑, 합성곱·풀링 분홍). 글자·숫자는 넣지 않습니다.

| 키 | 교시 | 칠판 속 구조 그림 | 등장 (왼쪽 → 오른쪽) |
|---|---|---|---|
| sc_period1 | 1교시 뉴런 한 개 | 노란 입력 셀 셋이 주황 출력 셀 하나로 이어짐 | 시아(생각) · 조수 하루(단단한 눈빛) · 모아(반짝 눈) |
| sc_period2 | 2교시 구부리기 | 입력 셋, 초록 은닉 셀 넷, 출력 둘 | 모아(생각) · 초파리 연구원(돋보기) · 시아 |
| sc_period3 | 3교시 틀린 만큼 고치기 | 은닉층 두 겹, 뒤에서 앞으로 되돌아오는 빨간 고리 | 시아(단단한 눈빛) · 조수 하루(보고) · 모아(응원) |
| sc_period4 | 4교시 학습 요령 | 은닉 셀 몇 개가 X 표시로 꺼져 있음 | 모아(기록 소개) · 주판봇(주판) · 시아(하품) |
| sc_period5 | 5교시 사진은 훑는다 | 분홍 합성곱·풀링 셀이 가까운 셀끼리만 이어짐 | 시아(검지) · 초파리 연구원(돋보기) · 모아(놀람) |
| sc_period6 | 6교시 순서는 기억한다 | 파란 기억 셀마다 자기에게 돌아오는 고리 | 모아(찻잔) · 주판봇(주판) · 시아(생각) |
| sc_final | 종례 모의고사 | 여섯 교시의 구조 그림 여섯 장 | 시아 · 모아 · 박사(판정 자세) · 조수 하루 |

**장면 공통 영어 프롬프트 틀**
```
Scene illustration, 3:2, 1200x800. Same art style and characters as the attached cover (16-bit RPG style pixel art, bold dark outline).
A bright white research lab, almost pure white background, a white board in the center showing a flat neural-network diagram: {칠판 속 구조 그림을 영어로}.
Characters, left to right: {등장 캐릭터와 표정}. They look at the board.
Keep faces inside the central safe area. No text, no letters, no numbers, no logos.
```

## 3. 반영 규격

- 표지 1600×900, 장면 1200×800, WebP로 페이지에 내장(한 편 600KB 이하).
- 목차 썸네일과 공유 미리보기(og:image)는 `assets/thumb_one_day_dl_pm.webp`와 `assets/og_one_day_dl_pm.jpg`입니다. 모아 일러스트를 받으면 이 두 파일을 그 그림으로 다시 만듭니다.
