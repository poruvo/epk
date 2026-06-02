---

description: Load these instructions for any task involving the gon pulvo EPK, booking page, artist press kit, one-sheet, SoundCloud archive, WeeklyBeats archive, live performance page, or booking-related content.
applyTo: '**/*.{html,css,js,json,md}'
-------------------------------------

# gon pulvo EPK Instructions

## Purpose

This project is the booking-facing EPK for gon pulvo, the experimental electronic project of Stephon X. Jones.

The EPK must help promoters, venues, galleries, DIY organizers, electronic music curators, and event bookers quickly understand:

* What gon pulvo is
* What kind of show or bill the act fits
* What the live set sounds like
* What the live set looks like
* Set length options
* Technical needs
* Booking and contact details
* Where to hear curated work
* Where to browse the broader WeeklyBeats and SoundCloud archive

The site should preserve the dark, strange, experimental, bass-heavy, horror-narrative identity of gon pulvo, but booking clarity comes first.

## Core Principle

Build the decision path first.

A promoter should understand the act in under 10 seconds.

Do not make the user decode the whole artist universe before they can find booking information.

The EPK should feel like:

"This is a serious, easy-to-book live act."

Not:

"Here is a whole artist universe you need to decode first."

## Artist Positioning

gon pulvo is a dark experimental electronic live act blending distorted rhythm, horror atmosphere, jungle / hip-hop movement, bass music, and narrative sound design.

Best-fit contexts:

* Experimental electronic
* Dark electronic
* Noise-adjacent bills
* Industrial / horror-themed bills
* Gallery and art-space performances
* DIY mixed bills
* Electronic support slots
* Multimedia / audio-reactive visual performances

## Required Page Structure

Use this page order:

1. Hero / Booking Summary
2. Watch / Listen / Live Proof
3. Booking Details
4. Short Bio
5. Booking-Relevant Audio
6. WeeklyBeats Quarterly Archive
7. Featured Projects
8. Press / Assets
9. About Stephon
10. Social Links
11. Contact

## Above the Fold

The first screen must include:

* Artist name: gon pulvo
* Short artist description
* Best-fit show types
* Set length options
* Basic technical needs
* Booking CTA
* Watch / Listen CTA

Primary CTA:

Book gon pulvo

Secondary CTA:

Watch / Listen

## Hero Copy

Use or adapt this copy:

gon pulvo is a dark experimental electronic live act blending distorted rhythm, horror atmosphere, jungle / hip-hop movement, bass music, and narrative sound design.

Available for 20-45 minute live electronic sets, support slots, experimental bills, gallery performances, DIY events, and dark electronic/noise-adjacent lineups.

Simple setup: table, power, and stereo DI or mixer input. Optional audio-reactive visuals available with advance coordination.

## Booking Details

Create a clear booking details section or card.

Set lengths:

* 20 minutes
* 30 minutes
* 45 minutes
* Extended sets available by request

Technical needs:

* Table or stable performance surface
* Power outlet
* Stereo DI or mixer input
* Venue PA connection
* Optional projection / HDMI support for visuals

Performance format:

Live electronic performance using hardware tracker, sampler, wind controller / digital sax, live FX, and optional audio-reactive visuals.

Avoid casual or uncertain booking language such as:

* prolly
* maybe
* extreme set
* unclear inside jokes
* project lore that does not help a booker make a decision

Use:

Extended sets available by request.

Do not use:

Extreme set length: 2-4 hours.

## Watch / Listen / Live Proof

Place this near the top of the page.

This section should prove that the live set works.

Include space for:

* 90-second live clip
* 10-15 minute live excerpt
* Curated booking-relevant audio
* Boogeyman project link

If final video assets are not ready, use clean placeholders:

* Live Clip - Coming Soon
* 10-Minute Live Excerpt - Coming Soon

Do not overload this section with every link.

Recommended CTA labels:

* Watch Live Clip
* Hear Recorded Work
* Boogeyman Project
* Bandcamp

## Booking-Relevant Audio

