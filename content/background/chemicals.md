---
title: Chemicals 
type: docs
weight: 2
prev: background/context
next: risk-assessment
---

## Thermal Layer

```mermaid

flowchart LR
	leuco([Leuco Dye]) ---> pcm[Phase Change Material]
    dev([Developer]) ---> pcm
    
    pcm --> tl[Thermal Layer]

    sen([Sensitizers]) --> tl
    stab([Stabilizers]) --> tl

    tl --> rp((( Receipt Paper)))
    
    style tl stroke-width:4px,stroke-dasharray: 0

```

Within the thermal layer, six chemical components facilitate a reaction when the receipt paper is exposed to heat. Critically, the agents responsible for the color change are the leuco dye, developer, and phase change materials. Although the precise composition may vary, these chemicals are commonly used:

### Leuco Dyes

Leuco Dyes are colourless (or nearly colourless) compounds that can be transformed into a coloured state by a chemical reaction. In thermal paper, leuco dyes develop colour when they react with developers. The colour change typically occurs due to a structural change in the dye molecule, which alters the way it absorbs and reflects light.

{{< cards >}}
  {{< card title="Fluoran" image="background/fluoran.png" >}}
  {{< card title="Crystal Violet Lactone" image="background/cvl.png" >}}
{{< /cards >}}

### Developers

Developers are chemicals that react with leuco dyes in the presence of heat to produce the colour change. Developers have acidic properties that trigger leuco dyes to change colour.

### Phase Change Materials (PCM) 

Phase change materials serve as the medium within which the leuco dye and developer are embedded. When heat is applied, it melts, allowing a reaction between the leuco dye and developer.hugo

{{< callout type="info" >}}
  Although the precise composition may vary, these are some of the most commonly used chemicals:
{{< /callout >}}
