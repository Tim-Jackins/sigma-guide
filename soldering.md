---
layout: page
title: Soldering
permalink: /soldering/
---

# Soldering

> Solder wire heated to 350° can be dangerous. You must be on your mettle!

## The Basics

Soldering is the process of joining two electrical components, whether they are [wire, pads, or ball grid arrays](http://www.pcb.electrosoft-engineering.com/04-articles-custom-system-design-and-pcb/01-printed-circuit-board-concepts/printed-circuit-board-pcb-concepts.html), with solder. Wait a minute, what's solder? Solder is a metal wire with a resonably low melting point. The benefit of soldering instead of using glue or some other adhesive is that solder is conductive. This allows you to make a strong electrical connection easily.

*Ugh, I hate reading. Is there a [good video](http://www.youtube.com/watch?v=QKbJxytERvg) for this?*

### Materials

Only solder wires and components that are meant to be soldered. If you're not sure if something should be soldered ask a teacher.

### Usage

Do not under any circumstances use it to cut plastic, make large pools or solder, or poke holes in acrylic and anything else. This can damage the iron, **do not do it**.

1. Remember to lightly wet the sponge before you start soldering
2. Don't use too much solder. Cover the pad but nothing else. Less is more; you want teeth not bubbles.
3. If you make a mistake grab a solder sucker and fix it.
4. Remember to turn off the station when you're done.
5. Clean up your station.

### Known problems

If the station displays a static `1` as the tempurature, try turning it off, waiting a second, and turning it back on. If that doesn't work try unplugging the iron, wait a second, and plug it back in.

If solder is covering a through-hole, you should place the soldering iron on one side and a solder sucker on the other side. Heat up the solder with the iron and pull away the iron while sucking the solder throught the hole and into the solder sucker. Sometimes you must add some solder to help leftover solder heat up don't be afraid to do this it can help get you out of a jam.

## SMD / SMT Soldering

If you [cut your own PCB](https://github.com/Tim-Jackins/pcb-machining), you will need to solder some SMD / SMT components. SMD components are simply normal components that come in [smaller packages](https://www.electronics-notes.com/articles/electronic_components/surface-mount-technology-smd-smt/packages.php).

### Materials

Currently we have the following SMD components:

| Type          | Size |
| ------------- |:----:|
| 10kΩ Resistor | 0805 |
| 220Ω Resistor | 0805 |
| LED (Red)     | 1206 |
| LED (Blue)    | 1206 |
| LED (White)   | 1206 |
| LED (Yellow)  | 1206 |
| LED (Green)   | 1206 |

### Usage

There's a [good video](https://www.youtube.com/watch?v=QzoPxvIM2qE) that you should really watch but in a general sense: follow all the same rules as regular solder and when you solder an SMD component add solder to one of the pads, heat up that pad and position the SMD component, then solder the other side of the component.
