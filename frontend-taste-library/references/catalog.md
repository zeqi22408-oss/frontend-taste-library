# Frontend reference catalog

## User preference rules

- An attractive reference is not automatically approved.
- Borrow principles that fit the current product; never reproduce a site wholesale.
- Favor clear hierarchy, responsive usability, accessibility, and performance over decorative complexity.

## Observed references

### Photography institution official sites

- Status: observed
- Inspected: 2026-08-17
- Context: sampled at the user's request to reduce the artificial, image-generation-heavy feel of 摄影信息雷达网 reference comps. These references are observed, not yet approved as the user's taste.

#### World Press Photo

- Source: https://www.worldpressphoto.org/
- Purpose: documentary photography institution presenting the annual contest, exhibitions, education, and support programs.
- Reusable patterns: one documentary photograph owns nearly the entire first viewport; the logo and one action sit directly on the image; the menu is compact; copy is brief and factual; red is reserved for identity and action rather than spread across components.
- Typography and structure: upright sans-serif utility type, modest headline scale, large uninterrupted image area, minimal interface chrome.
- Guardrails: keep consent UI from obscuring the work; mobile behavior was not fully verified in the current browser session.

#### Magnum Photos

- Source: https://www.magnumphotos.com/
- Purpose: photography cooperative and magazine presenting stories, photographers, learning, licensing, and prints.
- Reusable patterns: quiet white navigation with thin rules; a single naturally proportioned photograph leads; generous margins and minimal overlay preserve the author's image; categories remain plain text rather than decorative chips.
- Typography and structure: restrained serif-led editorial character supported by simple utility navigation; the photograph, not the interface, carries the emotion.
- Guardrails: keep cookie controls compact and verify mobile navigation separately; the mobile viewport could not be reliably sampled in this session.

#### LensCulture

- Source: https://www.lensculture.com/
- Purpose: contemporary photography magazine and opportunity platform combining editorial content, awards, learning, and submissions.
- Reusable patterns: deadline and submission action remain explicit; navigation is straightforward; one campaign visual establishes the page before editorial content begins; opportunity messaging is direct rather than hidden in a dashboard.
- Typography and structure: conventional sans-serif navigation, campaign-specific hero type, clear orange action accent, editorial content beginning immediately below the hero.
- Guardrails: the observed mobile page had horizontal overflow and an oversized campaign banner; preserve the direct opportunity/action model but not that responsive defect or purple campaign styling.

### Awwwards sample study

- Status: observed
- Inspected: 2026-08-17
- Source: https://www.awwwards.com/
- Context: inspiration portal sampled at the user's request; individual examples below are not yet confirmed as personal preferences.

#### The Watch

- Source: https://www.awwwards.com/sites/the-watch
- Purpose: luxury product experience centered on a real-time 3D watch.
- Reusable patterns: restrained black and gray palette, oversized type, generous whitespace, product interaction as narrative.
- Guardrails: motion should not obscure content; the observed Awwwards accessibility and responsive scores trailed its animation score.

#### SSTR - Friction Reduction

- Source: https://www.awwwards.com/sites/sstr-friction-reduction
- Purpose: industrial B2B presentation for friction reduction in oil drilling.
- Reusable patterns: editorial minimalism, modular grid, orange and charcoal palette, large typography, motion tied to hardware and engineering content.
- Good fit: industrial technology, manufacturing, engineering, and corporate storytelling.

#### HAOQI.DESIGN

- Source: https://www.awwwards.com/sites/haoqi-design
- Purpose: product designer and design-engineer portfolio.
- Reusable patterns: assertive typography, vivid media field, gallery structure, controlled WebGL and scroll interactions.
- Guardrails: retain semantic structure, readable content, reduced-motion behavior, and mobile performance.

## Approved references

### Lando Norris

- Status: approved
- Inspected: 2026-08-17
- Source: https://landonorris.com/
- Purpose: athlete and personal-brand site combining Formula 1 performance, lifestyle, merchandise, partners, and social content.
- Visual system: acid lime `#D2FF00`, dark green `#282C20`, off-white `#F4F4ED`, and charcoal `#111112`; Mona Sans Variable for forceful utility type, paired with Brier display serif for editorial contrast.
- Reusable patterns: full-bleed portrait hero with layered technical graphics; oversized all-caps statements with selected serif words; sparse editorial photo collage with small provenance captions; split “on track / off track” navigation; collectible product grids; a single high-energy accent color reused for calls to action and drawn marks.
- Interaction and responsive behavior: branded preloader, smooth scroll and canvas-based reveals, compact fixed mobile actions, full-screen mobile menu, stacked editorial compositions, and a two-column collectible grid on narrow screens.
- Good fit: athlete, entertainment, personal brand, premium lifestyle, campaign, and culture-led product sites.
- Guardrails: preserve semantic reading order and readable copy beneath spectacle; provide reduced-motion behavior; optimize canvas and image loading; add meaningful image alternatives. The inspected page used many canvas layers and many images without alternative text, so those implementation details are not part of the approved taste.

