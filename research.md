---
layout: default
title: Research
permalink: /research/
---
<div class="page research-page">
<p class="eyebrow">RESEARCH</p>
# Research at MAS Lab

<p class="research-lead"><strong>Medical imaging is the core of MAS Lab.</strong> We engineer biomedical imaging systems that use <strong>ultrasound, light, and radiation</strong> to visualize anatomy, physiology, and disease-related changes. We develop the entire pipeline—from physical measurements and acquisition hardware to image reconstruction, AI, and quantitative biomarkers. We also explore ultrasound stimulation and image-guided therapeutic applications.</p>

<p class="ko-summary" lang="ko"><strong>MAS Lab의 핵심 연구 분야는 의료영상입니다.</strong> 초음파·광음향·방사선 기반 영상 시스템을 개발하여 몸속 구조와 기능을 관찰하고, AI·영상처리를 활용해 질환의 진행과 치료 반응을 정량적으로 분석합니다. 연구의 중심은 영상물리·계측·시스템·신호처리이며, 이를 초음파 자극과 영상 기반 치료·재활 모니터링 분야로 확장합니다.</p>
<div class="research-pathway" aria-label="MAS Lab research approach"><span>Biomedical imaging systems</span><b aria-hidden="true">→</b><span>AI &amp; quantitative analysis</span><b aria-hidden="true">→</b><span>Disease &amp; treatment monitoring</span></div>

<section class="research-band">
  <div class="research-band-media">
    <img src="{{ '/assets/img/research/dlpact-wholebody.jpg' | relative_url }}" alt="3D whole-body photoacoustic imaging">
  </div>
  <div class="research-band-copy">
    <span class="eyebrow">01 · PHOTOACOUSTIC & ULTRASOUND IMAGING</span>
    <h2>Photoacoustic &amp; Ultrasound Imaging</h2>
    <p>We develop biomedical imaging systems that combine the strengths of light and ultrasound. Photoacoustic imaging uses light absorption to generate ultrasound signals, while conventional ultrasound images tissue structure through echoes. Our work includes high-speed 3D imaging, vascular visualization, oxygenation measurement, image reconstruction, and hardware optimization for preclinical and translational research.</p>
    <p class="research-ko" lang="ko"><strong>학생 연구 예시:</strong> 광음향/초음파 시스템 제작, 3D 재구성, 혈관 영상화, 산소포화도 분석, 고속 스캐닝, 멀티모달 영상, 영상 품질 및 시스템 최적화.</p>
  </div>
</section>

<section class="research-band reverse">
  <div class="research-band-media">
    <img src="{{ '/assets/img/research/xfelam-system.jpg' | relative_url }}" alt="XFEL-induced acoustic imaging system">
  </div>
  <div class="research-band-copy">
    <span class="eyebrow">02 · RADIATION-BASED IMAGING</span>
    <h2>Radiation-Induced Acoustic Imaging &amp; Dosimetry</h2>
    <p>Radiation can generate weak ultrasound waves when its energy is absorbed by a material or tissue. We investigate how to detect and reconstruct these signals to visualize radiation energy deposition and estimate delivered dose. This work includes X-ray-induced acoustic imaging, radiotherapy dosimetry, synchronized sensor systems, physics-based simulation, and reconstruction of low-SNR signals.</p>
    <p class="research-ko" lang="ko"><strong>학생 연구 예시:</strong> 방사선-음향 신호 검출, X-ray/radiotherapy 실험, 선량-음향 신호 calibration, Monte Carlo/음향 시뮬레이션, 저 SNR 신호 향상, 3D 선량 영상화.</p>
  </div>
</section>

