---
permalink: /research/
title: "Cell-Free Gene Expression"
author_profile: false
---

{% include base_path %}

<style>
.relevant-work {
  display: flex;
  flex-wrap: wrap;
  gap: 1rem;
  margin: 1.5rem 0;
}
.rw-card,
.rw-card:hover,
.rw-card:visited,
.rw-card * {
  text-decoration: none !important;
}
.rw-card {
  display: block;
  flex: 1 1 260px;
  max-width: 320px;
  padding: 1rem 1.1rem;
  border: 1px solid #d8dee6;
  border-left: 3px solid #1a2b4c;
  border-radius: 6px;
  color: inherit;
  background: #fff;
  transition: box-shadow 0.2s ease, transform 0.2s ease, border-color 0.2s ease;
}
.rw-card:hover {
  box-shadow: 0 6px 16px rgba(26,43,76,0.15);
  transform: translateY(-2px);
  border-left-color: #3d6fb4;
}
.rw-title {
  font-weight: 600;
  font-size: 0.95rem;
  color: #1a2b4c;
  margin-bottom: 0.35rem;
  line-height: 1.3;
}
.rw-meta {
  font-size: 0.8rem;
  color: #6b7280;
  margin-bottom: 0.5rem;
}
.rw-abstract {
  font-size: 0.85rem;
  color: #444;
  line-height: 1.4;
  max-height: 0;
  opacity: 0;
  overflow: hidden;
  transition: max-height 0.3s ease, opacity 0.3s ease, margin-top 0.3s ease;
}
.rw-card:hover .rw-abstract {
  max-height: 200px;
  opacity: 1;
  margin-top: 0.25rem;
}
</style>

Cell-free gene expression systems recreate the transcription and translation reactions of living cells in an open test-tube environment. By operating outside the constraints on cell growth and survival, these systems allow rapid design and engineering of biological systems that are difficult (and sometimes impossible) to study within living cells.

Over the past decade, *E. coli* lysate-based cell-free expression systems have emerged as a powerful platform for protein expression, biosensor development, metabolic engineering, and high-throughput screening. Yet as we move on to tackle increasingly ambitious problems, the limitations of *E. coli*-based platforms are becoming more apparent. Crude lysates contain thousands of native enzymes and regulatory molecules that can interfere with engineered systems, and the native biochemistry and machinery of *E. coli* fall short in supporting the growing diversity of biological designs.

Meeting these challenges requires platform innovation. Our laboratory builds next-generation cell-free platforms to expand what we can build with biology. Our research is organized around two complementary themes:

- **Platform innovation**, in which we develop cell-free gene expression systems that expand the reach of synthetic biology
- **Biotechnology application**, in which we apply these engineered systems to solve pressing biological problems

Our platform and biotechnology efforts inform one another. New capabilities of cell-free platforms make previously inaccessible applications possible, while application-driven challenges reveal the limitations of existing platforms and motivate the development of better ones. Through this integrated process, we seek to expand the range of biological systems that can be designed, built, and deployed.

<img src="/images/ResearchMain.png" alt="Platform innovation and biotechnology application feedback loop" style="max-width: 600px; width: 100%; height: auto; display: block; margin: 1.5em auto;">

---

## Platform Innovation

**Host-derived Systems**

Most cell-free expression platforms are built from lysates of a single host, typically *E. coli*, but the composition of the lysate itself is a black box. Our lab characterizes the lysate proteome, RNA pool, and metabolome in detail to understand how reaction chemistry comes together to support our gene expression tasks. Work in this area has already pinpointed concrete, fixable bottlenecks: from a missing cofactor to mismatched tRNA usage and availability. Diagnosing these bottlenecks lets us engineer the host and reaction conditions accordingly, arriving at reaction environments that are simpler to assemble and more reliably productive.

**Reconstituted Systems**

Reconstituted cell-free expression systems are built from purified components rather than crude cell extract, trading yield and cost for better control over reaction composition. Our lab develops custom reconstituted gene expression platforms for biosensor diagnostics that would not otherwise work in the crude cell lysate environment. By stripping away the murky background chemistry in reconstituted systems, we create a clean reaction environment in which sensors respond only to their intended signal. While this initially focuses on biosensor development, our broader goal is a future *design-build-work* workflow in which we understand every element's purpose and activity, so we control reaction rate and yield from the outset rather than discovering them through trial and error.

