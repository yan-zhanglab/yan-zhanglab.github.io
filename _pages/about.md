---
permalink: /
title: "Zhang Lab for Cell-Free Synthetic Biology"
excerpt: ""
author_profile: false
redirect_from: 
  - /about/
  - /about.html
---

<style>
.lede {
  font-size: 1.35rem;
  line-height: 1.4;
  color: #1a2b4c;
  font-weight: 500;
  margin: 0 0 1.1rem;
}
.lede-test {
  font-size: 1rem;
  line-height: 1.7;
  color: #1a2b4c;
  margin: 0 0 1.6rem;
}
.arc {
  display: flex;
  align-items: stretch;
  gap: 0.55rem;
  margin: 0.4rem 0 1.9rem;
}
.arc-step {
  flex: 1 1 0;
  min-width: 0;
  display: flex;
  flex-direction: column;
  gap: 0.28rem;
  padding: 1rem 1.05rem 1.05rem;
  border: 1px solid #dde3ea;
  border-radius: 8px;
  background: #fff;
  transition: box-shadow 0.2s ease, border-color 0.2s ease;
}
.arc-step:hover {
  box-shadow: 0 4px 12px rgba(26,43,76,0.09);
  border-color: #c3d4ea;
}
.arc-step--final {
  background: #f4f8fd;
  border-color: #bcd0ea;
}
.arc-head {
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 0.5rem;
  height: 72px;
  margin-bottom: 0.55rem;
}
.arc-icon {
  max-height: 64px;
  max-width: 104px;
  width: auto;
  flex: 0 0 auto;
}
.arc-icon--ship {
  max-height: 48px;
}
.arc-num {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  width: 22px;
  height: 22px;
  border-radius: 50%;
  background: #1a2b4c;
  color: #fff;
  font-size: 0.72rem;
  font-weight: 700;
  line-height: 1;
  margin-bottom: 0.2rem;
}
.arc-step--final .arc-num {
  background: #3d6fb4;
}
.arc-label {
  font-size: 1rem;
  font-weight: 600;
  color: #1a2b4c;
  line-height: 1.3;
  min-height: 2.6em;
}
.arc-sub {
  font-size: 0.83rem;
  color: #6b7280;
  line-height: 1.45;
  margin-top: auto;
}
.arc-arrow {
  flex: 0 0 auto;
  display: flex;
  align-items: center;
  justify-content: center;
  color: #b6c0cd;
  font-size: 1.15rem;
}
@media (max-width: 860px) {
  .arc {
    gap: 0.35rem;
  }
  .arc-step {
    padding: 0.8rem 0.7rem 0.85rem;
  }
  .arc-label {
    font-size: 0.92rem;
    min-height: 3.9em;
  }
  .arc-sub {
    font-size: 0.78rem;
  }
}
@media (max-width: 560px) {
  .arc {
    flex-direction: column;
    gap: 0.5rem;
  }
  .arc-step {
    padding: 0.9rem 1rem;
  }
  .arc-label {
    font-size: 1rem;
    min-height: 0;
  }
  .arc-sub {
    font-size: 0.83rem;
    margin-top: 0;
  }
  .arc-arrow {
    justify-content: center;
    padding: 0.1rem 0;
  }
}
.project-list {
  display: flex;
  flex-direction: column;
  gap: 0.75rem;
  margin: 1.5rem 0;
}
.project-card {
  padding: 0.9rem 1.1rem;
  border: 1px solid #d8dee6;
  border-left: 3px solid #1a2b4c;
  background: #fff;
  transition: box-shadow 0.2s ease, border-color 0.2s ease;
}
.project-card:hover {
  box-shadow: 0 4px 12px rgba(26,43,76,0.12);
  border-left-color: #3d6fb4;
}
.project-title {
  font-weight: 600;
  font-size: 0.98rem;
  color: #1a2b4c;
  margin-bottom: 0.25rem;
  line-height: 1.35;
}
.project-title a {
  color: inherit;
  text-decoration: none;
}
.project-title a:hover {
  text-decoration: underline;
}
.project-funder {
  font-size: 0.85rem;
  color: #6b7280;
  line-height: 1.4;
}
.join {
  border: 1px solid #d8dee6;
  border-top: 3px solid #1a2b4c;
  border-radius: 6px;
  background: #f7f9fc;
  padding: 1.3rem 1.4rem;
  margin: 1.5rem 0;
}
.join h2 {
  margin-top: 0 !important;
  font-size: 1.25rem;
  color: #1a2b4c;
}
.join p {
  font-size: 0.98rem;
  line-height: 1.65;
}
.role-grid {
  display: flex;
  flex-wrap: wrap;
  gap: 0.6rem;
  margin: 1.1rem 0;
}
.role {
  flex: 1 1 150px;
  min-width: 0;
  background: #fff;
  border: 1px solid #dde3ea;
  border-radius: 5px;
  padding: 0.7rem 0.85rem;
}
.role-name {
  font-size: 0.92rem;
  font-weight: 600;
  color: #1a2b4c;
}
.role-note {
  font-size: 0.85rem;
  color: #6b7280;
  margin-top: 0.15rem;
}
.join-ask {
  font-size: 0.95rem;
  line-height: 1.6;
  margin-bottom: 0;
}
.figure-caption {
  font-size: 0.85rem;
  color: #6b7280;
  text-align: center;
  max-width: 600px;
  margin: 0.6rem auto 2rem;
  line-height: 1.5;
}
</style>

