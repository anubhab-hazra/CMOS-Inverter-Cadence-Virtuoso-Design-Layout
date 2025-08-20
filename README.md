# CMOS Inverter — Cadence Virtuoso Design & Layout

Schematic and layout implementation of a CMOS inverter using Cadence Virtuoso. Includes symbol, testbench, transient simulations, parasitic-extracted layout (PEX), clean DRC/LVS, and a timing comparison between schematic and layout.

--- 

📌 Short description
Transistor-level CMOS inverter design with Layout XL verification and transient comparison. Shows the effect of layout parasitics on timing (schematic vs extracted-layout).

---

📝 Key results
- Schematic transient delay (midpoint): 42.77 ps
- Layout (PEX) transient delay (midpoint): 48.68 ps
- Increase due to layout parasitics: ~13.82% (≈ 5.91 ps difference)
- DRC: Clean (no violations)
- LVS: Matches schematic (no mismatches)

---

🛠 Tools & environment
- Cadence Virtuoso (schematic, symbol, layout)
- Layout XL (DRC / LVS)
- ADE / Spectre (transient simulation, PEX)

🔧 What’s included
- Schematic cell view of the CMOS inverter
- Generated symbol for hierarchical use
- Layout view (Layout XL) — DRC & LVS clean
- Testbench schematic (stimulus for transient)
- Parasitic-extracted netlist (PEX) and PEX simulation setup
- Transient waveforms and comparison plots
- DRC / LVS reports
