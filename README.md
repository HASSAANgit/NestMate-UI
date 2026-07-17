# NestMate 🏠
### Rent & Roommate Finder for the Pakistani Market

> A 24-screen high-fidelity mobile app UI — designed end-to-end for the Applied Human-Computer Interaction (AHCI) course at FAST-NUCES CFD Campus.

---

## 📱 Overview

Pakistan's informal rental market has no verification, no roommate matching, and no structured way to agree on living terms. **NestMate** solves all three.

Built over four phases using a rigorous user-centred design process — from market research and SRS through lo-fi wireframes, a full design system, a clickable prototype, and usability testing — NestMate is a trust-first platform for students and landlords navigating the Karachi rental market.

**SUS Score: 75.5 / 100** (above the 68 industry benchmark)  
**Prototype: [Open in Figma →](https://www.figma.com/design/dsPfDEltahyJgfJylvfEAT)**

---

## ✨ Key Features

| Feature | What it does |
|---|---|
| 🪪 CNIC Verification | Identity-checks both tenants and landlords before any contact |
| 🗺️ Map View | Geolocated listings with price pins and transit filters |
| 💬 Lifestyle Profiler | Swipe cards + emoji slider + drag-to-rank — builds compatibility data without a boring form |
| 🔷 Compatibility Dashboard | Hexagonal radar chart across 6 lifestyle dimensions with friction heatmap |
| 📋 Negotiate Living Terms | Clause-based workspace — Rent Split, Quiet Hours, Chores, Guest Policy — with Accept / Counter / Decline |
| 🔒 Privacy Control Centre | Per-field visibility (Public / Private / Connected / Matched) |
| 🏠 Landlord Dashboard | Stats, upcoming viewings, listing management — separate role-based flow |

---

## 🖼️ Screens

The prototype contains **24 screens** across four user flows:

```
Onboarding  →  Splash · Login · OTP · Role Selection · CNIC Verify · Profile Setup
Search      →  Home · Map View · Listing Detail · Book Viewing
Profiler    →  Lifestyle Topic Map · Swipe Cards · Emoji Slider · Drag to Rank
Matching    →  Roommate Discovery · Compatibility Dashboard · Side-by-Side Compare
Chat        →  Messages · Chat Thread · Negotiate Living Terms
Settings    →  Privacy Control Centre · Profile & Settings
Landlord    →  Create Listing · Landlord Dashboard
```

---

## 🎨 Design System

Built using **Atomic Design** methodology — all components have auto-layout and are reused as instances across every screen.

**25 master components · 100 instances across 24 screens**

### Atoms (12)
`Button/Primary` · `Button/Secondary` · `Input/Default` · `Chip/Default` · `Chip/Active` · `Badge/Verified` · `Avatar/XLarge-80` · `Toggle/On` · `Progress Bar` · `Slider` · `Map Marker/Normal` · `Map Marker/Selected`

### Molecules (13)
`Search Bar` · `Form Field` · `Listing Card` · `Roommate Card` · `Message Bubble (Sent · Received)` · `Step Indicator (Active · Inactive)` · `Clause Card` · `OTP Group` · `Bottom Nav Bar` · `Conversation Row` · `Stat Card`

### Colour Palette — Trust Blue

| Token | Hex | Usage |
|---|---|---|
| Blue 500 (Primary) | `#2F7BC7` | CTAs, prices, active states, Verified badge |
| Blue 900 (Text) | `#0A2540` | Headings, primary text |
| Blue 50 (Tint) | `#EFF5FB` | Chip backgrounds, card tints |
| Success 500 | `#12B76A` | Verified badge, agreed clauses |
| Warning 500 | `#F79009` | Countered clauses, friction points |
| Danger 500 | `#F04438` | Disagree, error states |

**Typography:** Inter · Display 32 / H1 24 / H2 20 / Body 16–14 / Caption 12  
**Grid:** 4pt · Border radii: 8 / 12 / 16 / 24

---

## 📊 Usability Testing Results

Five moderated think-aloud sessions with participants matching the primary personas.

| Task | Completion | Target |
|---|---|---|
| TC-01 Onboarding | 80% (4/5) | 80% |
| TC-02 Book Viewing | **100% (5/5)** | 90% |
| TC-03 Lifestyle Profiler | 80% (4/5) | 75% |
| TC-04 Compatibility | **100% (5/5)** | 85% |
| TC-05 Negotiate Terms | 60% (3/5) | 70% |

**Critical issues found: 2** (role-card ambiguity, negotiate-button discoverability) — both fixable with low effort.

---

## 🔬 Research & Process

**Phase 1 — Requirements Engineering**  
Desk research (Zameen.com, OLX, SpareRoom), persona development (Aisha — tenant, Mr. Tariq — landlord), 47 user stories across 6 epics, competitive analysis of 5 platforms, SRS document.

**Phase 2 — Information Architecture & Lo-Fi**  
IA diagram (Mermaid in Figma), 4 user flow diagrams, 24 grayscale wireframes, layout decisions validated before hi-fi investment.

**Phase 3 — Hi-Fi Design & Prototype**  
Full design system, 24 high-fidelity screens, clickable prototype (25+ connections), two flow starting points (Tenant Onboarding / Landlord Flow), zero dead ends.

**Phase 4 — Usability Testing**  
SUS 75.5, 100% completion on booking and matching flows, 2 critical issues identified and documented.

---

## 👥 Team

| Name | Roll No |
|---|---|
| Hassaan Bashir | 23F-0722 |
| Khansa Zumer | 23F-0771 |
| Zainab Attique | 23F-0843 |

**Course:** Applied Human-Computer Interaction (AHCI)  
**Instructor:** Mughees Ismail  
**Institution:** FAST-NUCES, CFD Campus · Spring 2026

---

## 🛠️ Tools Used

- **Figma** — Design system, hi-fi screens, prototype, IA diagrams
- **Inter** — Primary typeface
- **Atomic Design** — Component architecture methodology
- **SUS (System Usability Scale)** — Usability evaluation framework

---

## 📄 Deliverables

- [x] Software Requirements Specification (.docx)
- [x] Information Architecture & 4 User Flow Diagrams (Figma)
- [x] 24 Lo-Fi Wireframes (Figma)
- [x] Design System — 25 components with auto-layout (Figma)
- [x] 24 Hi-Fi Screens (Figma)
- [x] Clickable Prototype — 25+ connections, no dead ends (Figma)
- [x] Usability Testing Report (.docx)
- [x] Final Project Report (.docx)

---

## 🔗 Links

- **Figma Prototype:** https://www.figma.com/design/dsPfDEltahyJgfJylvfEAT
- **Figma Prototype Mode:** https://www.figma.com/proto/dsPfDEltahyJgfJylvfEAT

---

## 📣 LinkedIn Post (Ready to Copy)

If you want to share this project on LinkedIn, you can use this caption:

> Excited to share **NestMate** — a 24-screen high-fidelity mobile app UI designed for the Pakistani rental market as part of our AHCI project at FAST-NUCES.  
>  
> We focused on trust, compatibility, and better living-term negotiation through features like CNIC verification, lifestyle profiling, and a compatibility dashboard.  
>  
> ✅ SUS Score: **75.5/100**  
> 🎨 Designed in Figma with a reusable atomic design system  
> 🔗 Prototype: https://www.figma.com/design/dsPfDEltahyJgfJylvfEAT  
>  
> #UIUX #ProductDesign #Figma #HCI #UXResearch #DesignSystem #StudentProject

---

*This is a UI/UX design project — there is no application code. The repository contains the project report, design documentation, and assets.*