### Haitian Laser Machinery

- Status: approved
- Inspected: 2026-08-17
- Source: https://haitianlaser.com/
- Purpose: industrial B2B manufacturer site presenting a broad equipment portfolio, application solutions, company capability, service, and news.
- Visual system: white and ice-gray surfaces, deep industrial blue, restrained black text, pale atmospheric backgrounds, rounded media cards, and clean Chinese sans-serif typography.
- Reusable patterns: dark real-production hero followed by a bright isometric “complete industrial ecosystem” scene; product hotspots placed directly on equipment; horizontal application cards organized by customer industry; trust-building capability metrics and partner marks; clear progression from equipment to solutions, company proof, and current activity.
- Interaction and responsive behavior: fixed navigation, product mega-menu, horizontal product and industry carousels, interactive scene hotspots, compact mobile header, and nested accordion navigation for a deep product taxonomy.
- Good fit: industrial equipment, advanced manufacturing, automation, energy, engineering, and multi-product B2B corporate sites.
- Guardrails: keep the product taxonomy searchable and semantic, use one meaningful page heading, add image alternatives and reduced-motion support, and ensure mobile hero copy stays inside the viewport. During inspection the desktop intro mask did not dismiss automatically in one run, the mobile hero showed text-cropping risk, and the numerical count-up was unusually slow; do not reproduce those behaviors.

### Getty - Tracing Art

- Status: approved
- Inspected: 2026-08-17
- Source: https://www.getty.edu/tracingart/
- Purpose: an interactive editorial story explaining how the Getty Provenance Index traces the ownership, movement, and social context of artworks across centuries.
- Visual system: museum-white, warm stone, pale blue, and artwork-led dark scenes; Graphik sans-serif for interface and factual labels, paired with Bardford serif for narrative authority; restrained fixed Getty branding and compact black controls.
- Reusable patterns: turn chronology into a continuous scrollytelling spine; keep one artwork as the focal object while related works fade around it; combine large editorial statements with small source captions; alternate gallery-white space, full-bleed artwork, and quiet color-field chapters; use oversized names and dates as spatial landmarks; transform large datasets into clustered artwork-thumbnail constellations rather than conventional charts.
- Interaction and responsive behavior: very long scroll choreography, fixed brand and information controls, a compact vertical progress indicator, year markers, progressive image scaling and repositioning, contextual information drawer, and artwork exploration prompts. Mobile reflows the narrative into a clean single column, preserves the timeline and visualization, and adds a direct “tap an artwork” instruction without horizontal overflow.
- Good fit: museums, archives, cultural institutions, research storytelling, historical timelines, documentary features, data journalism, and premium long-form editorial experiences.
- Guardrails: reserve this degree of scroll choreography for focused stories rather than task-oriented or conversion-heavy pages; provide chapter navigation, a skip path, reduced-motion and non-canvas fallbacks, lazy media loading, and complete keyboard and screen-reader names. The inspected page was roughly 90,000 pixels tall on desktop, used canvas, exposed several unnamed controls and images in the accessibility tree, and had no detected reduced-motion rules; those implementation weaknesses are not part of the approved taste.

### Terminal Industries

- Status: approved
- Inspected: 2026-08-17
- Source: https://terminal-industries.com/
- Purpose: an enterprise B2B site positioning an AI-native Yard Operating System for logistics visibility, automation, security, and orchestration.
- Visual system: deep green `#052424`, acid lime `#ABFF02`, dirty white `#F0F0F0`, restrained gray, and occasional warm freight imagery; SuisseIntl for large direct messaging, paired with Geist Mono for numbered stages, interface labels, and operational detail.
- Reusable patterns: open with a cinematic physical-to-digital transformation from a real freight yard to a wireframe truck and data field; keep a compact floating navigation bar with persistent product and demo actions; establish trust through a large customer-logo grid; segment buying paths by current operational scale; place an ROI calculator directly inside the narrative; reveal benefits with scroll-progress text highlighting; map a modular platform to concrete operating zones such as gate, yard, dock, and network; follow product explanation with a full-bleed customer quotation and a high-intent contact section.
- Interaction and responsive behavior: scroll-scrubbed 3D and video sequence, context-adaptive fixed navigation, live calculator inputs and results, horizontal application carousel with zone tabs, nested mega-menu, and FAQ categories. Mobile preserves the cinematic sequence, converts trust marks to a two-column grid, stacks the buying-path cards and calculator, and uses a two-level side drawer with phone, product, demo, and contact actions anchored at the bottom.
- Good fit: logistics, industrial SaaS, computer vision, enterprise AI, operations software, automation platforms, and other complex B2B products that need both technical credibility and measurable commercial value.
- Guardrails: expose the value proposition and a usable CTA without waiting for the cinematic sequence; provide a static fallback, compressed media, and reduced-motion behavior; make calculator assumptions transparent; avoid letting the sticky navigation obscure section headings; add meaningful alternatives to decorative and informative imagery and remove unnamed interactive elements. The inspected page used canvas and multiple videos and had many images without alternative text, although it did include reduced-motion CSS and most major controls had accessible names.

