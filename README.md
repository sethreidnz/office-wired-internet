# Ethernet in office planning

## Photos

![House soffit exit point](images/photos/house-soffit-exit-point.jpg)

![House downpipe bottom](images/photos/house-downpipe-bottom.jpg)

![House path 1](images/photos/house-path-1.jpg)

![House path 2](images/photos/house-path-2.jpg)

![Office front](images/photos/office-front.jpg)

## Diagram

### Property Layout Top View

![Property Layout Top View](images/diagrams/property-layout-top-view.svg)

### Ethernet Path Top View

![Ethernet Path Top View](images/diagrams/ethernet-path-top-view.svg)

### Office Front Layout

![Office Front Layout](images/diagrams/office-front-layout.svg)

### Office Front Ethernet Path

![Office Front Ethernet Path](images/diagrams/office-front-ethernet-path.svg)

### House Downpipe Profile

![House Downpipe Profile](images/diagrams/house-downpipe-profile.svg)

### House Downpipe Ethernet Path

![House Downpipe Ethernet Path](images/diagrams/house-downpipe-ethernet-path.svg)

## To purchase

- For office:
  - 1x Single-Gang Surface Mount Box (Pattress Box): Make sure the depth matches your wall plate covers.
  - 1x Wall Plate Cover: To screw onto the box.
  - 2x Toolless Cat6 Jack: (If you’re sticking to the "one cable" plan, you only need one here, but having a spare is fine).
  - 3–4m Mini Trunking: (Self-adhesive).
  - 1x 5-Port Gigabit Switch: The "brain" of the office desk.
  - 3x Cat6 Patch Leads: One for Wall-to-Switch, two for your laptop docks.
  - Fish Tape - For feeding the cable in the wall in the garage
- For inside
  - 1x Double RJ45 Wall Plate (Faceplate).
  - 1x Mounting "C-Clip" or Bracket: Since you are putting a plate on a plasterboard wall, you need the little metal bracket that sits behind the wall for the plate to screw into.
  - 2x Toolless Cat6 Jacks: (One for your active line, one to fill the second hole as a spare).
  - 2x Cat6 Patch Leads (1m): One for Fibre-to-Deco, one for Deco-to-Wall.
- For outside (the run)
  - Cat6 Outdoor-Rated Ethernet Cable: (Measure your TBCs and add 5 meters for "oops" room).
  - 20mm Electrical Conduit: (Rigid grey pipe for the wall drop and underground).
  - 20mm Conduit Saddles: (To fix the pipe to the brick/wood).
  - 20mm Conduit Fittings: Sweep Bends
  - 90-degree Bends/Elbows: To go from vertical wall to horizontal ground.
  - Conduit Glue (PVC Cement): To make the joints waterproof.
  - Silicone Sealant: To seal the holes in the soffit and the office wall.
  - 1x 20mm Conduit Junction Box (Surface Mount)
  - Or 1x 20mm Female Adaptor
- Tools:
  - "Spade Bit" or "Hole Saw" (usually 20mm or 25mm)

Things to measure:

1. The total distance from the modem and the path that we are going to take to get the right cat6 size (add 2 meters for the service loop)
2. The distance from the soffit down to the ground of the house
3. The distance from that ground by the house in total that will go all the way through to the office (for the Electrical Conduit)
4. The distance from the ground to the place I'm going to go in in the office
5. The "Through the Wall" Thickness
6. The Soffit Depth
7. The "Obstacle Check" on the Path

Total Cable: (Distance 1 + 2 + 3 + 4) + 5 meters extra for slack and bends.
Total Conduit: (Distance 2 + 3 + 4) + 10% extra for the bits wasted when cutting and fitting.

## Measurements

- house
  - Path along side - 5m
  - Path to kitchen window - 450cm
  - Kitchen window to Browne box - 110cm
  - Down from suffit = 272cm
  - From downpipe to path = 105cm
  - Downpipe to corner of house - 16cm
  - Downpipe width 8cm
  - Soffit 40cm
  - Dirt bed 80cm depth
- Path
  - 80cm width
  - 10cm depth (into ground)
- Grass
  - Along house - 690cm
  - To office - 645cm
- Office outside-
  - From corner to heat pump pipe left side  - 80cm
  - Up to water pipes - 205cm
  - Up pipe to above door space - 30cm
  - From heat pump pipe to office wall space - 310cm
  - Overhang to right of office door space - 15cm
  - Height of above office door 255cm
  - Hight of office at corner 245c
  - Outside office width (corner to wall space) — 382
  - Outside garage width (wall space to other corner) — if different from office 265
  - Total height from ground to the top of the cream soffit/fascia strip (at the office corner)
  - Height from ground to the bottom of the water drainage pipe - 2m
  - Width of the wall space from the outside - 21cm
  - Width of total door space - 105cm
  - Distance from edge of office door space and office corner 265cm
  - Heat pump width 78cm
- Inside office
  - Distance into room in wall space - 270cm
  - Width 365cm
  - Depth 500cm
  - Wall width - approx 25cm

### Diagram Shape Dimensions (for to-scale bird's-eye view)

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

### Front Elevation Shape Dimensions (for to-scale office front view)

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

### House Downpipe Profile Dimensions (for to-scale wall front view)

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
