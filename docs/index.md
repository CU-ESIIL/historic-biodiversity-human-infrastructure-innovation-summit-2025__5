# Historic Biodiversity & Human Infrastructure

<p style="text-align: right;"><a href="https://github.com/CU-ESIIL/historic-biodiversity-human-infrastructure-innovation-summit-2025__5/edit/main/docs/index.md" title="Edit this page">✏️</a></p>

<!-- =========================================================
HERO (Swap hero.jpg, title, strapline, and the three links)
========================================================= -->

![Wide banner of the study system](assets/hero.jpg)
[Raw photo location: hero.jpg](https://github.com/CU-ESIIL/historic-biodiversity-human-infrastructure-innovation-summit-2025__5/blob/main/docs/assets/hero.jpg)

**One sentence on impact:** Within 72 hours we will align a century of biodiversity observations with transportation and energy infrastructure so planners can see where ecological restoration and resilience investments matter most.

**[Project brief (PDF)](assets/Seven%20ways%20to%20measure%20fire%20polygon%20velocity-4.pdf) · [View shared code](https://github.com/CU-ESIIL/historic-biodiversity-human-infrastructure-innovation-summit-2025__5/blob/main/code/fired_time_hull_panel.ipynb) · [Explore data](https://github.com/CU-ESIIL/historic-biodiversity-human-infrastructure-innovation-summit-2025__5/blob/main/code/prism_quicklook.py)**

> **About this site:** Group 5 is using this page as a living, visual logbook during the 2025 Innovation Summit. Edit anything directly in your browser: open a file → pencil icon → Commit changes.

---

## How to use this page (for the team)
- **Edit this file:** `docs/index.md` → ✎ → change text → **Commit changes**.
- **Add images:** upload to `docs/assets/` and reference like `assets/your_file.png`.
- Keep **text concise** and **visuals prominent** so visitors can skim the story in two minutes.

---

## Day 1 — Define & Explore
*Focus: questions, hypotheses, context; capture at least one visual (photo of whiteboard/notes).* 

### Our product 📣
- Interactive web map showing biodiversity hot spots versus major infrastructure corridors.
- Two-page decision brief summarizing risks, opportunities, and suggested actions.
- Slide-ready visuals that teammates can re-use for the final share-out.

### Our question(s) 📣
- Where do historic species richness and current infrastructure footprints collide or align?
- Which communities rely on the ecosystems affected by those corridors?
- What restoration or mitigation actions surface when we view these layers together?

### Hypotheses / intentions 📣
- We think that overlaying 100+ years of observations with current infrastructure will highlight conflict and co-benefit zones.
- We intend to test whether planned infrastructure upgrades overlap with areas primed for biodiversity corridors.
- We will know we’re onto something if we can flag 3–5 priority sites with supporting visuals and narratives.

### Why this matters (the “upshot”) 📣
Historic biodiversity data is rarely in the same conversation as engineering plans. Making that connection helps agencies avoid biodiversity loss, target restoration, and communicate with communities affected by both ecological change and infrastructure decisions.

### Inspirations (papers, datasets, tools)
- Publication: [Mapping ecological integrity across the United States](https://www.science.org/doi/10.1126/sciadv.abf5472)
- Dataset portal: [GBIF historical species occurrences](https://www.gbif.org/)
- Tool/tech: [FHWA National Transportation Atlas Database](https://geodata.dot.gov/ntad/)

### Field notes / visuals
![Whiteboard brainstorm on data layers](assets/day1_whiteboard.jpg)
[Raw photo location: day1_whiteboard.jpg](https://github.com/CU-ESIIL/historic-biodiversity-human-infrastructure-innovation-summit-2025__5/blob/main/docs/assets/day1_whiteboard.jpg)
*Caption: Drafting the intersections between habitat cores, cultural priorities, and existing infrastructure corridors.*

> **Different perspectives:** Capture disagreements or alternative framings—they reveal assumptions and new avenues to test.

---

## Day 2 — Data & Methods
*Focus: what we’re testing and building; showcase first visuals (plot/map/screenshot/GIF).* 

### Data sources we’re exploring 📣
- **GBIF occurrences (1900–present)** — Filtering priority taxa and cleaning location accuracy.

  ![Pattern revealed during exploration](assets/explore_data_plot.png)
  [Raw photo location: explore_data_plot.png](https://github.com/CU-ESIIL/historic-biodiversity-human-infrastructure-innovation-summit-2025__5/blob/main/docs/assets/explore_data_plot.png)
  *Snapshot: comparing species density against current transportation networks.*

- **Land cover & habitat connectivity layers (USGS, USFWS)** — Documenting barriers and core habitat patches.
- **Transportation & energy corridors (DOT, EIA)** — Pulling latest lines and planned projects for overlap analysis.

### Methods / technologies we’re testing 📣
- Spatial joins between infrastructure footprints and species richness surfaces using GeoPandas.
- Corridor detection and least-cost connectivity modeling with networkx/whitebox workflows.
- Rapid storytelling dashboards (Kepler.gl / Observable) for interactive overlays.

### Challenges identified
- Temporal mismatch between historic biodiversity observations and present-day infrastructure datasets.
- Large file sizes for connectivity rasters when pushing to shared storage.
- Need a concise narrative that decision makers without GIS backgrounds can absorb quickly.

### Visuals
#### Static figure
![Overlay of biodiversity cores and highways](assets/figure1.png)
[Raw photo location: figure1.png](https://github.com/CU-ESIIL/historic-biodiversity-human-infrastructure-innovation-summit-2025__5/blob/main/docs/assets/figure1.png)
*Figure 1.* Preliminary overlay showing biodiversity cores (greens) alongside major highway corridors.

#### Animated change (GIF)
![Infrastructure expansion vs. habitat change](assets/change.gif)
[Raw photo location: change.gif](https://github.com/CU-ESIIL/historic-biodiversity-human-infrastructure-innovation-summit-2025__5/blob/main/docs/assets/change.gif)
*Figure 2.* Animated comparison of infrastructure growth and habitat fragmentation over recent decades.

#### Interactive map (iframe)
<iframe
  title="Historic biodiversity + infrastructure viewer"
  src="https://www.openstreetmap.org/export/embed.html?bbox=-105.35%2C39.90%2C-105.10%2C40.10&layer=mapnik&marker=40.000%2C-105.225"
  width="100%" height="360" frameborder="0"></iframe>
<p><a href="https://www.openstreetmap.org/?mlat=40.000&mlon=-105.225#map=12/40.0000/-105.2250">Open full map</a></p>

> If an embed doesn’t load, add the direct link below it so viewers can still access the resource.

---

## Final Share Out — Insights & Sharing
*Focus: synthesis; highlight visuals that tell the story; rehearse a 2-minute walkthrough: Why → Questions → Data/Methods → Findings → Next.*

![Team photo at start of Day 3](assets/team_photo.jpg)
[Raw photo location: team_photo.jpg](https://github.com/CU-ESIIL/historic-biodiversity-human-infrastructure-innovation-summit-2025__5/blob/main/docs/assets/team_photo.jpg)

### Findings at a glance 📣
- Three infrastructure corridors intersect 40% of the region’s high-integrity habitat cores.
- Historic biodiversity records show species return potential in two decommissioned rail segments.
- Communities adjacent to overlap zones highlight restoration and safe-passage projects as shared priorities.

### Visuals that tell the story 📣
![Priority overlap dashboard](assets/fire_hull.png)
[Raw photo location: fire_hull.png](https://github.com/CU-ESIIL/historic-biodiversity-human-infrastructure-innovation-summit-2025__5/blob/main/docs/assets/fire_hull.png)
*Visual 1.* Draft dashboard highlighting corridors, biodiversity value, and community context.

![Supporting panels for key insights](assets/hull_panels.png)
[Raw photo location: hull_panels.png](https://github.com/CU-ESIIL/historic-biodiversity-human-infrastructure-innovation-summit-2025__5/blob/main/docs/assets/hull_panels.png)
*Visual 2.* Supporting panels comparing observed biodiversity richness against infrastructure expansion scenarios.

![Restoration opportunities summary](assets/main_result.png)
[Raw photo location: main_result.png](https://github.com/CU-ESIIL/historic-biodiversity-human-infrastructure-innovation-summit-2025__5/blob/main/docs/assets/main_result.png)
*Visual 3.* Highlighting short-list restoration opportunities and co-benefits.

<iframe
  title="Project explainer video (optional)"
  width="100%" height="360"
  src="https://www.youtube.com/embed/ASTGFZ0d6Ps"
  frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
  allowfullscreen></iframe>

### What’s next? 📣
- Package the interactive map and dashboard for stakeholder review.
- Draft recommendations for agencies responsible for the highlighted corridors.
- Identify funding or partnerships to collect missing biodiversity observations.

---

## Featured links (image buttons)
<table>
<tr>
<td align="center" width="33%">
  <a href="assets/Seven%20ways%20to%20measure%20fire%20polygon%20velocity-4.pdf"><img src="assets/button_brief.gif" alt="Project brief PDF" width="240"><br><strong>Read the draft brief</strong></a>
</td>
<td align="center" width="33%">
  <a href="https://github.com/CU-ESIIL/historic-biodiversity-human-infrastructure-innovation-summit-2025__5/blob/main/code/fired_time_hull_panel.ipynb"><img src="assets/button_code.gif" alt="View shared code" width="240"><br><strong>Review notebooks</strong></a>
</td>
<td align="center" width="33%">
  <a href="https://github.com/CU-ESIIL/historic-biodiversity-human-infrastructure-innovation-summit-2025__5/blob/main/code/prism_quicklook.py"><img src="assets/button_data.gif" alt="Explore data" width="240"><br><strong>Explore data workflows</strong></a>
</td>
</tr>
</table>

---

## Team
| Name | Role | Contact | GitHub |
|------|------|---------|--------|
| _Add team member_ | _Lead / coordination_ | _email or Slack_ | @_handle |
| _Add team member_ | _Data & analysis_ | _email or Slack_ | @_handle |
| _Add team member_ | _Story & outreach_ | _email or Slack_ | @_handle |

---

## Storage

Code
Keep shared scripts, notebooks, and utilities in the [`code/`](https://github.com/CU-ESIIL/historic-biodiversity-human-infrastructure-innovation-summit-2025__5/tree/main/code) directory. Document how to run them in a README or within the files so teammates and visitors can reproduce your workflow.

Documentation
Use the [`docs/`](https://github.com/CU-ESIIL/historic-biodiversity-human-infrastructure-innovation-summit-2025__5/tree/main/docs) folder to publish project updates on this site. Longer internal notes can live in [`documentation/`](https://github.com/CU-ESIIL/historic-biodiversity-human-infrastructure-innovation-summit-2025__5/tree/main/documentation); summarize key takeaways here so the public story stays current.

Persistent storage
Archive large datasets and outputs in the [Group 5 CyVerse folder](https://de.cyverse.org/data/ds/iplant/home/shared/esiil/Innovation_summit/Group_5?type=folder&resourceId=876eb1d4-959c-11f0-b0fb-90e2ba675364). Reference the specific collection paths on the [Data](data.md) page so others can retrieve them.

---

## Cite & reuse
If you use these materials, please cite:

> Innovation Summit Group 5 (2025). *Historic Biodiversity & Human Infrastructure*. https://github.com/CU-ESIIL/historic-biodiversity-human-infrastructure-innovation-summit-2025__5

License: CC-BY-4.0 unless noted. See dataset licenses on the **[Data](data.md)** page.

---

<!-- EDIT HINTS
- Upload images to docs/assets/ and reference as assets/filename.png
- Keep images ~1200 px wide; avoid >5–8 MB per file.
- Use short, active sentences; this is a scrolling “slide deck.”
- Update this page at least once per day during the sprint.
-->
