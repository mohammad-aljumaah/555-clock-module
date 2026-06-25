# 555 Clock Module

Designed by Mohammad Aljumaah . mohammad-aljumaah.me

A simple clock pulse generator built with the NE555P timer IC.
Outputs a ~7 Hz square wave. useful for clocking counters, shift registers, and other digital circuits.

Designed from scratch in KiCad. Includes schematic, PCB layout, Gerbers, and a full datasheet.

---

## Specs

| | |
|---|---|
| Supply | 5 V DC |
| Output | ~7 Hz square wave, ~50% duty cycle |
| Connector | 3-pin header — GND / VCC / CLK_OUT |
| Main IC | NE555P (DIP-8) |
| PCB | 2-layer, 4× M3 mounting holes |

---

## Repo Structure

```
Documentation/
├── datasheet.pdf       ← Full datasheet with specs, BOM, pinout, and theory
└── schematic.pdf       ← Exported schematic

Hardware/
├── 555-timer-clock.kicad_sch
├── 555-timer-clock.kicad_pcb
└── 555-timer-clock.kicad_pro

Production/
├── Gerbers/            ← Ready to send to a PCB fab
└── ZIP/
    └── 555-timer-clock-rA.zip   ← Zipped Gerbers, ready to upload
```

---

## Ordering a PCB

Upload `Production/ZIP/555-timer-clock-rA.zip` to any PCB fab:

- [JLCPCB](https://jlcpcb.com)
- [PCBWay](https://pcbway.com)
- [OSH Park](https://oshpark.com)

Recommended: **2 layers · FR-4 · 1.6 mm · HASL**

---

## Documentation

See [`Documentation/datasheet.pdf`](Documentation/datasheet.pdf) for the full datasheet. includes BOM, pinout, how to use it, how to change the speed, and safety notes.

---

**Mohammad Aljumaah** · [mohammad-aljumaah.me](https://mohammad-aljumaah.me)
