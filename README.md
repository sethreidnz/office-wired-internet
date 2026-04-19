# Ethernet in office planning

## Diagrams

### Property Layout Top View

![Property Layout Top View](images/diagrams/property-layout-top-view.svg)

**Key dimensions (all to-scale, 1px = 1cm):**

- Office: 382cm × 500cm (outside)
- Garage: 265cm × 500cm (outside)
- Wall space: 21cm × 500cm
- Grass: 690cm × 1145cm
- House: 1093cm × 1210cm
- Paths: 80cm wide
- Soffit overhang: 40cm
- Dirt bed: 40cm (around house, outside soffit)

### Ethernet Path Top View

![Ethernet Path Top View](images/diagrams/ethernet-path-top-view.svg)

**Cable route segments:**

- House inside (bare cable): ~65cm up through wall into ceiling + ~560cm across roof space (to soffit hole)
- House downpipe (conduit): 272cm down alongside downpipe
- House ground to path (conduit, buried 30cm deep): ~105cm
- Under path (conduit, buried below path base): ~80cm
- Alongside driveway edge (conduit, buried 30cm deep): ~615cm
- **Pull box** at corner where driveway meets horizontal path (weatherproof junction box, buried)
- Alongside horizontal path edge (conduit, buried 30cm deep): ~590cm
- Office front (conduit, P-clipped to wall/pipes): 377cm (200+155+22)
- Office wall space (bare cable): 270cm down inside wall
- Office inside (bare cable in trunking): 163cm ceiling to pattress box
- **Total: ~3,097cm (~31m) + slack**

**Bends in the run (5 total):**

1. House downpipe base → into ground towards path (sweep bend)
2. Underground turn → parallel with horizontal path (sweep bend)
3. Turn towards office along driveway edge (sweep bend) — **pull box here**
4. Driveway edge → up office wall (sweep bend)
5. Top of office wall → towards overhang (standard 90° bend)

Conduit ends at the overhang wood — cable passes through into the wall space bare. **Pull box** at bend 3 splits the run into two segments (2 bends + 3 bends). Use cable-pulling lubricant at each segment.

### House Inside Layout

![House Inside Layout](images/diagrams/house-inside-layout.svg)

**Key dimensions (fibre box wall profile):**

- Wall width shown: 202cm (bottom-right corner of house to fibre box)
- Floor to ceiling height: 245cm
- Fibre box: 17cm wide × 13cm high, 180cm from ceiling to top
- Cable wall entry point: aligned with fibre box, 10cm away

### House Inside Ethernet Path

![House Inside Ethernet Path](images/diagrams/house-inside-ethernet-path.svg)

**Conduit route:**

- Cable comes through ceiling from soffit/wall space, drops down to new ethernet port 10cm to the right of the fibre box

#### Photos — House Inside

![House inside fibrebox location](images/photos/house-inside-fibrebox-location.jpg)

### House Downpipe Profile

![House Downpipe Profile](images/diagrams/house-downpipe-profile.svg)

**Key dimensions:**

- Wall height (ground to soffit): 272cm
- Downpipe to corner of house: 16cm
- Downpipe width: 8cm

### House Downpipe Ethernet Path

![House Downpipe Ethernet Path](images/diagrams/house-downpipe-ethernet-path.svg)

**Conduit route:**

- Comes out of soffit, runs down the right side of the downpipe (in the 16cm gap), then along the wall at ground level

#### Photos — House Downpipe

![House soffit exit point](images/photos/house-soffit-exit-point.jpg)

![House downpipe bottom](images/photos/house-downpipe-bottom.jpg)

![House downpipe profile](images/photos/house-downpipe-profile.jpg)

### Office Front Layout

![Office Front Layout](images/diagrams/office-front-layout.svg)

**Key dimensions (working right to left from office corner):**

- Office blockwork: 265cm wide, 245cm high at corner
- Door space: 105cm wide, 255cm high
- Wall space: 21cm wide
- Garage: 265cm wide
- Water drainage pipe: at 200cm height
- HP pipe: 73cm from right corner
- Heat pump: 63cm from right corner, 78cm wide

### Office Front Ethernet Path

![Office Front Ethernet Path](images/diagrams/office-front-ethernet-path.svg)

**Conduit route segments (right to left):**

- Up office corner to water pipe: 200cm
- Along water pipe: 155cm
- Up downpipe into overhang: 22cm
- Into wall space
- **Total front run: 377cm**

#### Photos — Office Front

![Office front](images/photos/office-front.jpg)

![Office heatpump behind](images/photos/office-heatpump-behind.jpg)

![Office heatpump pipe front detail](images/photos/office-heatpump-pipe-front-detail.jpg)

