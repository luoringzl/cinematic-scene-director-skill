---
name: cinematic-scene-director-ultimate
description: Ultimate production design and cinematography engine with built-in Intelligent Style Advisor (proactive design recommendations when unsure of style), 18 Realist & High-Concept Stylized Art Directions, PBR micro-surface material libraries, DP lighting databases, 5 Scene State modifiers, 1:1 indoor-outdoor architectural continuity, and full historical/2020s set-dressing dictionaries. Use when designing film/drama scenes, diagnosing visual styles for a show, generating differentiated design drafts, or creating 16:9/9:16 AI scene prompts.
---

# Cinematic Scene Director Ultimate

A complete industrial-grade production design and cinematography engine equipped with four built-in reference databases:

1.  **`references/pbr-materials.md`**: 6 categories of PBR micro-surface textures (Stone/Fantasy Minerals, Timber/Lacquer, Forged Metals, Plaster/Terrazzo, Fabrics/Leather/Paper, and Wet/Dry Paving).
2.  **`references/dp-lighting.md`**: 6 categories of Cinematography Lighting & Optical Locks (Chiaroscuro Gobo Cuts, Practical Lamp Pools, Extreme Weather/God Rays, Urban Neon Optics, Volumetric Media, and Camera/Lens/Film Stock Locks).
3.  **`references/era-architecture-db.md`**: Full historical and contemporary architectural set-dressing dictionaries covering **8 Western Historical Eras (500 BC to 2020s)** and **Chinese Dynasties / Pagodas / Xianxia / Republican / Modern Urban** across Urban Exteriors, Rural Landscapes, and Interiors.
4.  **`references/stylized-and-states.md`**: **Intelligent Style Advisor Decision Matrix**, **6 High-Concept Stylized Art Directions (Styles 13–18)**, **5 Narrative Scene State Modifiers**, **Functional Shot Grammar**, and **Practical-Feel VFX Overlays**.

## Mandatory Resource Loading Rule

Whenever this skill is triggered to design scenes, recommend styles, or write prompts, load the relevant reference databases:

  - Load `references/stylized-and-states.md` whenever the user is unsure what visual style fits their project, wants design advice/recommendations, requests stylized/high-concept visuals, or needs scene state transitions (e.g., battle-damaged, abandoned).
  - Always load `references/pbr-materials.md` and `references/dp-lighting.md` to pull exact physical surface and lighting phrases.
  - Load `references/era-architecture-db.md` to pull authentic period architectural structures and set dressing for the target era/region.

## Core Workflow

### Step 1: Intelligent Style Consultation & Proactive Design Advice (When User is Unsure of Style)

When the user provides a script, synopsis, or concept without locking a specific visual style (or asks "what style fits this show?"), act as an **Executive Production Designer** and provide structured **Design Recommendations** before or alongside the prompts:

1.  **Diagnose along 3 Axes**:
      - **Era & Worldbuilding** (e.g., Tang Dynasty, 2020s Los Angeles, High-Fantasy Xianxia).
      - **Emotional & Narrative Core** (e.g., cold political intrigue, eerie folk-horror, old-money billionaire luxury, warm slice-of-life).
      - **Realism vs. Stylized Spectrum** (Grounded Documentary Realism vs. High-Concept Stylized Art Direction).
2.  **Propose 3 Tailored Visual Directions (Option A / B / C)** using the **Decision Matrix in `references/stylized-and-states.md`**:
      - **Direction A (Grounded Genre Realism / 正统写实派)**: Pull from Realist Styles 01–12.
      - **Direction B (High-Concept Stylized / 风格化视觉锤派)**: Pull from Stylized Directions 13–18 (e.g., *Oriental Folk-Horror*, *Villeneuve Monolithic Brutalism*, *Dunhuang Mineral-Pigment*, *Del Toro Crimson Gothic*, *Wes Anderson Symmetry*, or *Theatrical Stagecraft*).
      - **Direction C (Hybrid Signature Blend / 跨界融合独创派)**: Blend 70% realist base with 30% stylized geometry, custom mineral/material hooks, or era-contrasting set dressing (e.g., *2020s sleek metropolis exterior* + *preserved 1920s occult hunter interior*).