<p class="lede">What we can build with biology is limited by the tools we have. So we build better tools.</p>

The Zhang Lab develops cell-free synthetic biology platforms that draw from the vast diversity of biological machinery and make it programmable. Cell-free gene expression systems are where we build and characterize tools free of the constraints living cells impose.

<p class="lede-test">Then comes the real test: we ship the tools into the wild to find out whether we got it right.</p>

<div class="arc">
  <div class="arc-step">
    <div class="arc-head">
      <div class="arc-num">1</div>
      <img class="arc-icon" src="/images/step-learn.png" alt="A microbe broken open, revealing the machinery inside">
    </div>
    <div class="arc-label">Learn the Machines</div>
    <div class="arc-sub">Draw on machinery from across biology</div>
  </div>
  <div class="arc-arrow">&rarr;</div>
  <div class="arc-step">
    <div class="arc-head">
      <div class="arc-num">2</div>
      <img class="arc-icon" src="/images/step-build.png" alt="A reaction tube with transcription and translation machinery">
    </div>
    <div class="arc-label">Build the Cell-Free Platform</div>
    <div class="arc-sub">Assemble and characterize outside the cell</div>
  </div>
  <div class="arc-arrow">&rarr;</div>
  <div class="arc-step arc-step--final">
    <div class="arc-head">
      <div class="arc-num">3</div>
      <img class="arc-icon arc-icon--ship" src="/images/step-ship.png" alt="A paper plane shipping biological designs into living cells">
    </div>
    <div class="arc-label">Ship the Program</div>
    <div class="arc-sub">Send it into the wild</div>
  </div>
</div>

Our current tool-building efforts target human health, but the tools aren't limited to it. If you see an application we have not thought of, we want to hear about it.

## Questions We Are Working On

<div class="project-list">
  <div class="project-card">
    <div class="project-title"><a href="/projects/cprit-oncogenic-bacteria-colorectal-cancer">Can we detect, eliminate, and reprogram the bacteria that drive colorectal cancer?</a></div>
    <div class="project-funder">Cancer Prevention and Research Institute of Texas (CPRIT), Recruitment of First-Time, Tenure-Track Faculty Members</div>
  </div>
  <div class="project-card">
    <div class="project-title"><a href="/projects/nih-k99-r00-adaptive-phage-framework">Can we build a phage from its genome sequence alone, without a host, fast enough to counter antibiotic resistance?</a></div>
    <div class="project-funder">NIH MOSAIC Pathway to Independence Career Transition Award (K99/R00)</div>
  </div>
</div>

<div class="join">
  <h2>Join Us</h2>
  <p>We welcome researchers from across engineering and the natural sciences. What matters most is intellectual curiosity, creativity, and being a good teammate who collaborates openly with the rest of the lab.</p>
  <div class="role-grid">
    <div class="role">
      <div class="role-name">Postdoctoral scholars</div>
      <div class="role-note">Inquiries welcome</div>
    </div>
    <div class="role">
      <div class="role-name">Graduate students</div>
      <div class="role-note">Ph.D. and master's, any relevant Rice program</div>
    </div>
    <div class="role">
      <div class="role-name">Undergraduate researchers</div>
      <div class="role-note">Inquiries welcome</div>
    </div>
  </div>
  <p class="join-ask">Email me at <strong>yz350[at]rice[dot]edu</strong> with your CV, a brief description of your research interests and career plan, why you are interested in this lab, and contact information for three references. More detail on <a href="/members/Lab-Member/">our philosophy and open positions</a>.</p>
</div>
