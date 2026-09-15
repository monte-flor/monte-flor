# Monte Flor

## Site map (for editing content and photos)

A sketch of the entire `index.html`, section by section. Every block of visible text or photo has a code (section number + letter, e.g. `2.C`). To edit something, find its code here and search for the matching visible text in `index.html` — the line numbers given are approximate and meant as a quick reference.

The site is trilingual (English / Dutch / Spanish). Visible text lives in a `translations` object near the bottom of `index.html` (`en: {...}`, `nl: {...}`, `es: {...}`), keyed by `data-i18n="..."` attributes in the HTML. English text is quoted below; the Dutch and Spanish equivalents share the same key.

Photos are listed as "Photo" only, with no scene description — the image itself carries no visible caption unless noted. (The site markup does have hidden `alt`/`aria-label` text describing each photo for screen readers and SEO, but that text is not shown to visitors, so it isn't included here.)

### 0. Header / menu (line 2)
- **0.A – Logo**: "Monte Flor"
- **0.B – Menu links**: About · Stay the night · Come help · The flowers · Journal · Free advice
- **0.C – Language switcher**: 🇬🇧 English · 🇳🇱 Nederlands · 🇪🇸 Español (defaults to English on a visitor's first visit; remembers their choice after that)

### 1. HERO — landing (`#hero`, lines 3–41)
- **1.A – Photo, slide 1** — aerial drone shot of the farm terraces
- **1.B – Photo, slide 2** — aerial drone shot of the farm and hills
- **1.C – Photo, slide 3** — aerial drone shot of the flower terraces
- **1.D – Photo, slide 4** — aerial drone shot at golden hour
- **1.E – Main title**: "Monte Flor"
- **1.F – Subtitle**: "Flowers grown in harmony with the elements. Pure nature, nourished with organic fertilizers and our own pure spring water."
- **1.G – Buttons**: "Stay the night" · "Come help" · "Pick your flowers"

### 2. ABOUT (`#about`, lines 42–45)
- **2.A – Photo** — family portrait (no visible caption)
- **2.B – Caption box on the photo**: "Family on Camino" / "@family.on.camino"
- **2.C – Section label**: "The Story"
- **2.D – Title**: "Welcome to Monte Flor Galicia!"
- **2.E – Paragraph 1**: how the family left the busy Dutch Randstad and found their place in the Ribeira Sacra mountains
- **2.F – Paragraph 2**: on choosing a slower life, connection, and sustainability
- **2.G – Stats**: "100% Organic" · "40+ Flower Varieties" · "10,000+ m² Terraced Land"

### 3. STAY THE NIGHT (`#stay`, lines 46–49)
- **3.A – Label + title + subtitle**: "Slow Lodging" / "Stay the Night" / "Campervan Refuge & Tent Pitches"
- **3.B – Intro paragraph**: on the secluded terrace pitches for campervans and tent travelers
- **3.C – "Own Campervan Pitch" tab**:
  - Title: "Self-Contained Pitch on the Terraces"
  - Paragraph: on parking amidst terraced cutting flower beds
  - Price: "€3 / night"
  - Price caption: on supporting farm biodiversity and spring water filtration
  - Button: "Reserve Pitch" (links to park4night.com)
- **3.D – "Vintage Camper" tab**:
  - Title: "The Vintage Camper Refuge"
  - Paragraph: on the restored vintage camper beneath the chestnut trees
  - Price: "€55 / night"
  - Price caption: on linens, towels, spring water, and a seasonal bouquet
  - Button: "Book Van" (links to `#advice`)
- **3.E – Four amenity cards**:
  - "3 Pitches" — "Choose your view: the flower garden, the vegetable garden, or the valley."
  - "Spring Water" — "Fresh untreated natural spring drinking water on tap"
  - "No Toilet or Shower" (label "Facilities") — "No compost toilets or shower here."
  - "Great Signal" (label "No Wifi") — "The perfect place to connect with nature, but with great reception if you want to stay connected."
- **3.F – Three photos, each with a visible caption**:
  - Photo 1 — caption: "The farm entrance, framed by stone terraces"
  - Photo 2 — caption: "The camper, beside the flower garden"
  - Photo 3 — caption: "Room for more campervans"
- **3.G – Closing button**: "Check Availability" (links to park4night.com)

### 4. COME HELP (`#help`, lines 50–53)
- **4.A – Label + title + intro paragraph**: "Volunteering" / "Come Help" / intro about living and working alongside Mitchell and Maya on the farm
- **4.B – Card 1** (icon `pets`): "1. Animal Care" — daily help with the chickens and sheep, the dogs and cats, and Melinda the mare; two cows coming soon
- **4.C – Card 2** (icon `yard`): "2. Vegetable Garden" — the vegetable garden is up and running, and volunteer ideas are welcome
- **4.D – Card 3** (icon `forest`): "3. Woodland" — clearing the farm's woodland and starting a small forest and garden
- **4.E – Card 4** (icon `handyman`): "4. House & Family Life" — small maintenance jobs, DIY projects, household tasks, and family meals
- **4.F – Closing button**: "I want to help" (links to Workaway)

### 5. THE FLOWERS (`#flowers`, line 55)
- **5.A – Title + intro paragraph**: "Our Signature Flowers" / on organic cultivation on granite hillside terraces
- **5.B – Photo collage**: 4 photos of flower bouquets in a 2×2 / 4-across grid, no captions yet

### 6. THE PROCESS & JOURNAL (`#process`, lines 56–127)
- **6.A – Label + title + intro paragraph**: "Logbook" / "The Process & Journal" / on the seasonal rhythm of the farm
- **6.B – Entry 1** (active/colored, icon `spa`): Photo — "September 2026" — "Preparing the Ground" — Mitchell used the excavator to turn over the earth for the new flower garden
- **6.C – Entry 2** (active/colored, icon `filter_vintage`): Photo — "September 2026 to March 2027" — "Wait 6 Months" — the soil needs six months to rest so its microorganisms can develop before the first ranunculus roots go in
- **6.D – Entry 3, greyed out** (icon `sunny`): Photo — "Spring" — "Planting" — planting the first ranunculus and dahlia roots into the prepared beds
- **6.E – Entry 4, greyed out** (icon `local_florist`): Photo — no date yet — "Pick Your Flowers" — text is a placeholder ("Coming soon"), still needs its final description
- **6.F – Social strip**: "Follow our daily farm journal and morning harvests" + Instagram, YouTube, and TikTok icons (icons have no visible label, and their `href="#"` links are still empty and need to be filled in)

### 7. FREE ADVICE (`#advice`, lines 128–131)
- **7.A – Photo** (no visible caption) — **still a stock photo, needs to be replaced**
- **7.B – Title**: "Have a Question About Growing Flowers?"
- **7.C – Paragraph**: "Write to me and I'll gladly help. Knowledge should be shared. Send me a voice note or a message and I'll happily get back to you."
- **7.D – WhatsApp button**: "Send Maya a Message💐" (links to `https://wa.me/34744794047`)

### 8. FOOTER (line 131 onward)
- **8.A – Logo + description**: "Monte Flor" / "Galician Flower Farm" / on the organic cut-flower micro-farm in Ribeira Sacra
- **8.B – Location**: "Ribeira Sacra, Ourense" / "Galicia, Spain"
- **8.C – Contact**: email `seed@monteflorgalicia.com` + links to Instagram · YouTube · TikTok (all live, pointing at `monteflorgalicia` accounts)
- **8.D – Bottom bar**: "Grown with rain, Atlantic sun, and zero pesticides. Handmade in Galicia." / "© 2026 Monte Flor. All rights reserved."

### Known placeholders (sample data still to replace)
- The photo in **7.A** (Free advice section) is still a stock/generated image and needs to be replaced with a real photo.
- The description for **6.E** (Entry 4, "Pick Your Flowers") is a placeholder ("Coming soon") and needs its final text once the harvest details are confirmed.
- The social media icon links in **6.F** point to `#` (empty) and still need real URLs.
- The photo collage in **5.B** has no captions yet.

### Style notes
- Site copy avoids the dash character (`-`/`—`) as punctuation; use periods, commas, or separate sentences instead. Hyphens inside legitimate compound words (e.g. "off-grid") are fine.
- Keep English, Dutch, and Spanish in sync — when one language's text changes, update the same key in the other two `translations` blocks too.
