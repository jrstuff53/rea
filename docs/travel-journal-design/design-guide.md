# Travel journal design guide

26 November 2026 · John Robertson

Live, editable version: https://claude.ai/artifact/KwJqEgMt9XQs8DwQEJrtoK
Colour-scheme preview: [colour-preview.html](colour-preview.html) (also at https://claude.ai/artifact/AhkYae4qr9eK3BBqt9YgAy)

## Summary

Your app should feel light, calm and easy for every member of the family to use, on a phone while travelling and on a laptop at home. It is for you and your family to record trips as they happen, so speed and readability matter more than decoration.

The five rules that matter most:

1. **Photos and the map are the stars.** Keep everything else quiet: light background, plenty of space, one accent colour.
2. **Big and clear beats small and clever.** Entry text at 17 points and nothing under 14, strong contrast, buttons at least 48 pixels tall.
3. **One obvious main action per screen.** On a trip screen that is "Add an entry", in the accent colour, where the thumb reaches.
4. **Same parts everywhere.** Use the same card, button and heading styles on every screen so the app feels like one thing.
5. **Phone first, then widen.** Design the phone screen first; the laptop layout uses the extra width to show the map beside the entries.

No logo is needed. The app's name in a clean font is enough.

## What Polarsteps does well

Polarsteps looks modern because it is disciplined, not because it is busy. These are the ideas worth borrowing, based on its public website and profile pages as seen on 26 November 2026. Its name, logo, fonts and exact colours are its own and should not be copied.

| Idea | What Polarsteps does | How to use it in your app |
| --- | --- | --- |
| Warm, soft background | An off-white, slightly warm page colour instead of pure white | Pick a tinted off-white from one of the schemes below |
| One loud colour | A single bright accent is kept for the main button only | Use your accent only for the one action that matters most |
| Deep, not black, text | Text and headers are a very dark navy rather than black | Use a very dark tinted colour for text; it feels softer |
| Rounded shapes | Fully rounded "pill" buttons and cards with soft corners | Round all buttons fully; give cards corners of about 16 pixels |
| Big, simple headings | Very large bold headings with short words | One short, large heading per screen |
| One font family | One friendly rounded typeface for almost everything | Use one free font (see Text and fonts) |
| Map as centrepiece | The map fills most of the screen; the list sits beside it | Same idea on laptops; on phones the map sits at the top |
| Headline numbers | Countries, days and distance shown as big numbers with small labels | Show 3 trip stats in a row at the top of each trip |
| Friendly empty screens | "No public trips yet" with a short helpful sentence | Every empty screen says what to do next |
| Mixed tiles | Feature boxes in a tidy grid of different sizes and colours | Use for a trip summary screen, sparingly |

## Colours

Each scheme below has five colours plus white, and every pairing has been checked to pass the international readability standard for contrast (WCAG AA, which needs a score of 4.5 or more for normal text). Pick one scheme and use only its colours. The codes starting with # are what you give a designer or developer. The colour-scheme preview page shows each one on a mock phone and laptop screen.

**How to use the colours**

- **Background:** the page colour behind everything.
- **Cards:** pure white (#FFFFFF) panels that sit on the background and hold entries and photos.
- **Text:** headings and main writing.
- **Soft text:** dates, places and small labels.
- **Accent:** the main button and the route line on the map. Use it sparingly.
- **Second colour:** small highlights only, such as a "favourite" mark or a tag.

| Scheme | Feeling | Background | Text | Soft text | Accent | Second colour |
| --- | --- | --- | --- | --- | --- | --- |
| Sea and Sand | Coastal, relaxed | #FBF7F0 | #1B2B34 | #55636B | #0B6E77 teal | #B04A30 coral |
| Alpine Morning | Crisp, fresh | #F4F7FA | #16212E | #4E5B6A | #2557C7 blue | #8F5A00 amber |
| Terracotta Journal | Warm, nostalgic | #FAF4EC | #2A221D | #5E534B | #A8482A terracotta | #4F7356 sage |
| Botanical | Calm, natural | #F5F7F1 | #1D2A21 | #4D5A50 | #2A6B45 green | #9A5B00 mustard |

| Scheme | Text on background | Soft text on background | White on accent button | Accent on background |
| --- | --- | --- | --- | --- |
| Sea and Sand | 13.6 | 5.8 | 6.0 | 5.6 |
| Alpine Morning | 15.1 | 6.4 | 6.4 | 6.0 |
| Terracotta Journal | 14.3 | 6.8 | 5.8 | 5.3 |
| Botanical | 13.8 | 6.7 | 6.4 | 5.9 |

Contrast scores; 4.5 or more passes for normal text, 7 or more is the stricter level.

**Colour rules**

- Never use pure black text on pure white; the tinted pairs above are easier on the eyes.
- Never put light grey text on a light background, however stylish it looks.
- Never show meaning by colour alone; add a word or an icon too (for example a heart plus "Favourite").
- Give each colour a name in the app's settings ("background", "accent" and so on) rather than typing the colour code everywhere. Then swapping schemes, letting family pick their favourite, or adding a dark mode (light text on a dark background) later means changing one short list. Start with light, as you asked.

## Text and fonts

Use one free, modern font for everything, or at most one font for headings and one for text, in two or three weights (thicknesses) only. All three suggestions below are free from Google Fonts and are designed to be easy to read on screens.

| Font | Character | Good with |
| --- | --- | --- |
| Nunito Sans | Soft, rounded and friendly | Sea and Sand, Botanical |
| Inter | Clean and very readable at small sizes | Alpine Morning |
| Outfit (headings) + Inter (body) | Rounded, geometric headings with plain body text | Terracotta Journal |

**Sizes** ("points" in a phone app; if your app is a website, read them as pixels, for example 17px. On a large screen, the screen title can grow to 32 to 40.)

| Use | Size | Weight |
| --- | --- | --- |
| Screen title | 28 | Bold |
| Section heading | 20 | Bold |
| Entry text | 17 | Regular |
| Dates, places, labels | 14 | Medium, in soft text colour |
| Button text | 17 | Bold |

**Text rules**

- Never go below 14 points, and keep entry text at 17 so older eyes can read it.
- Let the phone's own text-size setting make the text bigger; the layout must still work when it does. If your app is a website, this needs to be built in on purpose, so ask whoever builds it to check.
- Lines of entry text should be no wider than about 70 characters on a laptop, so the eye can follow them.
- Leave generous space between lines (about 1.5 times the text size).
- Use sentence case ("Add an entry"), not ALL CAPITALS, which is harder to read.

## Layout on the phone

On a phone, everything you tap often sits in the lower two thirds of the screen, where a thumb reaches without stretching. The preview page shows this layout drawn out.

**A trip screen, from top to bottom**

1. A cover photo with the trip title, dates and the three headline numbers (days, places, kilometres) on a soft dark fade, a back arrow on the left, and a small save status on the right, such as "1 photo will upload later".
2. The map, about one third of the screen tall, showing the route and pins.
3. The first entry, starting on the opening screen so people see straight away that entries are the main content.
4. The entries as cards under day headings ("Day 9 · Sunday 11 May"), newest first: one photo, place and time of day (not the date again), title, first two lines of text, and who wrote it with their initial in a small circle.
5. A fixed bar at the bottom with 3 big icons with words under them: Trips, Globe (the 3D globe of every trip), Family.
6. A large "+ Add an entry" pill button in the accent colour, bottom right, always visible, sitting clear above the bottom bar with words on it, not just an icon.

**Spacing and shapes**

- Leave at least 16 pixels of space at the screen edges and between cards. Space is what makes a screen feel light.
- Every button and tappable thing is at least 48 by 48 pixels, with space between them, so fingers don't hit the wrong one.
- Cards are white with corners rounded about 16 pixels and a very faint shadow, sitting on the tinted background.
- Buttons are fully rounded "pills". The main button is filled with the accent colour; other buttons are outlined.

**Adding an entry should take seconds**

- One tap opens a simple screen: photo first, then a text box, with place and date filled in automatically.
- One big "Save" button at the bottom. Nothing else is required.
- Save a draft automatically, so nothing is lost if the phone loses signal.

## Layout on laptops and computers

On a laptop or desktop, use the extra width to show the entries and the map side by side, the way Polarsteps' web pages do. It is the same app with the same colours, cards and buttons, just arranged wider.

**A trip screen on a laptop**

1. A slim bar across the top: the app's name, Trips and Family (the current one underlined), a search box for trips and entries, and your initial and name on the right. No Map tab is needed because the map is always on screen.
2. A left column about 420 pixels wide: an "All trips › trip name" link to get back, a short cover photo strip, the trip title, the three headline numbers, then the entry cards under day headings, each with two lines of text and who wrote it.
3. The map fills everything to the right and stays still while the list scrolls.
4. Clicking a card opens the full entry in the left column (large photo, full text, more photos, "Back to trip" link) and highlights its pin on the map: larger, filled in the accent colour, with the place name. Every pin shows its place name where there is room. Clicking a pin opens its entry.
5. "Add an entry" sits as a pill button at the top of the left column.

**When the window is in between** (a tablet, or a narrow window)

- Below about 900 pixels wide, put the map on top and the list below. Between about 600 and 900 pixels, show the cards two across so they don't stretch.
- Never let a page scroll sideways.

**Reading a single entry on a laptop**

- Show it in a centred column no wider than about 720 pixels, with the photos larger and the text kept to a comfortable line length.
- Keyboard users must be able to move through everything with the Tab key, and see clearly which item is selected.

## The map

Use a light, muted map style so it matches the light feel of the app and lets your route stand out. Polarsteps' web profile page shows a dark map; a light one suits your brief better. Mapbox, which you plan to use, has a current default style called "Standard" with a light setting, and its colours can be tinted to match your scheme.

- **Route line:** drawn in the accent colour, about 4 pixels thick, with a thin white edge so it shows on any background.
- **Pins:** small white circles with an accent-coloured border; the selected one grows slightly. For a photo entry, the pin can show a tiny round photo.
- **The 3D globe:** use it for the "all my trips" overview, where it looks impressive. For a single trip, a flat zoomed-in map is easier to read.
- **Gentle movement:** when moving between places, let the map glide over about one second rather than jump. If "reduce motion" is on, jump instead.
- **Keep the map uncluttered:** hide extra labels, shops and landmarks you don't need.
- **Not everyone uses a map:** every place shown on the map must also be listed in words, for anyone who finds maps hard.

**On the phone:** show the trip map as a still preview that opens full screen when tapped. A live map in the middle of a scrolling page catches the thumb and stops the page scrolling.

**Costs and setup:** Mapbox's free allowance is very likely enough for a family, but it asks for a payment card. Restrict your Mapbox key to your own website address so nobody else can use it and run up a bill. When there is no signal, show the list of places in words instead of a blank map.

## Photos

Photos are what make a travel journal attractive, so give them room and keep everything around them simple. They are also what stops the app looking like a generic template: give each trip a full-width cover photo at the top of its page.

- **Full width:** on a phone, photos run edge to edge inside their card. On a laptop, a large lead photo with smaller ones in a tidy grid below.
- **Same shape in lists:** in the list of entries, crop every photo to the same shape (4 by 3 works well) so the list looks orderly. Show the full photo when the entry is opened.
- **Rounded corners:** match the cards, 16 pixels.
- **Text on photos:** only with a soft dark fade behind it, dark enough that white text still scores 4.5 for contrast.
- **Speed:** shrink photos before saving, and load them as the person scrolls, so the app stays quick on a weak signal.
- **Descriptions:** let people add a short caption, which also helps anyone using a screen reader (the phone feature that reads the screen aloud).
- **Tap to enlarge:** a tapped photo opens full screen, and swipes to the next one.
- **Never lose the original:** keep a full-size copy of every photo backed up, even though the app shows smaller ones.
- **While photos load:** show a soft grey shape of the same size, so the page doesn't jump as pictures arrive.

## Privacy and travelling offline

A travel journal holds your family's locations and photos, so it should be private by default and keep working without signal.

- **Private by default:** trips are visible only to family members you invite. Sharing more widely is a deliberate choice.
- **Strip hidden location data:** phone photos carry the exact place they were taken. Remove this from uploaded photos; the entry's place name is enough.
- **Protect home:** never pin your home address automatically, and consider showing a place only after you have left it.
- **Works without signal:** entries and photos are kept on the phone and upload later. Show a small, clear status such as "Saved on this phone, will upload later".
- **Fonts travel with the app:** include the font files in the app itself rather than loading them from Google each time, so the app looks right offline.

## Movement and animation

Small, quick movement makes an app feel modern and alive; too much makes it feel slow or makes some people feel unwell. Keep every animation short and purposeful.

- **Short:** most movements take 0.2 to 0.3 seconds. Map glides can take about one second.
- **Purposeful:** use movement to show where something came from (a card opening into the full entry) or that something worked (a soft tick after saving).
- **Gentle start and stop:** things should speed up and slow down gently rather than move at a fixed speed.
- **Respect the "reduce motion" setting:** phones and computers have a setting for people who are sensitive to movement. When it is on, replace movement with a simple fade.
- **Avoid:** bouncing, spinning, auto-playing slideshows, and anything that moves while someone is trying to read.

## Wording on buttons and messages

Words are part of the design. Short, friendly and specific wording makes the app feel polished.

| Instead of | Write |
| --- | --- |
| Submit | Save entry |
| New | Add an entry |
| No data | No entries yet. Tap "Add an entry" to start your trip. |
| Error 500 | That didn't save. Check your signal and try again; your draft is kept. |
| Are you sure? (deleting an entry) | Entry deleted. Undo (keep a "can't be undone" question only for deleting a whole trip) |
| Upload media | Add photos |

- Name buttons with a verb that says what happens.
- Every empty screen says what to do next, the way Polarsteps does on an empty profile.
- Error messages say what went wrong and what to do, in plain words, and never blame the person.

## Accessibility checklist for family members

Because family members of different ages and abilities will use the app, these checks should pass before any screen is called finished. Tick them off as you go.

- [ ] Text contrast is 4.5 or more everywhere (all four schemes already pass)
- [ ] Entry text is 17 points, and nothing is smaller than 14
- [ ] Text grows with the phone's text-size setting without overlapping or being cut off
- [ ] Every button is at least 48 by 48 pixels, and nothing sits under the phone's camera notch or the bar at the bottom edge
- [ ] Every icon has a word with it, or a hidden label a screen reader can speak
- [ ] Every photo can have a short description
- [ ] Nothing relies on colour alone, and outlines of buttons, input boxes and map pins score at least 3 for contrast against what is behind them
- [ ] Everything works with the keyboard on a laptop, and the selected item is clearly outlined
- [ ] Animations calm down when "reduce motion" is switched on
- [ ] Everything on the map is also available as a list in words
- [ ] Tested with the phone's built-in screen reader (VoiceOver on iPhone, TalkBack on Android) at least once

## Do's and don'ts

| Do | Don't |
| --- | --- |
| Use one colour scheme and stick to it | Mix colours from different schemes |
| Keep the accent for the one main action | Make every button bright |
| Leave lots of space around things | Fill every corner of the screen |
| Use one font, or at most two, in two or three weights | Use several fonts or decorative script fonts |
| Make photos large and consistently shaped | Show small, mismatched thumbnails |
| Round buttons and card corners the same way everywhere | Mix sharp and round corners |
| Put the main actions within thumb reach on phones | Put the main button in the top corner |
| Show the map beside the list on laptops | Stretch the phone layout across a wide screen |
| Keep animations short and gentle | Add bouncing or spinning effects |
| Write short, friendly, specific labels | Use technical words or ALL CAPITALS |
| Copy Polarsteps' principles | Copy Polarsteps' name, logo, fonts or exact colours |
