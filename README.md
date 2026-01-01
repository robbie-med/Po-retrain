# PO Reconditioning Plan

A lightweight, client-side web tool for **gradual re-training of oral intake (PO)** after prolonged underuse (e.g., PEG-J dependence, dysmotility, post-illness deconditioning).  
Designed to behave like *physical therapy for eating*: slow, repeatable, low-threat exposure with clear guardrails.

Live entirely in the browser — **no backend, no accounts, no data leaving the device**.

---

## What this is

- A **stage-based ladder** (Stage 0 → Stage 4) for rebuilding volume tolerance
- A **daily checklist** to reinforce habit consistency
- **Auto-saved notes** for symptom tracking and pattern recognition
- Optimized for **iPad / mobile Safari** use at the bedside or home

This is **physiology-first**, not psych labeling:
- Gastric accommodation
- Motility
- Reflux mechanics
- Learned threat signaling after prolonged non-use

---

## What this is not

- ❌ Not a calorie counter  
- ❌ Not a replacement for clinician judgment  
- ❌ Not a forced-exposure or “push through nausea” model  
- ❌ Not cloud-based (intentionally)

---

## Features

### Stage selector (persistent)
- Stage 0–4 selectable via pill buttons
- Selection is saved in `localStorage`
- Active stage is visually highlighted

### Daily plan checklist
- Mini-sessions
- Upright positioning
- Venting use
- Symptom documentation
- One-tap **“New day”** reset
- Full **reset all** option

### Notes
- Free-text notes with suggested structure
- Auto-save on keystroke
- Copy to clipboard
- Clear notes
- (Optional export can be added if desired)

### Navigation
- Smooth scrolling between sections
- Mobile-friendly tap targets
- No JavaScript frameworks

---

## Data & Privacy

- All data is stored **locally in the browser** using `localStorage`
- Clearing browser data clears everything
- No analytics
- No cookies
- No network calls

This is intentional.

---

## Tech stack

- Plain HTML + CSS + vanilla JavaScript
- No build step
- No dependencies
- Works offline after first load

---

## File structure

```text
/
├── index.html        # Main application
├── README.md         # This file
