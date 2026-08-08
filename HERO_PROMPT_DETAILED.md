# HERO IMAGE – DETAILED AI GENERATION PROMPT – FOR APPROVAL

## Purpose
Main hero cutout image for Manashjyoti Bora portfolio – first impression, sits in front of large "DEVELOPER" background text, above CTA cards, must work on desktop 1366-1920px and mobile 320-430px.

## Where it appears
- Section: `.banner-three-area` > `.banner-three-man` > `img src="assets/images/shapes/banner-three-man.png"`
- Position: absolute start-50 translate-middle-x, bottom 27% desktop / 38% mobile (per reference CSS), z-index 1, over DEVELOPER title
- Must not block header logo, CTA buttons, or cause overflow

## Output Filename
`manash-hero-fresh-cool-cutout.png`

## Image Format
- PNG
- Real alpha transparency (RGBA), corners alpha 0 transparent
- Absolutely no checkerboard background baked in (no grey-white squares)
- No white/grey square box behind person
- No card-shaped background unless intentionally part of CSS (not baked into image)
- Clean cutout edges, soft feathered, premium realistic lighting

## Aspect Ratio
- Tall portrait like reference hero: ~800x1200 to 922x1152, not square close-up (reference 1122x1402)
- Body framing: Upper-body to waist, not full-body with legs/shoes, not tight face-only crop
- Scale: Person should be ~70-80% of image height, centered, suitable for overlaying in front of DEVELOPER text, not too tiny nor too zoomed into only face

## Face Identity Rule (PRIMARY)
- Use ONLY raw uploaded photo as identity reference: `/home/user/uploads/file_0000000025a8722fa7b3e9d5dfeccaa6.png`
- Preserve:
  - Exact face identity of Manashjyoti Bora
  - Eyes, eyebrows, nose, lips, mustache, goatee, jawline, chin
  - Skin tone (warm medium), natural youthful age 17+ (not older)
  - Recognizable personality, friendly confident developer learner vibe
  - Short black natural hair as in raw (not curly like reference, keep short)
- Do NOT:
  - Use raw photo as simple crop (must redesign outfit/pose/body)
  - Copy reference person face
  - Generate random AI model face
  - Make him look older, muscular/heavy, celebrity-like, or distorted

## Hair Direction
- Keep short black natural hair as in raw, slightly styled premium but not curly like reference person
- Natural texture, not over-styled, not distorted, no artifacts

## Outfit Direction (Unique Manash Brand – NOT blind copy of reference)
- **Do NOT keep exact black polo crop from raw** – redesign to fresh, cool, realistic, unique portfolio style
- **Do NOT exactly copy reference white shirt / loose black tie / glasses / earphones blindly** – reference is only quality/layout inspiration, not outfit copy requirement per latest direction
- Create **signature personal style** for Manash:
  - Option: Modern black overshirt open over premium black tee, minimal clean, slim/average body, sleeves rolled slightly, youthful
  - Or: Off-white / cream minimal shirt with subtle texture, top button open, smart creative
  - Or: Dark charcoal shirt + layered tee, casual smart, youthful energetic
  - Must be uncommon but realistic, premium, clean, developer portfolio mood, black/white/cream/orange accents #010406 #f5f5f5 #ff5101
  - Avoid cheap AI fashion, random logos, brand logos, unrealistic clothing, heavy jewelry

## Pose Direction
- Fresh cool pose, not passport/ID style
- Slim/average body, upper-body, slight angle like reference hero (reference has slight tilt head, body angle, looking at camera)
- Confident but natural expression, slight smile or neutral, not over-smiling, not serious
- Hands not visible or naturally placed (avoid extra fingers, avoid hands in pockets if full-body – upper-body preferred, no hands needed)
- Body framing: From chest to head, suitable for hero cutout, not full legs

## Lighting Direction
- Premium studio lighting, bright natural outdoor soft shadows, realistic, soft key light from front-left, fill light, gentle rim light, orange/black/cream mood matching website
- No harsh shadow mismatch, no dark underexposed face, no blown highlights

## Background/Cutout Direction
- Real transparent background (alpha 0), no checkerboard pixels, no grey-white squares, no white square box
- Clean cutout edges, soft feathered 1-2px, no hard jagged edges, no halo
- No rounded square box unless intentionally designed in CSS (not baked into image)

## Website Brand Colors
- Match website: #010406 (dark), #f5f5f5 (cream/light), #ff5101 (orange accent)
- Lighting should complement these, not clash

## Mobile/Desktop Usage
- Mobile 360-430px: Header clean, DEVELOPER text dramatic visible behind person, cutout sits naturally in front/around text, no face blocking CTA awkwardly, no square/box background visible, no overflow, no vertical gap, no z-index issues, image scales correctly, not stretched, not too zoomed into only face, not too tiny, hero feels intentionally designed
- Desktop 1366-1920px: Balanced, premium, DEVELOPER title bold visible behind, CTA/card section not blocked, no layout shift, no blurry scaling

## Realism Requirements
- Ultra-realistic, 8k, sharp focus on face, realistic skin texture, pores visible subtle, not plastic skin, not over-smoothed, not AI blurry face
- No low-quality AI look, no cartoonish, no illustration

## Negative Prompt (Must Reject)
- checkerboard background
- grey-white squares pattern baked into image
- square photo box background
- white/grey box behind person
- card-shaped background baked into image unless intentionally part of CSS
- passport photo, ID photo, raw photo crop, black polo exact copy (unless redesigned)
- reference person face, random AI model face, different person, old-looking face, muscular/heavy body
- distorted eyes, distorted glasses, distorted ears, distorted hair, distorted neck, distorted body, extra fingers, bad cutout edges, harsh shadow mismatch, unrealistic pose, blurry face, plastic skin, low-quality AI look, watermark, text in image, logo, brand logo, extra hands, extra legs, shoes (if upper-body preferred), harsh flash, overexposed, underexposed

## Quality Checklist Before Approval
- [ ] Face clearly looks like Manash from raw photo (Identity Accuracy >=95/100)
- [ ] No checkerboard background, real alpha transparency corners alpha 0 (verified via Python PIL)
- [ ] No square/box background visible
- [ ] No passport/ID crop look
- [ ] Outfit unique Manash brand, not blind reference copy, not raw black polo exact copy
- [ ] Pose fresh cool, slim/average body, youthful 17+ creative developer personality
- [ ] Lighting premium realistic, orange/black/cream mood
- [ ] Tall composition 800x1200, not square close-up 800x800
- [ ] Sharp face, no blurry, no watermark, no artifacts, no extra fingers
- [ ] Works on mobile 360-430 and desktop 1366-1920, fits in front of DEVELOPER text, no blocking CTA, no overflow

## Generation Plan After Approval
1. Generate 3-4 options with variations:
   - Option A: Unique premium developer (charcoal overshirt + black tee)
   - Option B: Minimal smart creative (off-white minimal shirt)
   - Option C: Modern youthful portfolio (light grey tee + dark overshirt, slight smile)
   - Option D: Reference-layout-inspired fallback (white shirt loose tie glasses earphones but with Manash short hair, not curly)
2. Create comparison sheet with raw, current broken hero, reference hero, options 1-4
3. Self-score each: Identity Accuracy, Realism, Website Fit, Mobile Hero Potential – must be >=95/100, discard weak
4. Present comparison sheet to you, ask "Which hero option should I use, or what changes do you want?"
5. Wait for approval, do NOT integrate/push before approval

---

**Should I generate 3-4 hero options with this prompt? Please approve or suggest changes to the prompt (e.g., outfit color, pose, with/without glasses, hair style, background, etc.).**
