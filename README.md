# DRUM.NET
### Social Computing Before ARPANET

> *"Privileging the ARPANET-becomes-Internet history has caused us to overlook other forms of networked sociability."*
> — Joy Lisi Rankin, *A People's History of Computing in the United States*, 2018

---

**[→ Live Demo](https://your-username.github.io/drum-net)**

---

## What is this?

An interactive, glitchy, artsy web artifact for **Week 7: Social Computing** in Computation, Culture & Society (University of Chicago, 2026).

It maps **six social computing networks** from across human history — only one of which is ARPANET. Each network gets its own aesthetic, its own data, and its own pre-baked McLuhan quote that asks: what would his media theory have looked like if he'd centered the djembe instead of Gutenberg?

No API keys. No login. No server. Just one HTML file that runs anywhere.

---

## The Six Networks

| Network | Region | Era |
|---|---|---|
| 🥁 Yoruba Talking Drum Network | West Africa | ~800 CE – present |
| 🪢 Andean Quipu + Chasqui | South America | ~1400–1532 CE |
| 📯 Abbasid Barid Postal System | Middle East / Central Asia | 750–1258 CE |
| 🌊 Polynesian Wayfinding Network | Pacific Ocean | ~800–1300 CE |
| 📦 El Paquete Semanal | Cuba | ~2008 CE – present |
| 💾 ARPANET | United States | 1969–1990 CE |

---

## The Argument

McLuhan wrote in 1967 that electric media were creating a new "global village." Licklider and Taylor wrote in 1968 that computers would let geographically separated people form communities for the first time. Both were brilliant. Both were also writing as if the Yoruba drum relay network, Andean khipu, Abbasid Barid, and Polynesian navigation networks didn't exist.

This artifact asks: **what does "social computing" look like when you don't start the clock in 1969?**

It is not an argument that ARPANET wasn't revolutionary. It is an argument that it wasn't first, and that the history we inherited is a history told by people who looked like Licklider, from institutions that looked like DARPA.

---

## Features

- 🎛 **Six interactive network cards** — click any to expand a full-screen panel
- 🔤 **Native script fragments** throughout (`البريد`, `Àgídìgbo`, `Hōkūleʻa`, `Khipu`)
- 📺 **Per-network visualizations** — drum waves, quipu strings, Islamic star geometry, star constellations, static noise, ARPANET node pings
- ⌨️ **Typewriter McLuhan quotes** — pre-generated, baked in, no API required
- 📊 **Log-scale timeline** showing years of operation before ARPANET's first message
- 👾 **Glitch aesthetic** — chromatic aberration on the title, scanlines, random flash lines, scrolling background text in multiple scripts

---

## Readings Engaged

- Marshall McLuhan, *The Medium is the Massage* (1967)
- J.C.R. Licklider & Robert W. Taylor, "The Computer as a Communication Device" (1968)
- Fred Turner, "Where the Counterculture Met the New Economy" (2005)
- Joy Lisi Rankin, "PLATO's Republic (or, the Other ARPANET)" (2018)
- Ted Nelson, *Computer Lib / Dream Machines* (1974)

---

## How to Deploy (GitHub Pages)

1. Fork or clone this repo
2. Make sure `index.html` (rename from `drum_net.html`) is in the root
3. Go to **Settings → Pages → Source: main branch / root**
4. Your live URL will be `https://your-username.github.io/repo-name`

Everything runs client-side. No build step. No dependencies. No backend.

---

## Technical Notes

- Single `index.html` file (~850 lines)
- Pure HTML + CSS + vanilla JavaScript
- Google Fonts: VT323, Special Elite, Caveat, Libre Baskerville, Cinzel, Press Start 2P
- All visualizations are inline SVG generated at runtime
- McLuhan quotes are hardcoded strings — no API calls, no rate limits, no keys
- Tested in Chrome, Firefox, Safari

---

*Made with Claude (vibe coded) · CCS 26 · Week 7 · University of Chicago*