3.  **Explain the "Why" Briefly**: For each recommended direction, clearly state its **70/20/10 Color Matrix**, **Key Material Signature**, and **Why it hooks the audience** for this specific story.

### Step 2: Zero-Omission Scene Audit & 1:1 Indoor-Outdoor Continuity

1.  **Zero-Omission Scene Audit**:
      - Extract **every single location** from the user's script or request (including exteriors, interiors, storefronts, transitional stairwells, alleys, and rooftops). Never skip or merge distinct locations unless requested.
2.  **Strict 1:1 Indoor-Outdoor Architectural Continuity (CRITICAL)**:
      - When designing paired Exterior and Interior scenes of the same building (e.g., Agency Storefront Exterior <-> Agency Office Interior), lock an identical **Architectural Blueprint**:
          - Match the exact facade bay structure (e.g., centered recessed terrazzo doorway + inward-opening copper-framed frosted glass door with overhead brass bell + flanking display windows with Venetian blinds).
          - Match the central sightline axis (looking through the exterior door glass must reveal the exact same central runner rug, desk orientation, and banker's lamp seen inside; reverse angles from behind the desk looking toward the front door must show the exact same doorway, overhead bell, and flanking windows).

### Step 3: Per-Scene 5D Differentiation Engine & Scene State Control

Never let two scenes in the same project look repetitive:

1.  **Spatial Geometry & Scale Contrast**: Alternate between cavernous vertical height, claustrophobic horizontal compression, expansive negative space (30% sky/clouds/river/rock in grand establishing shots), and multi-level diagonal stairwells/terraces.
2.  **Camera Angle, Focal Length & Functional Shot Grammar**:
      - Vary optical perspective per scene (24mm high-angle aerial, 35mm low-angle puddle-skimming, 50mm central axial POV, 85mm voyeuristic foreground occlusion through railings/blinds, or functional shots from `references/stylized-and-states.md` like 90-degree top-down or macro insert).
3.  **Character Wealth & Functional Imprint**: Tailor set dressing to the occupant's exact status and history (e.g., a 160-year-old wealthy immortal's penthouse must feature billionaire old-money luxury—ebony herringbone & Nero Marquina marble floors, bespoke Italian leather, museum-grade 17th-century paintings, and a custom climate-controlled wine/blood vault—contrasted with a crumpled plastic blood bag).
4.  **Scene-Specific Lighting Signature**: Pull distinct lighting setups from `references/dp-lighting.md` for each room.
5.  **Narrative State Transitions**: When a scene appears multiple times under different plot conditions, apply the **5 Scene State Modifiers** from `references/stylized-and-states.md` (*Normal Lived-in*, *Post-Battle Damaged*, *Decades-Abandoned*, *Blackout Stealth*, or *Supernatural Ritual Active*).

### Step 4: Enforce PBR Material & Dry/Wet Boundary Rules

1.  **PBR 3-Layer Formula**: Pull from `references/pbr-materials.md` using `[Base Material & Craft] + [Patina/Wear/Imperfections] + [Light/Moisture Response]`.
2.  **Strict Indoor/Outdoor Moisture Boundary (CRITICAL)**:
      - **Exteriors in rain/mist**: Use wet specular sheen, rain puddles, waterlogged mud, moss, and rain-streaked glass.
      - **Interiors**: **Always specify 100% DRY indoor surfaces** (`completely dry matte hardwood floor`, `completely dry dusty terrazzo steps`, `dry worn Persian rug`) even during stormy/rainy nights, unless the script explicitly floods the room.
3.  **Anti-Repetition in Grand Establishing Shots**: For mountain/city panoramas, combine **3 distinct building typologies** (vertical spires/towers + horizontal grand halls + lightweight cantilevered pavilions), **asymmetric clustering**, and **30% clean negative space**.