### Bennett & Clive

- Status: approved
- Inspected: 2026-08-17
- Source: https://bennettandclive.com/
- Purpose: a brand-forward portfolio for a global creative production company serving fashion, beauty, entertainment, brands, agencies, photographers, and directors.
- Visual system: almost entirely black and white with occasional signal red; a heavy InterWeb grotesk used at extreme scale; names, navigation, and operational details share one direct typographic voice so the identity itself becomes the interface.
- Reusable patterns: devote the opening viewport to a single oversized wordmark; run a continuous full-bleed motion reel while client names remain arranged as a fixed typographic constellation; anchor the composition with small left, center, and right brand markers; transition from dense moving imagery to radical white space; split a short manifesto across opposite sides of the viewport; overlay two opposing service lists on a single media field; present the client roster as a loose name cloud rather than a conventional logo grid; finish with city clocks, direct contact details, and a wordmark that again fills the page edge.
- Interaction and responsive behavior: scroll-driven video changes, fixed desktop navigation, client-name links layered over motion, a full-screen blurred contact overlay, and an active service/media composition. Mobile reframes video vertically, compresses client names into a central stack, rebuilds the manifesto as an asymmetric split composition, stacks the client roster, and replaces the desktop navigation with a black full-screen menu containing oversized links, world clocks, contact details, and legal links.
- Good fit: fashion, beauty, luxury, entertainment, creative production, photography, film, art direction, design studios, and other portfolio sites where a small amount of copy must communicate strong taste and cultural confidence.
- Guardrails: use this density of overlap only when imagery and names are the primary content; protect text from edge clipping, allow for longer localized labels, keep the company proposition available outside the showreel, and provide video poster frames, compressed media, reduced-motion behavior, and pause controls. The inspected page used eight videos and had no detected reduced-motion rules; its major navigation controls were named accessibly, but some visual images remained unnamed in the accessibility tree.

### Couro Azul

- Status: approved
- Inspected: 2026-08-17
- Source: https://www.couroazul.com/
- Purpose: an immersive corporate and product site for a premium leather manufacturer serving automotive, railway, and aircraft interiors while communicating craft, technology, quality, and family legacy.
- Visual system: near-black, stone white `#F1EEE9`, warm leather brown `#A68676`, muted copper, gray, and deep green material imagery; restrained Gill Sans utility typography paired with Miller Display serif and italic faces for heritage, quotations, and editorial warmth.
- Reusable patterns: let extreme close-ups of material texture and manufacturing process occupy the entire viewport; keep navigation thin and quiet over cinematic imagery; move visually from raw hides and workshop machinery to finished transport interiors; organize market segments as three equal columns whose inactive options recede while hover changes the active background and emphasis; pair industrial proof with founder stories, dates, and personal quotations; use separate quality, care, and process chapters to make a material product feel both emotional and technically credible.
- Interaction and responsive behavior: single-viewport custom wheel choreography, cinematic video transitions, sound on/off control with a small waveform, page-level transitions, market hover states, language switch, and persistent scroll cue. Mobile separates market copy from the supporting image, keeps the identity compact, and uses a warm-brown full-screen menu with a simple vertical information architecture and segmented language control.
- Good fit: premium materials, automotive suppliers, transport interiors, industrial heritage, leather and textile manufacturers, craft-led engineering, luxury components, and other B2B brands whose material quality must be felt before it is explained.
- Guardrails: provide native scrolling, touch, keyboard, chapter navigation, and non-video fallbacks alongside any single-viewport choreography; keep the main thread responsive; ensure inactive states remain readable; label sound, navigation, and other icon-only controls; add meaningful image alternatives; move third-party award badges away from mobile content; include pause and reduced-motion behavior. The inspected implementation used canvas and video, exposed several unnamed controls and images, omitted alternative text on most images, and had no detected reduced-motion rules.


## Rejected references

Keep private or local rejected references in your own catalog. The public template intentionally omits local paths and private feedback.
