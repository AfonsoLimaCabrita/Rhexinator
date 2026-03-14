# Rhexinator — 3D-Printed Capsulorhexis Training Simulator

**Rhexinator** is a 3D-printed training model for practicing **continuous curvilinear capsulorhexis (CCC)** mechanics and cataract-style instrument ergonomics using a replaceable **film “capsule”**. The model is designed to provide realistic approach constraints (face/orbit/temporal and superior approach), a repeatable anterior-chamber working space, and **wound-based pivoting** via corneal incisions.

> **License:** CC0-1.0 (public domain dedication)  
> **Intended use:** training/education only (not a medical device)

---

## This project represents a collaborative work by:

- **Ophthalmology department, Unidade Local de Saude Santa Maria**
- **Faculdade de Medicina da Universidade de Lisboa**
- **Ophthalmology department, Unidade Local de Saude Sao Jose**
- **Universidade de Coimbra Faculdade de Medicina**
- **Universidade Nova de Lisboa Medical School**
- **Mass. Eye and Ear**

---

## What’s in this repository

Current printable parts (STL):

- `Face v5.stl` — upper half of the face/orbit housing  
- `Eye support v3.stl` — socket adapter / support that seats in the orbit and clamps the film  
- `Eye v10.stl` — eye module with iris + cornea + corneal incisions  
- `Stick v2.stl` — plunger/stick used to set eye height within the face (exposure/working depth)

---

## Bill of materials

- 3D-printed parts only (no screws required)
- **Consumable film sheet** (capsule surrogate), placed between the support and the eye module

### Film material (capsule surrogate)
Use a **thin, cellofane, flexible craft film sheet** (pre-cut square sheets). It is typically smooth/glossy, compliant under tension, and will generally **propagate a tear from a starter nick**, making it suitable for repeated CCC tear-control practice when clamped evenly.

**Handling tips**
- Aim for **uniform circumferential tension** (no slack/wrinkles over the working zone).
- If initiation is difficult: create a starter nick with a cystotome.

---

## Recommended print materials

- **TPU 95A:**  
  - `Eye v9.stl`  
  - `Eye support v3.stl`

- **PLA:**  
  - `Face v5.stl`  
  - `Plunger v2.stl`

All parts are designed for **friction-fit assembly** (no hardware).

### Baseline print settings (starting points)
These are generic starting points—tune to your printer/material.

### PLA (Face, Stick)
- Layer height: **0.20 mm**
- Perimeters/walls: **2**
- Infill: **15–25%**
- Supports: **None**

### TPU 95A (Eye, Eye support)
- Print speed: **Slow** (TPU-appropriate)
- Layer height: **0.20 mm**
- Surface pattern: **Circular** (all surfaces)
- Perimeters/walls: **4** (for durable edges)
- Retraction: **1.5 mm**
- Supports: **None**
---

## Assembly

### 1) Seat the support in the orbit
- Press `Eye support v3.stl` into the socket area of `Face v5.stl`.

### 2) Place the film (critical)
- Cut a small section of the square sheet of film and lay it **flat over the support**, centered.

### 3) Install the eye module (clamps the film)
- Press `Eye v9.stl` into the support so the film is **captured and tensioned** between:
  - **Support (below)** and **Eye module (above)**

Check that the film is taut across the working zone with minimal wrinkling.

### 4) Set eye height
- Use `Stick v2.stl` (plunger) to adjust the **height of the eye within the face**, tuning exposure/working depth.

---

## How to use (technique notes)

### Corneal incisions
The **rectangular incisions in the cornea** are meant to be used ports:
- Insert cystotome or capsulorhexis forceps through the rectangular ports into the anterior chamber.
- Use the incision edge as a **fulcrum** to pivot the instrument for controlled intra-chamber motion.
- This encourages “operate about the incision” mechanics rather than free-hand motion.

### Suggested practice workflow
1. Load a fresh film sheet.
2. Create a starter flap (needle/cystotome technique).
3. Complete CCC with forceps:
   - maintain smooth tear propagation
   - maintain centration
   - aim for consistent diameter and circularity
4. Replace the film and repeat.

---

## Troubleshooting

**Film wrinkles / inconsistent tension**
- Re-seat the film, ensure it is centered before pressing the eye in.
- Clean the clamping surfaces (dust reduces grip and uniform tension).

**Friction-fit too tight**
- Lightly sand mating surfaces or reduce XY expansion in slicer.
- TPU parts can “grab” PLA; small tolerance tweaks help.

**Friction-fit too loose**
- Increase perimeters or slightly increase extrusion multiplier.
- Consider printing TPU parts at slightly higher flow for a snugger fit (printer-dependent).

---

## Disclaimer

This project is provided **as-is** for training and educational purposes only.  
Not intended for diagnosis, treatment, patient use, or as a regulated medical device.

---

## Citation

If you use this in a presentation or educational work:

> Lima-Cabrita A. *Rhexinator: 3D-Printed Capsulorhexis Training Simulator*. GitHub repository.

---

## License

CC0-1.0 — see `LICENSE`.
