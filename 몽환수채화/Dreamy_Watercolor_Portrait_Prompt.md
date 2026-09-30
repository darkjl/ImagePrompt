# 몽환적 수채화 인물화 (마스터 템플릿 × 얼굴 아이덴티티) 프롬프트

## 1. 개요 및 아트 디렉팅 해설
- **콘셉트 테마**: 기존 마스터 수채화 템플릿의 조형적 틀(포즈, 구도, 흑연 연필 스케치 선, 불규칙하게 떨어진 수채화 물감 번짐 효과, 종이 질감)을 엄격히 고정한 채, 업로드된 사진에서 오직 '얼굴 골격(Identity)'만을 추출하여 몽환적이고 아련한 수채화 인물화로 재해석
- **핵심 아트 디렉팅 & 조형 원리**:
  - **얼굴 렌더링 (Face Rendering — 최우선 원칙)**:
    - 사진이나 매끄러운 3D 렌더처럼 보이지 않도록, 얼굴 또한 배경/옷/머리카락과 완전히 동일한 기법(흑연 연필 선 + 떨어진 수채화 물방울 번짐)으로 표현.
    - **연필 밑선(Graphite First)**: 턱선, 눈꺼풀, 코(2~3개 짧은 선), 입술 주변에 얇고 살짝 끊어지는 흑연 스케치 선이 뚜렷하게 노출됨.
    - **종이를 피부 베이스로 활용(Paper as Skin)**: 부드러운 피부 그라데이션 대신 거친 코튼 수채화지의 결 자체를 피부 톤으로 활용.
    - **우연한 물감 방울(Dropped Pigment)**: 마른 경계선(Hard dried edge)을 지닌 2~4개의 불규칙한 블룸(Bloom), 안쪽은 연하고 테두리는 진한 물감 고임. 화장처럼 칠해진 것이 아닌 무작위로 번진 물감 얼룩.
    - **눈 & 입술**: 눈은 40~50%쯤 지그시 감은 나른하고 몽환적인 시선(상향 응시). 매트하고 투명한 더스티 로즈빛 입술 번짐(광택/립라인 없음).
  - **시선과 고개 각도 (Head Tilted Upward)**:
    - 원본 사진의 정면 각도를 무시하고, 고개를 30~40도 뒤로 젖혀 턱을 높이 들고 하늘/빛을 올려다보는 우아한 포즈. 턱 밑선과 길게 뻗은 목선, 턱을 가볍게 받친 손가락.
  - **아이덴티티 보존 & 로판풍 미화 (55:45)**:
    - 원본 얼굴의 고유 특징(눈매, 눈썹, 콧대, 입매, 얼굴 윤곽선)을 살려 인물을 확실히 인식할 수 있게 하되, 한국 로맨스 판타지 표지 수준의 정제된 V라인과 섬세한 이목구비로 미화.
  - **배경의 은은한 고양이 (Subtle Background Cat)**:
    - 좌측 상단/좌측 배경에 눈에 띄지 않게 작게(손 크기 이하) 자리 잡은 고양이. 인물과 동일하게 성긴 연필선과 옅은 더스티 블루/라벤더 수채화 번짐으로 스케치되어 종이 여백 속으로 녹아드는 분위기 있는 실루엣.
  - **시그니처 서명 (Artist Signature)**:
    - 우측 하단 모서리 여백에 연필 또는 묽은 수채화로 자연스럽게 흘려 쓴 작고 단정한 **"JL"** 서명.
  - **무드 및 팔레트**:
    - 더스티 블루, 파우더 블루, 라벤더, 블러시 핑크, 모브, 소프트 그레이 등 맑고 투명하며 아련한 파스텔 톤 팔레트.

---

## 2. 프롬프트 전문 (코드 블록)

