---
permalink: /research/
title: "Platform Innovation"
author_profile: false
---

{% include base_path %}

<style>
.lede {
  font-size: 1.35rem;
  line-height: 1.4;
  color: #1a2b4c;
  font-weight: 500;
  margin: 0 0 1.1rem;
}
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
.rw-card:hover,
.rw-card:focus-visible {
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
  line-height: 1.45;
}
.theme {
  font-weight: 600;
  font-size: 1.05rem;
  color: #1a2b4c;
  margin: 1.8rem 0 0.4rem;
}
.sec {
  display: flex;
  align-items: center;
  gap: 0.9rem;
  margin: 2.6rem 0 1rem;
  padding-bottom: 0.6rem;
  border-bottom: 1px solid #e5e9ef;
}
.sec-icon {
  max-height: 54px;
  max-width: 72px;
  width: auto;
  flex: 0 0 auto;
}
.sec h2 {
  margin: 0 !important;
  font-size: 1.35rem;
  color: #1a2b4c;
  line-height: 1.25;
}
.claim {
  font-size: 1.02rem;
  font-weight: 600;
  color: #1a2b4c;
  line-height: 1.4;
  margin: 1.6rem 0 0.5rem;
}
.claim + p {
  margin-top: 0;
}
</style>

<p class="lede">We are a platform innovations lab. We expand the platforms at hand to build with biology and, in the process, expand what they can do to unlock new biotechnology.</p>

Cell-free gene expression systems recreate the same gene transcription and translation in an open test tube reaction. By removing constraints such as cell growth and survival in a living cell, cell-free systems let us design and engineer biological systems that are difficult, and sometimes impossible, to work on.

For decades, the *E. coli* lysate-based cell-free system has been the workhorse powering biotechnology innovations, but it also set an inconvenient ceiling. Crude lysate carries thousands of native enzymes and regulatory molecules that interfere with engineered systems, and *E. coli*'s own biochemistry cannot support the growing diversity of designs people want to build. Sooner or later, the limit isn't what biology can do, it's what the platform can support.

We are now facing this ceiling. Our ability to design and build with biology is advancing faster than ever, but the platform can no longer support our endeavors. So we build better platforms.


<div class="sec">
  <img class="sec-icon" src="{{ base_path }}/images/step-microbe.png" alt="A rod-shaped microbe with a phage attached">
  <h2>Expanding the Platforms We Work On</h2>
</div>

<div class="theme">Host-derived Systems</div>

<p class="claim">Most cell-free platforms are built from the lysate of a single host, and the composition of that lysate is a black box.</p>

We characterize the proteome, RNA pool, and metabolome in detail to understand how the reaction chemistry actually comes together to support gene expression. This has already pinpointed concrete, fixable bottlenecks, from a missing cofactor to mismatched tRNA usage and availability. Diagnosing a bottleneck lets us engineer the host and the reaction conditions against it, arriving at reaction environments that are simpler to assemble and more reliably productive.

<div class="theme">Reconstituted Systems</div>

<p class="claim">Reconstituted systems are built from purified components rather than crude extract, trading yield and cost for control over composition.</p>

We develop custom reconstituted platforms for sensing tasks that will not work in a crude lysate background at all. Stripping away the murky background chemistry creates a clean reaction environment in which a sensor responds only to its intended signal. The longer goal is a design-build-test workflow where every element's purpose and activity is known, so reaction rate and yield are set deliberately rather than discovered by trial and error.

**Relevant Works**

<div class="relevant-work">
  <a class="rw-card" href="{{ base_path }}/publication/2025-04-10-Optimizing-One-Pot-PURE">
    <div class="rw-title">Optimizing protein production in the One-Pot PURE system: insights into reaction composition and expression efficiency</div>
    <div class="rw-meta">ACS Synthetic Biology · 2025</div>
    <div class="rw-abstract">Characterizes proteome and tRNA composition bottlenecks in the One-Pot PURE system, improving cell-free protein yield and reproducibility across labs.</div>
  </a>
  <a class="rw-card" href="{{ base_path }}/publication/2021-09-01-Metabolic-Dynamics-in-Escherichia-coli-Based-Cell-Free-Systems">
    <div class="rw-title">Metabolic Dynamics in <i>Escherichia coli</i>-Based Cell-Free Systems</div>
    <div class="rw-meta">ACS Synthetic Biology · 2021</div>
    <div class="rw-abstract">Uses metabolomics to profile temporal metabolic dynamics in <i>E. coli</i>-based cell-free reactions, revealing robust, lysate-dependent behavior that shapes protein yield.</div>
  </a>
