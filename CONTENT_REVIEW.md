# Events Portfolio Content Review

## Completed events

The portfolio contains 24 structured records sourced from the supplied resume: PUBG Mobile Campus Championship Season 1; PUBG Mobile India Series Season 1; PUBG Mobile India Tour; PMCO; PMAS; Free Fire India Championship Seasons 1 and 2; Free Fire India Today League 2019; Acer Predator League Seasons 1–3; PVP Esports Championship; World Esports Championship; MTV Ucypher Season 1; FMSCI Championship 2022; MMSC Bike Racing / Rolon Round of the Indian National Motorcycle Racing Championship; IIT Techfest 2016–2019; Taiwan Gaming Excellence 2018–2019; Playtonia Conqueror's Insignia Seasons 1–2; ASUS ROG Offline Qualifiers; GGNation Challenger Series; Campus Showdown; College Esports Championship; Ground Zero LAN; ISRL; ESPL; and an aggregate Broadcast Infrastructure & OTT Operations record.

Duplicate event names were consolidated. Event metrics are shown only when present in the resume. Public sources corroborate event identity but do not expand Ninad Yadav's responsibilities.

## Unresolved logo matches

- `src/assets/events/infinix-world-esports-cup.png`: The asset reads “Infinix World Esports Cup,” while the resume text says “World Esports Championship.” Do not treat these as the same event without confirmation.
- `src/assets/events/asus-rog-masters.png`: The resume text says “ASUS ROG Offline Qualifiers 2016.” Confirm that ROG Masters is the correct event branding.
- `src/assets/events/waves-summit.png`, `src/assets/events/pune-grand-tour.png`, `src/assets/events/india-maritime-week-2025.png`, `src/assets/events/world-economic-forum.png`, `src/assets/events/dreamhack-mumbai-2018.png`, and `src/assets/events/hitwicket-world-championship.png`: Identified visually, but the resume provides no role, date, or assignment narrative. These are mapped but not presented as portfolio participation.
- `src/assets/events/maharashtra-government.png` and `src/assets/events/government-of-india.png`: Organization marks are identifiable, but no supported project relationship is stated in the resume text.

## Missing media

- No third-party event photography was downloaded because reusable rights were not established.
- No specific official YouTube video was embedded because the research did not establish a definitive event video and role match. Official channel links are provided instead.
- PMCO, PVP Esports Championship, IIT Techfest, Taiwan Gaming Excellence, College Esports Championship, ISRL, ESPL, and the infrastructure portfolio use designed text placeholders where no approved resume logo is available.

## Unclear rights

- All displayed event logos are resume-provided and labeled accordingly. Trademark and brand ownership remain with the original rights holders.
- External articles and official websites are link-only.
- Official YouTube channels are link-only until a specific embeddable video is approved.
- Assets marked `useAllowed: false` in `src/data/logoMap.json` remain excluded from participation claims.

## Facts requiring confirmation

- Exact PMCO and PMAS editions, dates, employer, role, and prize pools.
- Exact PVP Esports Championship edition and date.
- Whether “World Esports Championship” is the same event as the Infinix World Esports Cup logo.
- Exact title and participating countries for the FMSCI Championship 2022 assignment.
- The full names and exact dates of ISRL and ESPL.
- Annual role details for IIT Techfest 2016–2019.
- Season dates for Free Fire India Championship Seasons 1 and 2.
- Whether the ROG Masters logo is the correct mark for ASUS ROG Offline Qualifiers 2016.
- The resume phrase “7L+ offline audience” for Ground Zero LAN should be confirmed as 700,000+ and clarified as attendance, reach, or another audience measure.
- Whether WAVES, Pune Grand Tour, India Maritime Week 2025, World Economic Forum, DreamHack Mumbai 2018, Hitwicket World Championship, and government logos represent completed professional assignments.

## External sources used

- Primary source: `Ninad_masterprofile_doc.pdf`, supplied by Ninad Yadav.
- PUBG MOBILE Esports India official YouTube channel: `https://www.youtube.com/@PUBGMOBILEEsportsIndia`
- Free Fire Esports India official YouTube channel: `https://www.youtube.com/@FreeFireEsportsIndiaOfficial`
- Asia Pacific Predator League official website: `https://www.predator-league.com/`
- FMSCI official website: `https://www.fmsci.co.in/`
- Madras Motor Sports Club official website: `https://www.madrasmotorsports.com/`
- IIT Bombay Techfest official website: `https://techfest.org/`
- Taiwan Excellence official website: `https://www.taiwanexcellence.org/`
- India Today article on the 2019 Free Fire India Today League finale: `https://www.indiatoday.in/sports/other-sports/story/free-fire-india-today-league-finale-siri-fort-1598056-2019-09-12`
- Liquipedia tournament overview for PUBG Mobile India Series 2019: `https://liquipedia.net/pubgmobile/PUBG_Mobile_India_Series/2019`
- Sportskeeda announcement for PUBG Mobile India Tour 2019: `https://www.sportskeeda.com/esports/pubg-mobile-india-tour-2019-announced-with-a-prize-pool-of-rs-1-5-crore`
- IMDb series overview for U Cypher: `https://www.imdb.com/title/tt8018490/`

## Validation notes

- JSON schema completeness, unique event IDs, asset existence, and one-to-one logo-map coverage were checked locally.
- JSX parsed successfully using Babel standalone.
- Static routes for the page, data files, sitemap, llms.txt, and a representative logo returned HTTP 200 locally.
- Keyboard focus styles, Escape-to-close, modal focus trapping, reduced-motion support, semantic headings, lazy-loaded logos, alt text, loading, empty, and error states were implemented.
- A project build was not run because the task environment explicitly prohibits local build commands; automated platform validation performs the build.
- No production deployment was performed.