**Relevant Works**

<div class="relevant-work">
  <a class="rw-card" href="https://yan-zhanglab.github.io/publication/2025-04-10-Optimizing-One-Pot-PURE" target="_blank" rel="noopener">
    <div class="rw-title">Optimizing protein production in the One-Pot PURE system: insights into reaction composition and expression efficiency</div>
    <div class="rw-meta">ACS Synthetic Biology · 2025</div>
    <div class="rw-abstract">Characterizes proteome and tRNA composition bottlenecks in the One-Pot PURE system, improving cell-free protein yield and reproducibility across labs.</div>
  </a>
  <a class="rw-card" href="https://yan-zhanglab.github.io/publication/2021-09-01-Metabolic-Dynamics-in-Escherichia-coli-Based-Cell-Free-Systems" target="_blank" rel="noopener">
    <div class="rw-title">Metabolic Dynamics in Escherichia coli-Based Cell-Free Systems</div>
    <div class="rw-meta">ACS Synthetic Biology · 2021</div>
    <div class="rw-abstract">Uses metabolomics to profile temporal metabolic dynamics in E. coli-based cell-free reactions, revealing robust, lysate-dependent behavior that shapes protein yield.</div>
  </a>
</div>

---

## Biotechnology Applications

**Biosensor Diagnostics**

Cell-free systems are especially well-suited to biosensor diagnostics. By simply swapping the genetic program that expresses the sensor and reporter output, the same reaction can be tuned to detect analytes ranging from ions and small molecules to nucleic acids and proteins. To reach point-of-need settings, these cell-free reactions can be freeze-dried for ambient-temperature storage and shipment and activated on demand by simply adding the sampling fluid. Our goal is to build diagnostic platforms that are fast, low-cost, and field-deployable, while meeting the sensitivity and specificity needed for real-world clinical and environmental samples.

**Phage Therapeutics**

As cases of antibiotic resistance grow, using bacteriophages (the natural predators of bacteria) as antimicrobial agents to treat multidrug-resistant infections is gaining renewed attention. Rather than relying on the traditional phage cultivation method, which requires propagating the susceptible host, the cell-free expression platform enables on-demand acceleration of phage production and engineering. We are applying our cell-free platform development to support diverse phage rebooting, in which we assemble and recover infectious phages directly from their genome sequence, without a host, and engineer them against pressing ESKAPE pathogens.

**Relevant Works**

<div class="relevant-work">
  <a class="rw-card" href="https://yan-zhanglab.github.io/publication/2021-09-01-Protocell-arrays-for-simultaneous-detection-of-diverse-analytes" target="_blank" rel="noopener">
    <div class="rw-title">Protocell arrays for simultaneous detection of diverse analytes</div>
    <div class="rw-meta">Nature Communications · 2021</div>
    <div class="rw-abstract">Integrates cell-free expression into membrane-less protocells arrayed together, enabling simultaneous detection of chemically diverse targets from a single sample.</div>
  </a>
  <a class="rw-card" href="https://yan-zhanglab.github.io/publication/2021-11-01-Point-of-Care-Analyte-Quantification-and-Digital-Readout-via-Lysate-Based-Cell-Free-Biosensors-Interfaced-with-Personal-Glucose-Monitors" target="_blank" rel="noopener">
    <div class="rw-title">Point-of-Care Analyte Quantification and Digital Readout via Lysate-Based Cell-Free Biosensors Interfaced with Personal Glucose Monitors</div>
    <div class="rw-meta">ACS Synthetic Biology · 2021</div>
    <div class="rw-abstract">Couples E. coli lysate-based biosensors to personal glucose monitors, enabling reconfigurable, quantitative analyte detection at the point of care.</div>
  </a>
  <a class="rw-card" href="https://yan-zhanglab.github.io/publication/2019-09-01-Point-of-care-biomarker-quantification-enabled-by-sample-specific-calibration" target="_blank" rel="noopener">
    <div class="rw-title">Point-of-care biomarker quantification enabled by sample-specific calibration</div>
    <div class="rw-meta">Science Advances · 2019</div>
    <div class="rw-abstract">Uses each patient sample to generate its own calibration curve, enabling quantitative, naked-eye colorimetric readouts robust to complex sample interference.</div>
  </a>
</div>

---