<section class="research-band">
  <div class="research-band-media dual-media">
    <img src="{{ '/assets/img/research/csf-flow.jpg' | relative_url }}" alt="CSF dynamics monitored by photoacoustic imaging">
    <img src="{{ '/assets/img/research/brain-angiogram-so2.jpg' | relative_url }}" alt="Whole-brain angiogram and oxygen saturation">
  </div>
  <div class="research-band-copy">
    <span class="eyebrow">03 · QUANTITATIVE IMAGING BIOMARKERS</span>
    <h2>Disease Monitoring &amp; Quantitative Biomarkers</h2>
    <p>Medical images are most valuable when they provide measurements, not only pictures. We develop image-processing and AI-based methods to quantify blood vessels, oxygenation, cerebrospinal-fluid transport, tumors, and the distribution of drugs or contrast agents. By repeating measurements over time, we study disease progression, treatment response, and recovery.</p>
    <p class="research-ko" lang="ko"><strong>응용 방향:</strong> 뇌혈관·뇌척수액, 종양 미세환경, 약물·조영제 biodynamics, 질환 진행, 치료 반응을 반복 측정하고 vascular, oxygenation, molecular, fluid-dynamic 지표를 정량 바이오마커로 정의·검증합니다.</p>
  </div>
</section>

<section class="research-band reverse">
  <div class="research-band-media">
    <img class="ultrasound-visual" src="{{ '/assets/img/research/ultrasound-stimulation-therapy.jpg' | relative_url }}" alt="Conceptual focused ultrasound stimulation and therapy with quantitative biological response monitoring">
  </div>
  <div class="research-band-copy">
    <span class="eyebrow">04 · ULTRASOUND THERAPEUTICS</span>
    <h2>Ultrasound Stimulation &amp; Therapy</h2>
    <p>Beyond imaging, we investigate ultrasound-based stimulation and therapy. We design and optimize ultrasound frequency, pressure, pulse patterns, and exposure conditions for applications such as neuromodulation and rehabilitation. Imaging and physiological measurements help us evaluate how biological systems respond to stimulation.</p>
    <p class="research-ko" lang="ko"><strong>학생 연구 예시:</strong> 초음파 주파수·강도·펄스 조건 최적화, 신경자극 및 therapeutic ultrasound 실험, 자극 전후 생체 반응 영상화, 재활 관련 기능 변화의 정량 평가, image-guided stimulation.</p>
  </div>
</section>

<section class="representative-work" style="margin-top: 2.5rem;">
  <div class="section-head">
    <div>
      <p class="eyebrow">CROSS-CUTTING METHODS</p>
      <h2>AI &amp; Computational Imaging</h2>
    </div>
  </div>
  <p>AI is not treated as a separate research destination in MAS Lab. Instead, model-based reconstruction, deep learning, physics-informed learning, segmentation, multimodal registration, uncertainty estimation, and GPU computing are used across all four research directions to improve sensitivity, speed, robustness, and quantitative reliability.</p>
  <p class="research-ko" lang="ko">AI는 독립적인 연구 목적이라기보다 방사선 유도 음향영상, 광음향·초음파 영상, 바이오마커 정량화, 초음파 자극 연구 전반을 고도화하는 공통 방법론으로 활용합니다. 물리 모델과 AI를 결합하여 저 SNR, 제한 시야, inverse problem, 자동 정량화 문제를 해결합니다.</p>
</section>