![Office pipeline side profile](images/photos/office-pipeline-side-profile.jpg)

![Office water pipe connection to roofspace](images/photos/office-water-pipe-connection-to-roofspace.jpg)

![Wallspace above office door](images/photos/wallspace-above-office-door.jpg)

### Office Inside Layout

![Office Inside Layout](images/diagrams/office-inside-layout.svg)

**Key dimensions (wall space wall profile, door on left):**

- Wall shown: ~460cm wide, 215cm floor to ceiling
- Door to plug 1: 255cm
- Plug 1 to plug 2: 67cm
- Plug 2 to corner (going right): 70cm
- Vertical trunking up: 67cm
- Ceiling to power back box: 25cm
- All boxes: 12cm wide
- New ethernet box: 10cm left of plug 1

### Office Inside Ethernet Path

![Office Inside Ethernet Path](images/diagrams/office-inside-ethernet-path.svg)

**Conduit route:**

- Cable comes through ceiling from wall space, drops 163cm straight down to new ethernet pattress box (10cm left of plug 1)

#### Photos — Office Inside

![Office inside ethernet location](images/photos/office-inside-ethernet-location.jpg)

## To Purchase

### House Inside

| Item | Qty | Store | Price | Link |
|------|-----|-------|-------|------|
| Double-Gang Vertical Wall Plate (Keystone) | 1 | Jaycar | ~$8 | [Wallplates section](https://www.jaycar.co.nz/cables-connectors/wallplates-and-keystone/c/1E) |
| Mounting C-Clip/Bracket (plasterboard) | 1 | Bunnings | ~$3.32 | [Deta Plaster Clip](https://www.bunnings.co.nz/deta-plaster-clip-mounting-bracket-single-pack_p0310775) |
| Cat6A Shielded Keystone Jacks | 2 | PB Tech | ~$10 ea | [FP-C6AUGS-06](https://www.pbtech.co.nz/product/SCBDNX1013/Dynamix-FP-C6AUGS-06-Cat6A-Shielded-Keystone-Sliml) |
| Cat6 Patch Leads 1m | 2 | Jaycar | ~$5 ea | [YN8502](https://www.jaycar.co.nz/cat6-patch-cable-1meter-blue/p/YN8502) |

> **Grounding note:** The outdoor cable is U/FTP (foil-shielded). Use shielded keystone jacks at the house end — the jack's metal body automatically contacts the cable's foil shield when terminated. Bond the metal wall plate to the building's electrical earth by running a short earth wire (green/yellow) from the wall plate screw to the nearest earth point (e.g. earth pin on the adjacent power socket). Ground at the house end only — leave the office end unshielded to avoid ground loops. If it's working at gigabit speed with no dropouts, the grounding is correct.

### Outside Run

| Item | Qty | Store | Price | Link |
|------|-----|-------|-------|------|
| Cat6 Outdoor-Rated Cable 50m | 1 | PB Tech | ~$143 | [OPL-UFTP6-50](https://www.pbtech.co.nz/product/CABOPL1012/Cat6-Ethernet-Cable---50m-UFTP---Outdoor---Shielde) |
| Weatherproof Pull Box (junction box with lid) | 1 | Mitre 10 | ~$10 | Search in-store — IP55+ rated, 20mm knockouts |
| 20mm Rigid Conduit (4m lengths) | 10 | Mitre 10 | ~$14.68 ea | [Marley 20mm x 4m](https://www.mitre10.co.nz/shop/marley-arma-rigid-conduit-pipe-20mm-x-4m-grey/p/333734) |
| 20mm Conduit Couplers/Joiners | 10 | Mitre 10 | ~$1 ea | [Marley Coupling](https://www.mitre10.co.nz/shop/marley-conduit-plain-coupling-20mm-grey/p/103097) |
| 20mm 90-degree Conduit Bends | 3 | Mitre 10 | ~$3.36 ea | [Marley 90° Bend](https://www.mitre10.co.nz/shop/marley-conduit-90-degree-plain-bend-20mm-grey/p/103094) |
| 20mm Conduit Sweep Bends | 6 | Mitre 10 | ~$6.28 ea | [Marley Sweep Bend](https://www.mitre10.co.nz/shop/marley-conduit-90-degree-sweep-bend-20mm-grey/p/103200) |
| 20mm Stainless Steel P-Clips | 10 | TBC | ~$2 ea | Not found at Mitre 10/Bunnings — try in-store or [RS Online](https://nz.rs-online.com/web/c/fasteners-fixings/clips-springs/p-clips/) |
| Conduit Glue (PVC Cement) | 1 | Mitre 10 | ~$12 | [ADOS PVC Cement 125ml](https://www.mitre10.co.nz/shop/ados-pvc-pipe-cement-clear-pvc-adhesive-125ml-clear/p/370313) |
| Silicone Sealant (clear) | 1 | Mitre 10 | ~$11 | [Gorilla Silicone 300ml](https://www.mitre10.co.nz/shop/gorilla-plumbers-silicone-sealant-300ml-clear/p/104833) |
| 20mm Conduit Bushes/Grommets | 10 | TBC | ~$1 ea | Not found online — ask in-store at Mitre 10 or try [NZ Fasteners](https://nzfasteners.co.nz/collections/grommets-ee) |

### Office Inside

| Item | Qty | Store | Price | Link |
|------|-----|-------|-------|------|
| Double Keystone Surface Box (horizontal) | 1 | Jaycar | ~$5 | [YN8024](https://www.jaycar.co.nz/double-keystone-surface-box/p/YN8024) |
| Toolless Cat6 Keystone Jacks | 2 | Jaycar | ~$8 ea | [YN8029](https://www.jaycar.co.nz/rj45-socket-cat6-keystone-jack/p/YN8029) |
| Mini Trunking 25x16mm (3m, cut to 2m) | 1 | Mitre 10 | ~$8 | [Marley Mini Trunking](https://www.mitre10.co.nz/shop/marley-mini-trunking-3m-25x16mm-white/p/103197) |
| 5-Port Gigabit Switch | 1 | Jaycar | ~$48 | [YN8395](https://www.jaycar.co.nz) (search YN8395) |
| Cat6 Patch Leads 1m | 3 | Jaycar | ~$5 ea | [YN8502](https://www.jaycar.co.nz/cat6-patch-cable-1meter-blue/p/YN8502) |

### Tools

| Item | Qty | Store | Price | Link |
|------|-----|-------|-------|------|
| Drywall/Jab Saw | 1 | Bunnings | ~$6 | [Craftright 150mm](https://www.bunnings.co.nz/craftright-jab-saw-150mm_p5710163) |
| 25mm Spade Bit | 1 | Mitre 10 | ~$5.45 | [Spade Bits section](https://www.mitre10.co.nz/shop/tools-equipment/power-tool-accessories/drilling/drilling/flat-spade-bits/c/RC27910) |
| Fish Tape 30m | 1 | Jaycar | ~$50 | [TH2355](https://www.jaycar.co.nz) (search TH2355) |
| Hacksaw | 1 | Mitre 10 | ~$15 | Search in-store |
| Cable Clips 6-8mm (pack) | 1 | Mitre 10 | ~$5 | [HPM Cable Clips](https://www.mitre10.co.nz/shop/hpm-cable-clips/p/388902) |
| Duct Tape | 1 | Mitre 10 | ~$8 | Available in-store |
| Safety Glasses | 1 | Mitre 10 | ~$5 | Available in-store |
| Wall Filler (Polyfilla) | 1 | Mitre 10 | ~$8 | Available in-store |
| Wire Coat Hanger | 1 | Home | Free | Check your wardrobe |
| Cable-Pulling Lubricant | 1 | Mitre 10 | ~$15 | Search in-store — water-based cable lube |

### Items to find in-store (no online link found)

- **20mm Stainless Steel P-Clips** — try Mitre 10 or Bunnings in-store, or [RS Online NZ](https://nz.rs-online.com/web/c/fasteners-fixings/clips-springs/p-clips/)
- **20mm Conduit Bushes/Grommets** — ask at Mitre 10 electrical section, or [NZ Fasteners](https://nzfasteners.co.nz/collections/grommets-ee)
- **Weatherproof Pull Box** — IP55+ rated with 20mm knockouts, check Mitre 10 electrical section

### Estimated Total: ~$550-600

## Raw Measurements Reference

- House
  - Path along side — 500cm
  - Path to kitchen window — 450cm
  - Kitchen window to Browne box — 110cm
  - Ground to soffit — 272cm
  - From downpipe to path — 105cm
  - Downpipe to corner — 16cm
  - Downpipe width — 8cm
  - Soffit overhang — 40cm
  - Dirt bed depth — 80cm
- Path
  - Width — 80cm
  - Depth (into ground) — 10cm
- Grass
  - Along house — 690cm
  - To office — 645cm
- Office (outside)
  - Width (corner to wall space) — 382cm
  - Garage width (wall space to corner) — 265cm
  - Wall space width — 21cm
  - Height at corner — 245cm
  - Height above door — 255cm
  - Door space width — 105cm
  - Blockwork (corner to door space) — 265cm
  - Water drainage pipe height — 200cm
  - HP pipe from corner — 73cm
  - Heat pump from corner — 63cm
  - Heat pump width — 78cm
  - Overhang past door space — 15cm
  - Up to water pipes — 205cm
  - Up pipe to above door — 30cm
- Office (inside)
  - Wall space depth into room — 270cm
  - Width — 365cm
  - Depth — 500cm
  - Wall thickness — ~25cm
  - Floor to ceiling — 215cm
  - Ceiling to top of power box — 25cm
  - Ceiling to top of ethernet port box — 163cm
- House (inside)
  - Floor to ceiling — 245cm
  - Corner to fibre box — 202cm
  - Fibre box width — 17cm
  - Fibre box height — 13cm
  - Ceiling to top of fibre box — 180cm
  - Fibre box to wall entry point — 10cm
  - Heat pump: 70cm from left edge of fibre box, 78cm wide, 30cm tall, 20cm from ceiling

---

## Diagram Technical Reference

These shape dimension tables are used for maintaining the to-scale SVG diagrams (1px = 1cm).

### Bird's-Eye View Shapes

| Shape | Width | Depth | Notes |
|-------|-------|-------|-------|
| Office | 382cm | 500cm | Outside measurement |
| Garage | 265cm | 500cm | Outside measurement |
| Wall Space | 21cm | 500cm | Between garage and office |
| Driveway | 265cm | 645cm | Same width as garage |
| Dirt (below office) | 382cm | 60cm | Estimated |
| Horizontal Path | 690cm | 80cm | Same width as grass |
| Vertical Path | 80cm | 1935cm | 645cm above + 80cm horiz path + 1210cm house side |
| Grass | 690cm | 1145cm | 645cm gap + 500cm office depth, extends alongside office |
| House | 1093cm | 1210cm | Width: office(382)+wall(21)+grass(690). Depth: path(500)+window(450)+fibrebox(110)+end(150) |
| Soffit | 40cm | 40cm | Overhang around house |
| Dirt (around house) | 40cm | 1210cm | Dirt bed around house, outside soffit |

### Office Front Elevation Shapes

Working right to left from office corner. Diagram ends at garage door left edge.

| Shape | X from right | Width | Height | Notes |
|-------|-------------|-------|--------|-------|
| Office blockwork | 0 | 265cm | 245cm | Corner to door space edge |
| Heat pump | 1cm | 78cm | 55cm | On ground against wall |
| HP Pipe | 80cm | 8cm | 205cm | From ground up to water pipe |
| HP Pipe box | 78cm | 16cm | 14cm | Junction at top of pipe |
| Water drainage pipe | 80cm | 302cm | 12cm | HP pipe across to wall space (at 200cm height) |
| Downpipe (vertical) | 252cm | 10cm | 30cm | From water pipe up into roof |
| Door space | 265cm | 105cm | 255cm | Full door opening |
| Overhang hatch | 265cm | 105cm | 55cm | Above door, under roof |
| Wall space | 382cm | 21cm | 245cm | Between office and garage |
| Garage wall | 403cm | 265cm | 245cm | Only showing to door edge |
| Cream soffit | 0 | full | ~50cm | Strip above blockwork |
| Roof/fascia | 0 | full | ~15cm | Slopes up to garage peak |

### House Downpipe Profile Shapes

Front elevation looking at the house wall where the downpipe is. Right side is the corner of the house.

| Shape | X from corner (right) | Width | Height | Notes |
|-------|----------------------|-------|--------|-------|
| Wall (blockwork) | 0 | ~100cm shown | 272cm | House wall face section |
| Fascia/roof edge | 0 | full width | 12cm | Eaves edge above wall |
| Downpipe | 16cm | 8cm | ~268cm | From soffit down to shoe fitting |
| Pipe shoe fitting | ~20cm | 14cm | 8cm | Elbow/bend at pipe base |
| Pipe brackets | on pipe | 12cm | 2.5cm | Clips holding pipe to wall, ~70cm apart |
| Ground/dirt | 0 | full width | visible | Ground level at wall base |
| Corner edge | 0 | — | 272cm | Bold line marking house corner |

---

## Step-by-Step Installation

### Phase 1: House Inside

### Phase 2: House Roof Space

### Phase 3: House Soffit & Downpipe

### Phase 3: House Ground to Path

### Phase 4: Under Path

### Phase 5: Along Horizontal Path to Pull Box

### Phase 6: Pull Box to Driveway Edge

### Phase 7: Driveway Edge to Office Wall

### Phase 8: Up Office Wall & Into Overhang

### Phase 9: Office Wall Space & Inside

### Phase 10: Cable Pull

### Phase 11: Terminate & Test
