# Instagram Overlay Guidelines — Ratio Based
# Logo & Slogan Placement Rules (All measurements as ratios of image dimensions)

## WHY RATIOS NOT PIXELS
All measurements are expressed as ratios (0.0–1.0) of the image width (W) or height (H).
This ensures correct proportions regardless of output resolution.
Example: marginTop = 0.059 × H means 5.9% from top edge.

---

## FORMAT 1: Square Post 1:1

Canvas: 1080×1080 (W=H)
Instagram UI: NONE — feed posts have no UI overlays

### SLOGAN
- Position: top-left OR top-right (alternate randomly for variety)
- Distance from top: 0.074 × H
- Distance from side: 0.055 × W
- Font size: 0.105 × W
- Line spacing: 1.15 × font_size
- Max line width: 0.45 × W (so text does not cross center)
- Color: brand primary color
- Style: bold, with shadow (3px offset, 50% opacity black)

### LOGO
- Position: OPPOSITE corner from slogan (bottom)
- If slogan top-left → logo bottom-right
- If slogan top-right → logo bottom-left
- Distance from bottom: 0.065 × H
- Distance from side: 0.055 × W
- Logo width: 0.24 × W

### SAFE ZONE
- All elements must stay inside: 0.056×W margin from all edges
- Never place over faces or product

---

## FORMAT 2: Portrait Post 4:5

Canvas: 1080×1350 (W < H)
Instagram UI: NONE — feed posts have no UI overlays
NOTE: Profile grid crops to 1:1 center — keep critical elements in center 74% of height

### SLOGAN
- Position: top-left OR top-right (alternate randomly)
- Distance from top: 0.059 × H
- Distance from side: 0.055 × W
- Font size: 0.105 × W
- Line spacing: 1.15 × font_size
- Max line width: 0.45 × W
- Color: brand primary color
- Style: bold, with shadow (3px offset, 50% opacity black)

### LOGO
- Position: OPPOSITE corner from slogan (bottom)
- If slogan top-left → logo bottom-left (same side — matches nümunə şəkil)
- Distance from bottom: 0.052 × H
- Distance from side: 0.055 × W
- Logo width: 0.25 × W

### SAFE ZONE
- All elements inside: 0.056×W from left/right, 0.044×H from top/bottom
- Grid crop safe area: central 0.74 of height — keep main content here

---

## FORMAT 3: Story/Reels 9:16

Canvas: 1080×1920 (H >> W)
Instagram UI overlays:
- TOP: 0.130 × H (profile name, progress bar, close button)
- BOTTOM: 0.167 × H (send message bar, reaction buttons)
- RIGHT: 0.111 × W (like, comment, share buttons)

### SLOGAN
- Position: TOP CENTER (centered horizontally)
- Distance from top: 0.160 × H (safely below UI)
- Horizontal: centered (x=0 from center)
- Font size: 0.105 × W
- Line spacing: 1.15 × font_size
- Max line width: 0.75 × W
- Color: brand primary color
- Style: bold, with shadow

### LOGO
- Position: BOTTOM CENTER (centered horizontally)
- Distance from bottom: 0.190 × H (safely above UI)
- Horizontal: centered (x=0 from center)
- Logo width: 0.24 × W

### SAFE ZONE
- Top buffer: 0.130 × H minimum
- Bottom buffer: 0.167 × H minimum  
- Right buffer: 0.111 × W minimum
- Left buffer: 0.056 × W minimum
- All critical content in central 70–80% of frame

---

## LOGO SELECTION RULE
- Dark background (luminance < 0.3) → use WHITE logo
- Light background (luminance > 0.7) → use COLOR logo
- Unknown/mixed → use WHITE logo with shadow

## FONT SIZE RULE
- Base font size = 0.105 × image_width
- Minimum font size = 0.085 × image_width (never smaller)
- Maximum font size = 0.120 × image_width (never larger)

## SLOGAN SPLIT RULE
- Always split slogan into 2 lines at the middle word
- Each line max 0.45 × W for feed posts
- Each line max 0.75 × W for story format

## SHADOW RULE
- Always add text shadow for readability
- Shadow offset: 3px (or 0.003 × W)
- Shadow opacity: 50%
- Shadow color: black

## CONSISTENCY RULE
- Same logo position across all posts of same brand
- Slogan position can alternate left/right for variety
- Never place logo or slogan over human faces
- Never place over the hero product