```text
# MASTER WATERCOLOR TEMPLATE × UPLOADED FACE (IDENTITY ONLY)

Use the EXISTING WATERCOLOR ARTWORK as the fixed MASTER TEMPLATE.
Use ONLY the CURRENTLY UPLOADED PORTRAIT as facial identity reference.
Analyze each new upload from scratch; never reuse previous faces.

CORE RULE:
PHOTO → WHO she is (facial structure only).
TEMPLATE → EVERYTHING ELSE (pose, angle, expression, hair, hand, body,
clothing, background, composition, crop, sketch, palette, texture, mood,
and HOW the face is painted).
Only two additions are allowed: a subtle cat in the background
and a small "JL" signature (see sections 7 and 8).

[1. FACE RENDERING — HIGHEST PRIORITY]
The face must be rendered with the SAME technique as the hair,
clothing, and background: graphite sketch + dropped watercolor.
It must NOT look like a photograph.

PENCIL FIRST:
Draw the face as a visible graphite sketch: thin, slightly broken
outlines around the jaw, eyelids, nose (2–3 short lines only),
and lips. Sketch lines must be clearly visible on the face.

PAPER AS SKIN:
The face base is white watercolor paper with visible grain.
No smooth skin gradient. No photographic shadows.
No soft blending between light and shadow.

DROPPED PIGMENT:
Color appears as a few watercolor DROPS that landed on the face:

- 2–4 irregular blooms with hard, darker dried edges
- lighter centers, uneven pigment pooling
- some blooms extend beyond the face contour into hair or neck
- one small dusty-blue or lavender stain from the background
may cross the cheek or temple
- tiny splatter dots may land on the face
Blooms are placed asymmetrically and randomly,
not where makeup would be applied.

EYES:
Eyes half-open, about 40–50% closed — heavy, relaxed lids,
softly gazing upward in a dreamy, faraway look.
The upper part of the iris is hidden under the lowered lids;
the lower part of the iris is visible with a soft graphite tone
and a tiny untouched-paper highlight.
Long lashes angled downward, casting a soft graphite shadow line.
Delicate graphite eyelid creases, minimal dark pigment,
a faint dusty-rose or lavender bloom on one eyelid.
NOT fully closed. NOT wide open. NOT staring at the viewer.
No photographic eyes, no heavy eyeliner.

LIPS:
A single bloom of diluted dusty rose with an irregular dried edge
and paper texture visible through it.
Not glossy, not bright red, no highlight, no sharp lip line.

CONSISTENCY:
The face must look equally hand-made as the hand and clothing.
If the face is smoother or more realistic than the hair, it is WRONG.

[2. POSE — HEAD TILTED UPWARD]
The head is clearly tilted BACK and the face looks UPWARD,
as if gazing at the sky or light above.

- head tilted back about 30–40 degrees
- chin lifted high; underside of the jaw and chin clearly visible
- long, extended neck line and visible throat
- face seen slightly from below: nostrils slightly visible,
forehead foreshortened, eyes positioned higher on the face
- eyes half-open (about 40–50% closed), gaze drifting upward, dreamy
- lips gently parted
- hand fingertips touching beneath the chin, supporting the lifted jaw

Ignore the head angle of the uploaded photo completely.
Even if the source face is frontal, rotate it upward to match this pose.
NOT a frontal face. NOT a slight chin lift.

[3. TEMPLATE LOCK]
Do not redesign, rearrange, or reinterpret the template. Keep exact:
composition, crop, framing, subject size/placement,
hand position and finger placement beneath the chin,
dark hair with bangs and loose strands, clothing, airy background,
paint splashes, drips, blooms, and degree of unfinishedness.
The source face adapts to the template — never the reverse.

[4. IDENTITY FROM PHOTO]
Extract only facial structure: eye shape/angle/spacing, eyelids,
eyebrows, nose bridge/length/width/tip, mouth width, lip shape,
face width/length, cheeks, jaw, chin, forehead, feature spacing,
characteristic asymmetry. The result must be clearly recognizable
as the same person.
Identity comes from SHAPE and PENCIL LINES only — never from
photographic shading or color.
Ignore everything else in the photo: hair, pose, head angle, gaze,
expression, hands, clothing, accessories, background, lighting,
shadows, skin tone, makeup, blush, contrast, photographic texture.

[5. BEAUTIFICATION]
Identity 55% / Beautification 45%.
Idealize into a premium Korean romance-fantasy cover heroine:
elegant contour, soft V-line, refined chin and nose, balanced eyes,
long lashes, soft feminine lips.
"The same person idealized" — NOT "a different beautiful woman,"
NOT a generic webtoon/anime face.

[6. PAINT-DROP PRINCIPLE — WHOLE SHEET]
Watercolor looks accidentally dropped across the whole sheet and
ignores anatomical boundaries (e.g. background → hair → cheek,
cheek → neck → clothing, hand → wrist → clothing).
Use blooms, wet-on-wet bleeding, backruns, pooling, granulation,
feathered and cauliflower edges, droplets, drips.
Face, hair, hand, neck, clothing, and background must feel like ONE
sheet of paper — never a finished face surrounded by splashes.
Hand and neck: graphite outlines, mostly paper, a few stains.

[7. BACKGROUND CAT — SUBTLE]
Add one small cat in the background, barely noticeable at first glance.

- placed in the upper-left or left background area, away from
the face and hand, never overlapping or covering the woman
- small in scale (roughly the size of her hand or smaller)
- sitting quietly or curled up, looking softly upward like the woman
- drawn with the SAME technique: loose graphite sketch lines and
a few pale dusty-blue / soft-gray / lavender watercolor blooms
- mostly unfinished: parts of its body dissolve into untouched paper
and the surrounding watercolor stains
- no solid fill, no detailed fur, no cute cartoon style
The cat is an atmospheric detail, not a second subject.
It must not change the overall composition or visual balance.

[8. SIGNATURE — "JL"]
Add a small handwritten signature "JL" in the bottom-right corner.

- looks like an artist's hand signature on the original artwork
- written in graphite pencil or thin diluted charcoal-brown watercolor
- small and understated, slightly slanted, natural hand-drawn stroke
- placed on the paper margin, not overlapping the figure or major blooms
- exactly the two letters "JL", no other text, no date, no frame, no logo

[9. MOOD & ATMOSPHERE — STRONGER]
The image must feel like a quiet, emotional moment captured
in watercolor: as if she is feeling soft light or wind from above,
lost in a memory or a daydream.

- expression: serene, tender, slightly melancholic, gently longing
- soft diffused light falling from above onto her lifted face,
expressed by leaving the upper face as luminous untouched paper
- a few loose hair strands drifting upward or sideways, as if in a breeze
- slightly more airy negative space around the face
- cool dusty-blue and lavender blooms around the head,
with small blush-pink accents for warmth
- a few tiny scattered droplets near the face like floating light
The atmosphere comes from light, air, and emotion —
not from more detail or more color.

[10. STYLE]
Palette: dusty blue, powder blue, muted indigo, lavender, blush pink,
dusty rose, mauve, soft gray, charcoal brown
(peach and beige only as small accents on hand/clothing).
Transparent, watery, luminous, irregular.
Graphite: thin exploratory lines, overlapping sketch marks, broken
contours, loose hair strokes — hand-drawn, not clean digital lineart.
Visible watercolor paper grain through the entire figure.

[11. FORBIDDEN]
Any change to composition, hand, hair, clothing, or background
(except the subtle cat and the "JL" signature).
Frontal face. Level head. Slight chin lift only.
Source-photo head angle.
Fully closed eyes. Wide-open eyes. Direct gaze at the viewer.
Photographic face, face paste, obvious face swap.
Smooth skin blending, flesh-tone base wash, airbrush, plastic or
glossy skin, pores, realistic shadows under nose or chin,
symmetrical blush, fully modeled cheeks.
Glossy red lips, lip highlights, sharp lip line.
A face that looks cleaner or more realistic than the rest of the image.
A large, detailed, cartoonish, or foreground cat.
Any text other than "JL". Typed or digital-font signature.
Oil, acrylic, gouache textures. Cel shading, anime or webtoon faces.

[FINAL CHECK]

- Recognizable as the uploaded person through structure?
- Beautified without losing identity?
- Head clearly tilted back, looking upward, with the underside
of the chin and the neck line visible?
- Eyes half-open (about 40–50% closed), gazing upward, dreamy?
- Template hair, hand, clothing, background unchanged?
- Pencil lines clearly visible on the face?
- Paper grain visible on the face, no smooth skin gradient?
- Face color appears as dropped blooms with dried edges?
- Lips matte and watercolor-like, not glossy red?
- Face no more realistic than hair, hand, and clothing?
- Small sketched cat present in the background, subtle and unfinished?
- Small handwritten "JL" in the bottom-right corner?
- Does the image feel quiet, emotional, and atmospheric?
If any answer is NO, fix before output.

REMINDER: Head tilted upward, eyes half-open with a dreamy upward gaze.
The face is a pencil sketch on paper with a few dropped watercolor
blooms — NOT a photograph.
A faint sketched cat in the background. "JL" signed bottom-right.
"This exact person was originally drawn and painted in this
watercolor artwork." ONLY THE FACIAL IDENTITY CHANGES.
```

---

## 3. 결과물 비교 갤러리

| 생성 모델 | 결과 이미지 |
| :--- | :--- |
| **Google Gemini** | ![Gemini 결과](./제미나이.jpg) |
| **OpenAI GPT** | ![GPT 결과](./GPT.png) |