### Step 5: Standardized Single-Code-Block Delivery

Default to **16:9 widescreen** (`--ar 16:9`) unless **9:16 vertical** (`--ar 9:16`) is requested. Place all generated design notes and prompts inside a **single unified code block** for effortless one-click copying.

## The 18-Style Matrix Summary (12 Realist + 6 High-Concept Stylized)

### Part A: 12 Grounded Realist Styles (写实影视调色锁 01–12)

  - **Style 01 | Ink-Cyan & Slate (东方水墨青灰·冷峻权谋风)**: `muted ink-cyan and deep slate-grey color grading, low saturation, high contrast chiaroscuro shadows, weathered grey brick and aged nanmu wood patina textures, 10% warm amber candlelight accent, shot on Arri Alexa LF with Cooke Anamorphic lenses, authentic 35mm film grain, classical Chinese realist cinema aesthetic, no people --ar 16:9 --style raw`
  - **Style 02 | Imperial Vermilion & Burnished Gold (盛世流金重彩·皇家华贵风)**: `rich imperial vermilion and dark burnished gold color palette, sumptuous cinematic lighting, glossy lacquered wood patina and intricate silk brocade micro-textures, volumetric god rays piercing through subtle incense smoke, shot on Arri Alexa 65 with Panavision Primo 70 lenses, 35mm film grain, opulent Oriental historical epic aesthetic, no people --ar 16:9 --style raw`
  - **Style 03 | Poetic Song Celadon & Cream (宋明极简雅宋·微暖治愈风)**: `warm and airy Song Dynasty painting color palette, soft rice-paper cream, tea-brown and celadon cyan tones, gentle diffused natural daylight casting dappled leaf shadows, authentic raw wood, woven bamboo, celadon glaze and linen textures, soft highlight roll-off, shot on Sony Venice with Leica Summilux-C lenses, subtle film grain, poetic Oriental realist aesthetic, no people --ar 16:9 --style raw`
  - **Style 04 | Gritty Frontier Ochre (大漠苍凉黄沙·粗粝边塞风)**: `gritty ochre, weathered sandstone and burnt sienna color grading, wind-eroded rammed earth and sun-cracked timber textures, dry dust particles suspended in the air, low-angle golden hour backlight casting long dramatic shadows, high contrast coarse 35mm film grain, shot on Arriflex 435 with vintage anamorphic lenses, Kodak 2383 print film look, no people --ar 16:9 --style raw`
  - **Style 05 | 1930s Shanghai Slate-Green Noir (海派冷绿暗调·民国谍战风)**: `sophisticated 1930s Shanghai noir color palette of muted slate-green and deep charcoal, razor-sharp chiaroscuro lighting and geometric framing, damp exterior brick, distressed leather, oxidized brass and velvet micro-textures, warm amber tungsten wall lamp diffusing in mist, shot on Arri Alexa Mini LF, 35mm film grain, period neo-noir cinema aesthetic, no people --ar 16:9 --style raw`
  - **Style 06 | Humid Monsoon Moss-Green (南方潮湿青苔·现实犯罪悬疑风)**: `humid monsoon moss-green and peeling concrete-grey color palette, hyper-realistic lived-in decay textures including water-stained plaster, chipped paint, and rusted iron grilles, harsh sickly cyan-white fluorescent tube lighting mixed with distant crimson neon, shot on Arri Alexa Mini, Kodak Vision3 500T 35mm film stock, gritty Asian crime thriller aesthetic, no people --ar 16:9 --style raw`
  - **Style 07 | Sleek Corporate Navy & Champagne (高定冷冽流光·现代都市商战风)**: `sleek modern luxury corporate aesthetic, deep navy blue and architectural slate-grey palette, authentic Calacatta marble veins, brushed bronze, floor-to-ceiling glass reflections and supple leather textures, warm champagne cove lighting contrasting with cool city skyline bokeh outside, shot on RED V-Raptor 8K VV with Zeiss Supreme Prime lenses, crisp cinematic photorealism, no people --ar 16:9 --style raw`
  - **Style 08 | Nostalgic 1980s Warm Amber (年代暖金怀旧·市井烟火风)**: `nostalgic 1980s warm amber and terracotta brick color grading, accents of weathered turquoise-blue painted wooden window frames, golden afternoon sunlight filtering through sycamore leaves, authentic vintage enamelware, dry terrazzo floors and lived-in courtyard textures, soft warm halation on highlights, Fujifilm Eterna 35mm film stock look, no people --ar 16:9 --style raw`
  - **Style 09 | Cold Slate-Blue Neo-Noir (暗黑冷蓝死黑·美式超自然/悬疑风)**: `cold slate-blue and desaturated cyan-grey color grading, high contrast with crushed black shadows, aged 19th-century oak patina and oxidized metal micro-textures, dramatic single-source chiaroscuro lighting, shot on Arri Alexa 65 with Panavision Primo 70 lenses, 35mm film grain, dark American thriller drama aesthetic, no people --ar 16:9 --style raw`
  - **Style 10 | Victorian Gaslamp Chiaroscuro (维多利亚油画暗金·英伦古典推理风)**: `19th-century Victorian gaslamp noir palette, soot-black and fog-grey contrasting with rich mahogany wainscoting, tufted Chesterfield brown leather and polished brass patina, warm amber gaslight and fireplace glow cutting through cold blue-grey shadows, Rembrandt lighting, shot on Arri Alexa LF, 35mm film grain, gothic period drama aesthetic, no people --ar 16:9 --style raw`
  - **Style 11 | Bleak Medieval Iron & Basalt (寒铁凛冬粗粝·欧洲中世纪史诗风)**: `bleak and gritty medieval historical epic palette, desaturated iron-grey, mud-brown and freezing winter blue, rough-hewn basalt stone walls, battle-scarred ancient oak, rusted iron and tallow torch soot textures, overcast natural skylight clashing with flickering orange hearth fire, shot on Arri Alexa 65, coarse 35mm film grain, uncompromising historical realism, no people --ar 16:9 --style raw`
  - **Style 12 | Brutalist Rain & Holographic Neon (高反差赛博霓虹·近未来科幻写实风)**: `grounded photorealistic neo-noir sci-fi aesthetic, monolithic brutalist concrete and dark asphalt base textures, vibrant cyan and amber-orange holographic neon Physically Based Rendering (PBR) reflections on brushed titanium surfaces, shot on Arri Alexa LF with anamorphic lenses producing subtle horizontal blue lens flares, 35mm film grain, no people --ar 16:9 --style raw`

### Part B: 6 High-Concept Stylized Art Directions (高概念风格化美术锁 13–18, full prompts in `references/stylized-and-states.md`)

  - **Stylized 13 | Oriental Folk-Horror & Eerie Mythos (东方志怪与中式新怪谈风)**
  - **Stylized 14 | Monolithic Brutalist Minimalism (维伦纽瓦式“极简巨物主义”风)**
  - **Stylized 15 | Art Nouveau & Crimson Gothic Surrealism (新艺术运动与哥特超现实风)**
  - **Stylized 16 | Dunhuang Mineral-Pigment & Gold-Leaf Fantasy (东方重彩岩彩与敦煌壁画风)**
  - **Stylized 17 | Hyper-Symmetrical Pastel & Vintage Pop (强迫症对称与复古撞色美学风)**
  - **Stylized 18 | Theatrical Stagecraft & Poetic Negative Space (舞台戏剧光影与留白写意风)**

## Gotchas & Guardrails

  - **Zero Context Contamination**: Never reference or bind scenes to previously discussed scripts, characters, or uploaded files from earlier turns unless the user explicitly asks to work on that project in the current prompt.
  - **Dry Interiors by Default**: Always explicitly mark indoor floors as `completely dry matte...` when exterior weather is rainy.