Because the WeeklyBeats archive contains multiple genres, create a separate curated section above the archive.

Suggested title:

Start Here: Booking-Relevant Audio

Purpose:

Give promoters the clearest starting point before they explore the broader archive.

This section may include:

* A curated SoundCloud playlist
* 3-5 selected tracks
* A Bandcamp link
* A YouTube/live clip link
* Boogeyman link if relevant

Suggested copy:

These selections are the clearest starting points for promoters and event organizers. The quarterly playlists below show the wider WeeklyBeats archive and genre range.

## WeeklyBeats and SoundCloud

Canonical WeeklyBeats profile:

https://weeklybeats.com/gonpulvo

Canonical SoundCloud profile:

http://soundcloud.com/poruvo

WeeklyBeats is the primary weekly release context.

SoundCloud is where the artist organizes WeeklyBeats entries into quarterly playlists and broader listening archives.

The EPK should represent this clearly:

* WeeklyBeats = ongoing weekly release practice
* SoundCloud = quarterly playlist archive and broader listening platform

Create a section called:

WeeklyBeats Quarterly Archive

Suggested subtitle:

Weekly releases on WeeklyBeats, organized into quarterly SoundCloud playlists.

Purpose:

Show consistency, creative range, and ongoing output.

Do not make WeeklyBeats or SoundCloud the main booking path.

The EPK should still prioritize:

1. Live proof
2. Booking-relevant audio
3. Set length
4. Technical needs
5. Contact

WeeklyBeats and SoundCloud should support the booking case by showing consistency, range, and active output.

Suggested copy:

gon pulvo releases regularly through WeeklyBeats, using the platform as a public creative log for weekly experiments, sketches, rhythm studies, genre explorations, and narrative fragments.

Those entries are also organized into quarterly SoundCloud playlists, making it easier to browse the work by season and creative period.

For booking, start with the curated audio and live proof above. The WeeklyBeats and SoundCloud archive shows the broader creative range and ongoing output.

Each quarterly card should support:

* Quarter
* Year
* Playlist title
* Date range
* Short description
* Genre notes
* SoundCloud playlist URL
* WeeklyBeats profile URL
* Optional featured tracks
* Optional SoundCloud embed

Preferred data file:

data/weeklybeats-playlists.json

Use one embedded SoundCloud playlist at a time. Older quarters should be cards with links.

Do not embed every playlist at once.

CTA button labels may include:

* View WeeklyBeats
* Follow on WeeklyBeats
* Open WeeklyBeats Archive
* Listen on SoundCloud
* View Quarterly Playlists

## Required JSON File

Create or update:

data/weeklybeats-playlists.json

Use this structure:

[
{
"quarter": "Q1",
"year": "2026",
"title": "WeeklyBeats 2026 Q1",
"dateRange": "January - March 2026",
"description": "Weekly releases and experiments from the first quarter of 2026.",
"genreNotes": [
"multi-genre",
"experimental electronic",
"ambient",
"jungle",
"hip-hop",
"sound design"
],
"weeklybeatsProfileUrl": "https://weeklybeats.com/gonpulvo",
"soundcloudPlaylistUrl": "",
"embedUrl": "",
"isCurrent": false,
"isFeatured": true,
"highlightTracks": [
{
"title": "",
"note": "",
"weeklybeatsUrl": "",
"soundcloudUrl": ""
}
]
}
]

## Bio

Use a short booker-facing bio first.

Suggested copy:

gon pulvo is the experimental electronic project of Stephon X. Jones, blending distorted rhythm, bass-heavy textures, horror atmosphere, and surreal narrative structure. His work crosses hip hop, house, ambient, jungle, and experimental bass while using recurring motifs, dreamlike tension, and reactive visuals to shape immersive live sets.

Longer bio can go lower on the page or behind an expandable section.

Do not repeat the same bio ideas in multiple places.

## Featured Projects

Keep Boogeyman as a featured project, but make it secondary to booking.

Suggested copy:

Boogeyman is a narrative-driven experimental electronic project exploring fear, identity, recursion, and dream logic. In live settings, the project can be paired with glitch aesthetics and audio-reactive visuals to create a darker immersive performance environment.

Suggested buttons:

* Listen on Bandcamp
* View Project
* Project Website
* Shop

Project lore is allowed, but it should not interrupt the booking flow.

Remove or relocate unclear in-universe text from booking-critical sections unless it is clearly labeled as project lore.

## Press / Assets

Include a section for press or booking assets.

Support:

* Artist photo
* Logo or visual mark
* Short bio
* One-line description
* One-sheet
* Downloadable assets if available

Do not make this section too large.

Suggested CTA labels:

* Download One-Sheet
* Download Press Assets
* Copy Short Bio
* Copy One-Line Description

## One-Sheet / Print Version

If the site includes a printable one-sheet, make it useful for booking.

The one-sheet should fit on one page and include:

* Artist name
* One-line description
* Short bio
* Best-fit bills
* Set lengths
* Technical needs
* Links
* Contact
* Artist photo or logo

Do not include:

* Long project lore
* Long gear lists
* Cybersecurity background
* Every social link
* Dense paragraphs

## About Stephon

If including professional background, place it near the bottom under:

About Stephon

Suggested copy:

Outside of music, Stephon X. Jones works in cybersecurity and compliance consulting. This background informs gon pulvo's interest in systems, recursion, identity, infrastructure, and failure.

This section should not compete with booking information.

## Social Links

Top-priority links:

* Bandcamp
* YouTube
* Instagram
* SoundCloud
* Contact

Full link list can go lower.

Do not dump every social link above the fold.

SoundCloud link:

http://soundcloud.com/poruvo

WeeklyBeats link:

https://weeklybeats.com/gonpulvo

## Contact

Contact must be easy to find.

Include booking CTA near the top and bottom.

Contact section should include:

* Booking email
* Preferred contact method
* Instagram DM if applicable
* Discord if applicable

Suggested copy:

For booking, collaboration, or show inquiries, email is preferred. Please include event date, city, venue, set length, compensation, and technical details if available.

## Design Guidelines

Preserve the existing dark experimental identity.

Prioritize:

* Mobile readability
* Fast loading
* Clear hierarchy
* Scannable sections
* Accessible contrast
* Clear CTA buttons
* Minimal link clutter
* Strong dark experimental visual identity

Avoid:

* Walls of text
* Repeated social link dumps
* Too many SoundCloud embeds
* Hidden contact info
* Abstract copy above the fold
* Overly casual wording in booking-critical sections

## Technical Guidelines

Use simple maintainable HTML, CSS, and JavaScript.

Do not add heavy frameworks unless already present or explicitly approved.

Use semantic HTML where practical:

* header
* main
* section
* nav
* footer
* article
* address

Lazy-load media embeds where possible.

Mobile layout is primary.

Use JSON data files for archive content when practical.

Embedded media should not slow the page down.

Use one featured SoundCloud embed at a time. Do not load multiple SoundCloud iframes on initial page load.

## Accessibility Guidelines

Use readable font sizes.

Use accessible contrast.

Buttons and links should have clear labels.

Images should include useful alt text.

Embedded media should have fallback links.

Do not rely only on color to communicate state or importance.

## Acceptance Criteria

The EPK is successful when:

* A promoter understands gon pulvo in under 10 seconds
* Set lengths are visible near the top
* Technical needs are visible near the top
* Watch / Listen appears near the top
* Booking CTA appears near the top and bottom
* Booking-relevant audio is separate from the broader archive
* WeeklyBeats quarterly playlists are supported without clutter
* WeeklyBeats and SoundCloud canonical links are included
* SoundCloud embeds do not slow down the page
* Boogeyman and project lore are preserved but secondary
* Professional background is lower on the page
* Mobile layout is clean and readable
* Contact is easy to find
* The page feels like a booking tool first and an artist world second

## Final Rule

Do not redesign the identity first.

Redesign the decision path first.

Make the EPK feel like gon pulvo, but make it easy for a promoter to book.
