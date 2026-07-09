# Montjuïc & the Litoral

A one-day motorcycle roadbook for **Sunday 6 September 2026** — 11:30 until dinner, built for a
**125cc**, and it never leaves Barcelona.

Open `index.html` in a browser. No build step, no dependencies.

## The day

| Time | Stop | Why |
|---|---|---|
| 11:30 | El Cullerot de Sants | *Esmorzar de forquilla* — the Catalan fork-and-knife breakfast |
| 13:15 | Avinguda de l'Estadi → Miramar | The surviving bones of the 1969–75 Montjuïc GP circuit |
| 14:00 | Jardins de Mossèn Costa i Llobera + Mirador de l'Alcalde | Cactus garden over the port, free, empty |
| 15:30 | Vallvidrera *(optional — see below)* | The city's own mountain road, up and down the Arrabassada |
| 17:15 | Bar Rovira, El Clot | Vermut, family-run since 1963, no tourists |
| 18:15 | Jon Cake, Poblenou | The cheesecake |
| 19:15 | Barceloneta | Park in a free moto bay, feet on the sand |
| 19:50 | Avinguda del Litoral → Fòrum | The seafront run at golden hour |
| 20:45 | Els Pescadors | Dinner with friends on Plaça de Prim |

~55 km, zero motorway, every stop verified open on a Sunday.

## Design notes

Roadbook aesthetic: asphalt and ember. Syne for display, Chivo for body, Chivo Mono for timings
and road numbers. The timeline rail is a dashed road centre-line; the optional leg is drawn with
a dashed border. Mobile-first — this gets read on a phone at a petrol station. `@media print`
collapses it into something you can fold into a tank bag.

## Verified

- **Sunset 20:16 CEST, azimuth 279° (due west)** — timeanddate + NOAA. Barcelona's beaches face
  roughly ESE, so the sun sets *behind* Collserola, not over the sea. The route rides east into
  the afterglow rather than pretending otherwise.
- **125cc on autovías** — RD 1428/2003 art. 38.1 bars *ciclomotores* (≤50 cc), not motorcycles.
  The Ronda de Dalt and Ronda Litoral are legal on a 125. This route doesn't use them.
- **ZBE** — enforced Mon–Fri 07:00–20:00 only (zbe.barcelona). Sundays are unrestricted.
- **Bus/taxi lanes** — motorcycles banned since 2011. Relevant on Joan de Borbó.
- **Passeig Marítim de la Barceloneta** — pedestrian, both levels. Bogatell and Mar Bella
  promenades likewise. **Avinguda del Litoral** is the only legal seafront road.
- **Carretera de les Aigües** — closed to motor vehicles (Collserola ordinance art. 14).
- **Moto parking** — white-line bays are free and unreserved, ~95,000 citywide (areaverda.cat).
- **Els Pescadors** — Sunday dinner 20:00–00:15, kitchen to 22:15 (own site). 932 25 20 18.

## Call before you go

- **Collserola is closed.** African swine fever, since a Generalitat resolution of 12 March 2026,
  no announced reopening. Paved through-roads are exempt so the Vallvidrera climb should be
  legal, but this is live — check `parcnaturalcollserola.cat/actualitat/avisos/`. The leg is
  marked optional in the roadbook for exactly this reason.
- **Montjuïc's roads** close for stadium events. No standing Sunday closure exists, but the
  official mobility page bot-blocks automated checks — verify the event calendar manually.
- **Jon Cake Poblenou** — 08:00–20:00 daily traces to one press piece from the opening. The
  Santa Caterina branch (Sant Pere Més Baix 36, Sun 10:00–20:00) is corroborated across four
  listings and is the safer fallback.
- **El Cullerot de Sants** — Sunday 09:00–17:00 is consistent across directories but has no
  primary source. Backup: **Ca la Montse**, Barceloneta, confirmed Sun 10:00–16:00 on its own
  site with online booking.
- **Bar Rovira** — confirmed open Sunday; nothing agrees on the closing time.

## Deliberately excluded

- **Bunkers del Carmel** — resident-permit parking on the approach, gated nightly, and a 2026
  council process underway to regulate tourist crowds after serious incidents. Exactly the kind
  of place this roadbook is meant to avoid.
- **Castell de Montjuïc** — the "free on Sunday afternoons" rule doesn't appear in its current
  2026 admissions sheet. Full price, long queue. The gardens below are better and free.
- **Parc del Laberint d'Horta** — free on Sundays, but the maze itself is closed for renovation
  until 2027.
- **Anything outside the city.** The Garraf cliff road, Sitges, the Sakya Tashi Ling monastery
  and Els Pescadors' Costa Brava cousins are all off the table on a 125 day. See git history for
  the earlier out-of-town version.