<section id="representative-work" class="representative-work">
  <div class="section-head">
    <div>
      <p class="eyebrow">REPRESENTATIVE WORK</p>
      <h2>Selected Research Highlights</h2>
    </div>
  </div>
  <p class="muted">The images below are reproduced or adapted from representative publications and are linked to the original articles.</p>

  <div class="work-grid">
    <article class="work-card">
      <img src="{{ '/assets/img/research/xfelam-resolution.jpg' | relative_url }}" alt="XFEL induced acoustic microscopy">
      <div class="work-body">
        <span class="work-tag">RADIATION ACOUSTICS · 2024</span>
        <h3>X-ray free-electron laser induced acoustic microscopy</h3>
        <p>XFEL excitation enables micron-scale X-ray-induced acoustic microscopy and demonstrates the feasibility of a new X-ray acoustic regime.</p>
        <a href="https://doi.org/10.1016/j.pacs.2024.100587" target="_blank" rel="noopener">Photoacoustics ↗</a>
        <small>Figure reproduced from Choi et al., <em>Photoacoustics</em> 35, 100587 (2024), CC BY-NC-ND 4.0.</small>
      </div>
    </article>

    <article class="work-card">
      <img src="{{ '/assets/img/research/xact-insitu.jpg' | relative_url }}" alt="In situ X-ray induced acoustic computed tomography">
      <div class="work-body">
        <span class="work-tag">RADIATION ACOUSTICS · 2022</span>
        <h3>In situ X-ray-induced acoustic computed tomography</h3>
        <p>Contrast-enhanced XACT demonstrates volumetric in situ small-animal imaging and establishes a route toward biomedical X-ray acoustic applications.</p>
        <a href="https://doi.org/10.1364/OL.447618" target="_blank" rel="noopener">Optics Letters ↗</a>
        <small>Figure reproduced from Choi et al., <em>Optics Letters</em> 47, 90-93 (2022).</small>
      </div>
    </article>

    <article class="work-card">
      <img src="{{ '/assets/img/research/csf-flow.jpg' | relative_url }}" alt="CSF and glymphatic imaging">
      <div class="work-body">
        <span class="work-tag">BIOAPPLICATION · 2026</span>
        <h3>Photoacoustic monitoring of CSF dynamics and glymphatic function</h3>
        <p>Whole-body PACT tracks CSF transport, anesthesia-dependent efflux, and impaired clearance in an Alzheimer’s disease mouse model.</p>
        <a href="https://doi.org/10.1038/s41467-026-69390-4" target="_blank" rel="noopener">Nature Communications ↗</a>
        <small>Figure adapted from Choi et al., <em>Nature Communications</em> 17, 2677 (2026), CC BY 4.0.</small>
      </div>
    </article>

    <article class="work-card">
      <img src="{{ '/assets/img/research/stroke-so2.jpg' | relative_url }}" alt="Stroke oxygen saturation monitoring">
      <div class="work-body">
        <span class="work-tag">NEUROIMAGING · 2025</span>
        <h3>Early-stage ischemic stroke monitoring</h3>
        <p>Whole-brain PACT visualizes cerebrovascular remodeling and vessel-specific oxygenation changes following photothrombotic stroke.</p>
        <a href="https://doi.org/10.1002/advs.202409361" target="_blank" rel="noopener">Advanced Science ↗</a>
        <small>Figure adapted from Kim et al., <em>Advanced Science</em> 12, 2409361 (2025), CC BY 4.0.</small>
      </div>
    </article>

    <article class="work-card">
      <img src="{{ '/assets/img/research/rotary-wholebody.jpg' | relative_url }}" alt="Multiplane whole-body PACT">
      <div class="work-body">
        <span class="work-tag">IMAGING SYSTEM · 2025</span>
        <h3>Multiplane spectroscopic whole-body PACT</h3>
        <p>Continuous rotary scanning extends tomographic coverage for high-resolution structural, functional, and pharmacokinetic small-animal imaging.</p>
        <a href="https://doi.org/10.1002/lpor.202400672" target="_blank" rel="noopener">Laser &amp; Photonics Reviews ↗</a>
        <div class="work-awards"><span class="pub-badge">Wiley Top Viewed Article 2025</span></div>
        <small>Figure reproduced from Yang et al., <em>Laser &amp; Photonics Reviews</em> 19, 2400672 (2025), CC BY-NC-ND 4.0.</small>
      </div>
    </article>

    <article class="work-card">
      <img src="{{ '/assets/img/research/tumor-progression.jpg' | relative_url }}" alt="Tumor progression monitored with PACT">
      <div class="work-body">
        <span class="work-tag">ONCOLOGY · 2024</span>
        <h3>3D multiparametric PACT of primary and metastatic tumors</h3>
        <p>Longitudinal structural, oxygenation, and pharmacokinetic measurements characterize tumor progression and metastasis in living mice.</p>
        <a href="https://doi.org/10.1021/acsnano.3c12551" target="_blank" rel="noopener">ACS Nano ↗</a>
        <small>Figure reproduced from Kim et al., <em>ACS Nano</em> 18, 18176-18190 (2024), CC BY-NC-ND 4.0.</small>
      </div>
    </article>

    <article class="work-card">
      <img src="{{ '/assets/img/research/hdpact-recovery.jpg' | relative_url }}" alt="Hybrid diffusion enhanced PACT">
      <div class="work-body">
        <span class="work-tag">COMPUTATIONAL IMAGING · 2026</span>
        <h3>Hybrid diffusion model for multiparametric 3D PACT</h3>
        <p>Deep generative reconstruction restores structural and functional information from substantially reduced ultrasound-element sampling.</p>
        <a href="https://doi.org/10.1002/advs.202513624" target="_blank" rel="noopener">Advanced Science ↗</a>
        <small>Figure adapted from Jeong et al., <em>Advanced Science</em> 13, e13624 (2026), CC BY 4.0.</small>
      </div>
    </article>

    <article class="work-card">
      <img src="{{ '/assets/img/research/dlpact-wholebody.jpg' | relative_url }}" alt="Deep learning enhanced whole-body PACT">
      <div class="work-body">
        <span class="work-tag">COMPUTATIONAL IMAGING · 2023</span>
        <h3>Deep learning enhanced multiparametric dynamic volumetric PACT</h3>
        <p>A 3D progressive U-Net recovers limited-view volumetric information and enables high-speed structural, functional, and contrast-enhanced imaging.</p>
        <a href="https://doi.org/10.1002/advs.202202089" target="_blank" rel="noopener">Advanced Science ↗</a>
        <div class="work-awards"><span class="pub-badge">Back Cover</span><span class="pub-badge">Wiley Top Downloaded Article</span></div>
        <small>Figure adapted from Choi et al., <em>Advanced Science</em> 10, 2202089 (2023), CC BY 4.0.</small>
      </div>
    </article>
  </div>