</div>


<div class="sec">
  <img class="sec-icon" src="{{ base_path }}/images/step-apply.png" alt="A gear, representing biotechnology built on the platform">
  <h2>What New Platforms Open Up</h2>
</div>

A platform is only as interesting as what it lets someone build. Each capability we add opens applications that were previously out of reach, and each application we chase exposes the next platform limitation. Two directions currently drive the work.

<div class="theme">Phage Therapeutics</div>

<p class="claim">Traditional phage work requires propagating a susceptible host. A cell-free platform does not.</p>

As antibiotic resistance spreads, bacteriophages, the natural predators of bacteria, are drawing renewed attention as antimicrobials against multidrug-resistant infections. We reboot phage directly from genome sequence, assembling and recovering infectious particles without a host, which makes production and engineering far faster. We are building this capability out across diverse phage and engineering them against ESKAPE pathogens.

<div class="theme">Biosensor Diagnostics</div>

<p class="claim">Swap the genetic program, and the same reaction detects a different target.</p>

Cell-free reactions are unusually well suited to diagnostics: one reaction can be retargeted from ions and small molecules to nucleic acids and proteins just by changing the sensor and reporter it expresses. For point-of-need use, these reactions can be freeze-dried for ambient-temperature storage and shipping, then activated by adding the sample itself. We build toward diagnostics that are fast, low-cost, and field-deployable while still meeting the sensitivity and specificity that real clinical and environmental samples demand.

**Relevant Works**

<div class="relevant-work">
  <a class="rw-card" href="{{ base_path }}/publication/2021-09-01-Protocell-arrays-for-simultaneous-detection-of-diverse-analytes">
    <div class="rw-title">Protocell arrays for simultaneous detection of diverse analytes</div>
    <div class="rw-meta">Nature Communications · 2021</div>
    <div class="rw-abstract">Integrates cell-free expression into membrane-less protocells arrayed together, enabling simultaneous detection of chemically diverse targets from a single sample.</div>
  </a>
  <a class="rw-card" href="{{ base_path }}/publication/2021-11-01-Point-of-Care-Analyte-Quantification-and-Digital-Readout-via-Lysate-Based-Cell-Free-Biosensors-Interfaced-with-Personal-Glucose-Monitors">
    <div class="rw-title">Point-of-Care Analyte Quantification and Digital Readout via Lysate-Based Cell-Free Biosensors Interfaced with Personal Glucose Monitors</div>
    <div class="rw-meta">ACS Synthetic Biology · 2021</div>
    <div class="rw-abstract">Couples <i>E. coli</i> lysate-based biosensors to personal glucose monitors, enabling reconfigurable, quantitative analyte detection at the point of care.</div>
  </a>
  <a class="rw-card" href="{{ base_path }}/publication/2019-09-01-Point-of-care-biomarker-quantification-enabled-by-sample-specific-calibration">
    <div class="rw-title">Point-of-care biomarker quantification enabled by sample-specific calibration</div>
    <div class="rw-meta">Science Advances · 2019</div>
    <div class="rw-abstract">Uses each patient sample to generate its own calibration curve, enabling quantitative, naked-eye colorimetric readouts robust to complex sample interference.</div>
  </a>
</div>


<div class="sec">
  <img class="sec-icon" src="{{ base_path }}/images/step-ship.png" alt="A paper plane shipping biological designs into living cells">
  <h2>Shipping the Program</h2>
</div>

Building outside the cell is a means, not the end. The tube is where we can see and control every variable. Shipping is where we give that control up.

A phage rebooted in a tube has to go on to infect a live pathogen. A sensor built in a clean reconstituted reaction has to return a true answer in serum, in an environmental sample, in whatever someone actually hands us. Both are the same test in different form: the program has to hold true somewhere we do not govern.

That trip is the hardest test we can give our own work, and it is where our funded projects point: engineering rebooted phage against live ESKAPE pathogens, and detecting, eliminating, and reprogramming the oncogenic bacteria implicated in colorectal cancer.

<p style="font-size: 0.95rem;">More detail on the <a href="{{ base_path }}/projects/nih-k99-r00-adaptive-phage-framework">adaptive phage framework</a> and the <a href="{{ base_path }}/projects/cprit-oncogenic-bacteria-colorectal-cancer">oncogenic bacteria project</a>.</p>
