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

Two most common leuco dyes used (click to learn more):

<!--- Chemical Structures Crop: 1600x1200 dpi:96 --->

{{< cards >}}
  {{< card title="Fluoran" subtitle="Fluoran is a broad category of leuco dyes that can produce typically black or blue." image="/images/fluoran.png" link="https://pubchem.ncbi.nlm.nih.gov/compound/68994" >}}
  {{< card title="Crystal Violet Lactone (CVL)" subtitle="CVL is a triphenylmethane leuco dye that is used to produce blue or violet." image="/images/cvl.png" link="https://pubchem.ncbi.nlm.nih.gov/compound/73773">}}
{{< /cards >}}

### Developers

Developers are chemicals that react with leuco dyes in the presence of heat to produce the colour change. Developers have acidic properties that trigger leuco dyes to change colour.

Two most common developers used (click to learn more):

{{< cards >}}
  {{< card title="Bisphenol A (BPA)" subtitle="subtitle" image="/images/bpa.png" method="Crop" options="1600x1200 Center" link="https://pubchem.ncbi.nlm.nih.gov/compound/6623" >}}
  {{< card title="Bisphenol S (BPS)" subtitle="Subtitle" image="/images/bps.png" method="Crop" options="1600x1200 Center" link="https://pubchem.ncbi.nlm.nih.gov/compound/6626">}}
{{< /cards >}}

### Phase Change Materials (PCM) 

Phase change materials serve as the medium within which the leuco dye and developer are embedded. When heat is applied, it melts, allowing a reaction between the leuco dye and developer.

![Receipt Paper Layers](rp-layers.jpg)

[^1]: test