---
permalink: /research/
title: "Cell-Free Gene Expression"
author_profile: false
---

{% include base_path %}

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

**Relevant Work**  

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

<style>
.relevant-work {
  display: flex;
  flex-wrap: wrap;
  gap: 1rem;
  margin: 1.5rem 0;
}
.rw-card {
  display: block;
  flex: 1 1 260px;
  max-width: 320px;
  padding: 1rem 1.1rem;
  border: 1px solid #d8dee6;
  border-left: 3px solid #1a2b4c;
  border-radius: 6px;
  text-decoration: none;
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


---

## Biotechnology Applications

---