</section>

<section class="collaborators-section" id="collaborators">
  <div class="section-head">
    <div>
      <p class="eyebrow">COLLABORATIVE RESEARCH</p>
      <h2>Research Collaborators &amp; Networks</h2>
    </div>
  </div>
  <p class="collab-intro">Our collaborative work centers on biomedical imaging and its applications, connecting radiology, nuclear medicine, imaging AI, neuroscience, nanotechnology, rehabilitation, and translational science.</p>
  <p class="collab-intro collab-intro-ko" lang="ko">국내외 연구진과의 공동연구를 통해 방사선·음향 계측, 영상 시스템 개발, computational imaging, 전임상·임상 검증, 자극·치료 연구까지 범위를 확장합니다.</p>

  <div class="collab-grid" aria-label="Research collaborator institutions">
    <a class="collab-card collab-stanford" href="https://www.stanford.edu/" target="_blank" rel="noopener">
      <img class="collab-logo" src="{{ '/assets/img/collaborators/stanford-university.png' | relative_url }}" alt="Stanford University logo">
    </a>
    <a class="collab-card collab-postech" href="https://www.postech.ac.kr/" target="_blank" rel="noopener">
      <img class="collab-logo" src="{{ '/assets/img/collaborators/postech.png' | relative_url }}" alt="POSTECH logo">
    </a>
    <a class="collab-card collab-snuh" href="https://www.snuh.org/" target="_blank" rel="noopener">
      <img class="collab-logo" src="{{ '/assets/img/collaborators/snuh.png' | relative_url }}" alt="Seoul National University Hospital logo">
    </a>
    <a class="collab-card collab-cmc" href="https://www.cmcseoul.or.kr/" target="_blank" rel="noopener" aria-label="The Catholic University of Korea Seoul St. Mary's Hospital">
      <img class="collab-logo" src="https://tong.visitkorea.or.kr/cms/resource/24/3464124_image2_1.jpeg" alt="Seoul St. Mary's Hospital logo" loading="lazy">
      <span>Seoul St. Mary's Hospital</span>
    </a>
    <a class="collab-card collab-anam" href="https://anam.kumc.or.kr/" target="_blank" rel="noopener" aria-label="Korea University Anam Hospital">
      <img class="collab-logo" src="https://chblob.icloudhospital.com/thumbnails/Korea-Univ-Anam-Hospital-logo-a9aa061c-aaf0-40fd-8666-57468112ca3c.webp?format=webp&amp;q=75&amp;w=96" alt="Korea University Anam Hospital logo" loading="lazy">
      <span>Korea University Anam Hospital</span>
    </a>
  </div>
  <p class="collab-disclaimer">Institution names indicate research relationships or networks at the project/researcher level and do not imply institutional endorsement.</p>
</section>
</div>