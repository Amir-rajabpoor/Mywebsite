---
layout: default
title: Amir Rajabpoor Alisepahi
---
<style>
  .amir-wrapper {
    max-width: 1050px;
    margin: 0 auto;
    padding: 2rem 1rem 4rem 1rem;
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
    line-height: 1.6;
  }

  .amir-hero {
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    gap: 2rem;
    margin-bottom: 3rem;
  }

  .amir-hero-text {
    flex: 2 1 260px;
  }

  .amir-hero-text h1 {
    margin-top: 0;
    margin-bottom: 0.3rem;
  }

  .amir-hero-text h2 {
    margin-top: 0;
    font-weight: 500;
    font-size: 1.05rem;
    color: #555;
  }

  .amir-hero-tags {
    display: flex;
    flex-wrap: wrap;
    gap: 0.4rem;
    margin: 0.75rem 0 1rem 0;
  }

  .amir-tag {
    font-size: 0.78rem;
    padding: 0.22rem 0.6rem;
    border-radius: 999px;
    border: 1px solid #d0d0d0;
    background: #fafafa;
  }

  .amir-hero-links {
    display: flex;
    flex-wrap: wrap;
    gap: 0.6rem;
    margin-top: 0.5rem;
  }

  .amir-hero-links a {
    font-size: 0.9rem;
    text-decoration: none;
    padding: 0.35rem 0.75rem;
    border-radius: 999px;
    border: 1px solid #007acc;
    color: #007acc;
  }

  .amir-hero-links a.primary-link {
    background: #007acc;
    color: #fff;
  }

  .amir-hero-photo {
    flex: 1 1 220px;
    display: flex;
    justify-content: center;
  }

  .amir-hero-photo img {
    max-width: 260px;
    border-radius: 999px;
    border: 3px solid #eee;
  }

  .amir-nav {
    display: flex;
    flex-wrap: wrap;
    gap: 0.5rem;
    margin: 0 0 2rem 0;
    border-bottom: 1px solid #e0e0e0;
    padding-bottom: 0.75rem;
  }

  .amir-nav a {
    font-size: 0.9rem;
    text-decoration: none;
    padding: 0.3rem 0.8rem;
    border-radius: 999px;
    border: 1px solid #d0d0d0;
    color: #333;
    background: #fafafa;
  }

  .amir-nav a:hover {
    background: #e9f4ff;
    border-color: #007acc;
  }

  .amir-section {
    margin-bottom: 3rem;
  }

  .amir-section h3 {
    margin-top: 0;
    margin-bottom: 0.75rem;
  }

  .amir-columns {
    display: grid;
    grid-template-columns: minmax(0, 3fr) minmax(0, 2fr);
    gap: 1.75rem;
  }

  @media (max-width: 800px) {
    .amir-hero {
      flex-direction: column;
    }
    .amir-columns {
      grid-template-columns: 1fr;
    }
  }

  .amir-highlights ul {
    padding-left: 1.1rem;
    margin-top: 0.2rem;
  }

  /* Tabs */

  .amir-tabs {
    border-radius: 0.75rem;
    border: 1px solid #e0e0e0;
    padding: 1rem;
    background: #fcfcfc;
  }

  .amir-tab-buttons {
    display: flex;
    flex-wrap: wrap;
    gap: 0.5rem;
    margin-bottom: 1rem;
  }

  .amir-tab-button {
    border: 1px solid #d0d0d0;
    background: #f5f5f5;
    border-radius: 999px;
    font-size: 0.85rem;
    padding: 0.3rem 0.9rem;
    cursor: pointer;
  }

  .amir-tab-button.active {
    background: #007acc;
    color: #fff;
    border-color: #007acc;
  }

  .amir-tab-panel {
    display: none;
    font-size: 0.92rem;
  }

  .amir-tab-panel.active {
    display: block;
  }

  /* Figures */

  figure.amir-figure {
    margin: 1rem 0;
    text-align: center;
  }

  figure.amir-figure img {
    max-width: 100%;
    border-radius: 0.5rem;
    border: 1px solid #e0e0e0;
  }

  figure.amir-figure figcaption {
    font-size: 0.8rem;
    color: #555;
    margin-top: 0.4rem;
  }

  /* Lists */

  .amir-list-tight {
    padding-left: 1.1rem;
    margin-top: 0.2rem;
  }

  .amir-list-tight li {
    margin-bottom: 0.2rem;
  }

  /* Small caps heading label */

  .amir-label {
    text-transform: uppercase;
    letter-spacing: 0.08em;
    font-size: 0.7rem;
    color: #888;
  }
</style>

<div class="amir-wrapper">

  <!-- HERO -->

  <div class="amir-hero">
    <div class="amir-hero-text">
      <div class="amir-label">Profile</div>
      <h1>Amir Rajabpoor Alisepahi</h1>
      <h2>Ph.D. Researcher · Mechanical & Acoustic Metamaterials · University of Vermont</h2>

      <div class="amir-hero-tags">
        <span class="amir-tag">Mechanical / Phononic Metamaterials</span>
        <span class="amir-tag">Wave Propagation & Topological States</span>
        <span class="amir-tag">FEM & Laser Vibrometry</span>
        <span class="amir-tag">Complex Systems & Data Science</span>
        <span class="amir-tag">NSF I-Corps Innovation</span>
      </div>

      <p>
        I design and study mechanical and acoustic metamaterials that control how waves move—
        from topological edge states in phononic crystals to data-driven models of complex
        structures. My work integrates analytical modeling, finite element simulations, and
        3D-printed experiments to connect fundamental mechanics with real engineering applications.
      </p>

      <div class="amir-hero-links">
        <a class="primary-link" href="#research">See my research</a>
        <a href="#publications">Publications</a>
        <a href="#projects">Data & projects</a>
        <a href="mailto:amir.rajabpoor@uvm.edu">Email</a>
        <!-- Add your own links here -->
        <!-- <a href="YOUR_CV_PDF_URL">CV (PDF)</a> -->
        <!-- <a href="YOUR_SCHOLAR_URL">Google Scholar</a> -->
        <!-- <a href="YOUR_LINKEDIN_URL">LinkedIn</a> -->
      </div>
    </div>

    <div class="amir-hero-photo">
      <img src="ammmm.png" alt="Portrait of Amir Rajabpoor Alisepahi" />
    </div>
  </div>

  <!-- TOP NAV -->

  <nav class="amir-nav">
    <a href="#about">About</a>
    <a href="#research">Metamaterials & Research</a>
    <a href="#projects">Data & Projects</a>
    <a href="#publications">Publications</a>
    <a href="#experience">Experience</a>
    <a href="#skills">Skills</a>
    <a href="#education">Education</a>
  </nav>

  <!-- ABOUT + HIGHLIGHTS -->

  <section id="about" class="amir-section">
    <div class="amir-columns">
      <div>
        <div class="amir-label">About</div>
        <h3>What I work on</h3>
        <p>
          I am a Ph.D. candidate in Mechanical Engineering at the University of Vermont, focusing on
          <strong>mechanical and phononic metamaterials, topological phononic band structures, and wave propagation</strong>.
          I build and analyze lattices with long-range couplings, in-gap edge and domain-wall states, and
          nonlinear effects—then validate them with 3D-printed experiments and laser vibrometry.
        </p>
        <p>
          Alongside metamaterials, I hold a graduate certificate in
          <strong>Complex Systems and Data Science</strong>, using machine learning and statistical modeling to study
          complex physical and environmental systems. I am especially interested in translational directions such as
          <strong>semiconductor heat management, structural health monitoring, and acoustic/thermal control</strong>.
        </p>
      </div>
      <div class="amir-highlights">
        <div class="amir-label">Highlights</div>
        <h3>Snapshot</h3>
        <ul class="amir-list-tight">
          <li>First-author work in <em>Communications Physics</em> and <em>Crystals</em> on topological and long-range phononic lattices.</li>
          <li>Hands-on experimental work: 3D-printed metamaterial prototypes + laser vibrometer measurements.</li>
          <li>Certificate in Complex Systems & Data Science (UVM) with projects in ML, spatial statistics, and NLP.</li>
          <li>NSF I-Corps–funded team exploring phononic/thermal metamaterials for semiconductor heat management.</li>
        </ul>

        <figure class="amir-figure">
          <img src="C1.jpg" alt="UVM Certificate in Complex Systems and Data Science" />
          <figcaption>Graduate Certificate in Complex Systems &amp; Data Science, University of Vermont.</figcaption>
        </figure>
      </div>
    </div>
  </section>

  <!-- RESEARCH: TABS -->

  <section id="research" class="amir-section">
    <div class="amir-label">Research</div>
    <h3>Metamaterials, Wave Control & Topological Phononics</h3>

    <div class="amir-tabs">
      <div class="amir-tab-buttons">
        <button class="amir-tab-button active" data-tab="meta">Mechanical / Phononic Metamaterials</button>
        <button class="amir-tab-button" data-tab="topo">Topology & Long-Range Coupling</button>
        <button class="amir-tab-button" data-tab="exp">Experiments & Figures</button>
      </div>

      <div class="amir-tab-panel active" id="tab-meta">
        <p>
          I design periodic and quasi-periodic mechanical lattices that manipulate elastic and acoustic waves across
          a wide range of frequencies. This includes:
        </p>
        <ul class="amir-list-tight">
          <li>Phononic crystals with engineered bandgaps for vibration isolation and wave filtering.</li>
          <li>Mechanical metamaterials that guide waves along designed paths or localize energy at interfaces.</li>
          <li>Nonlinear and amplitude-dependent wave phenomena in discrete and continuum systems.</li>
        </ul>
        <p>
          Tools: analytical derivations (e.g., dispersion relations, nonlocal models), finite element analysis
          (COMSOL, MATLAB), and reduced-order models to connect design parameters with band structures.
        </p>
      </div>

      <div class="amir-tab-panel" id="tab-topo">
        <p>
          A large part of my work focuses on <strong>topological phononic band structures</strong> and on how going beyond
          nearest-neighbor interactions changes the usual picture. Recent topics include:
        </p>
        <ul class="amir-list-tight">
          <li>
            Breakdown of conventional winding-number calculations in 1D lattices with interactions beyond nearest neighbors.
          </li>
          <li>
            In-gap edge and domain-wall states in strongly perturbed Su–Schrieffer–Heeger (SSH)-type phononic lattices.
          </li>
          <li>
            Exploring how symmetry, disorder, and coupling range affect robustness of localized edge modes.
          </li>
        </ul>
        <p>
          These studies bridge rigorous topological analysis with realistic mechanical architectures that can be
          fabricated and tested in the lab.
        </p>
      </div>

      <div class="amir-tab-panel" id="tab-exp">
        <p>
          I close the loop between modeling and experiment using 3D-printed structures and full-field measurements:
        </p>
        <ul class="amir-list-tight">
          <li>Design and fabrication of mechanical lattices and metamaterial beams.</li>
          <li>Laser vibrometer measurements to map mode shapes and verify localized states.</li>
          <li>Comparison of measured dispersion with FEM and analytical predictions.</li>
        </ul>

        <figure class="amir-figure">
          <img src="P3.png" alt="Phonon dispersion of graphene-like system at multiple temperatures" />
          <figcaption>
            Example dispersion analysis: temperature-dependent phonon band structures from multiscale simulations.
          </figcaption>
        </figure>
      </div>
    </div>
  </section>

  <!-- DATA / PROJECTS: TABS WITH FIGURES -->

  <section id="projects" class="amir-section">
    <div class="amir-label">Data & Complex Systems</div>
    <h3>Data-Driven Engineering & Applied ML Projects</h3>

    <p>
      Through the Complex Systems &amp; Data Science program and independent work, I apply machine learning
      and statistical modeling to engineering, environmental, and social-data problems. Below are a few examples.
    </p>

    <div class="amir-tabs">
      <div class="amir-tab-buttons">
        <button class="amir-tab-button active" data-tab="ds-ml">ML & Prediction</button>
        <button class="amir-tab-button" data-tab="ds-spatial">Spatial & Spatio-Temporal Modeling</button>
        <button class="amir-tab-button" data-tab="ds-nlp">Text & Social Data</button>
      </div>

      <div class="amir-tab-panel active" id="tab-ds-ml">
        <ul class="amir-list-tight">
          <li><strong>Predicting Soil Parameters Using Counter-Propagation Neural Networks</strong> – Built models to infer geotechnical soil properties from limited measurements.</li>
          <li><strong>Predicting Car Accident Severity in Vermont</strong> – Classified crash severity using environmental, road, and temporal features.</li>
          <li><strong>Battery-Bus Design Project</strong> – Contributed to energy-efficiency and structural considerations in an electric bus design.</li>
        </ul>

        <figure class="amir-figure">
          <img src="Splitted_OR10_Prediction%2Btest.jpg" alt="Scatter plot of ML model predictions vs. test data" />
          <figcaption>
            Example ML output: multi-class prediction performance for a counter-propagation neural-network model.
          </figcaption>
        </figure>
      </div>

      <div class="amir-tab-panel" id="tab-ds-spatial">
        <ul class="amir-list-tight">
          <li><strong>Spatio-Temporal Modeling of Malaria Prevalence</strong> – Used R-INLA and SPDE methods to capture spatial structure and temporal trends.</li>
          <li><strong>Impact of Boundary Conditions on Composite Skew Nanoplates</strong> – Investigated frequency shifts using GDQ and FEM frameworks.</li>
          <li><strong>Elastic-Plastic Buckling of Circular Plates with Variable Thickness</strong> – Modeled stability limits under different loading and geometry configurations.</li>
        </ul>
      </div>

      <div class="amir-tab-panel" id="tab-ds-nlp">
        <ul class="amir-list-tight">
          <li><strong>Quantifying Antisemitism on Twitter</strong> – Explored annotation schemes and NLP pipelines for hate-speech classification.</li>
        </ul>
        <p>
          These projects sharpen my ability to combine domain knowledge in mechanics with modern data science, using
          tools such as Python, R, TensorFlow, PyTorch, and advanced Bayesian methods.
        </p>
      </div>
    </div>
  </section>

  <!-- PUBLICATIONS -->

  <section id="publications" class="amir-section">
    <div class="amir-label">Selected Work</div>
    <h3>Publications</h3>
    <p>Representative publications (first author unless otherwise noted):</p>
    <ul class="amir-list-tight">
      <li>
        Rajabpoor Alisepahi, A.; Ma, J. <strong>In-Gap Edge and Domain-Wall States in Largely Perturbed Phononic Su–Schrieffer–Heeger Lattices.</strong>
        <em>Crystals</em>, 2024, 14, 102.
      </li>
      <li>
        Rajabpoor Alisepahi, A., Sarkar, S., Sun, K. et al.
        <strong>Breakdown of Conventional Winding Number Calculation in One-Dimensional Lattices with Interactions Beyond Nearest Neighbors.</strong>
        <em>Communications Physics</em> 6, 334 (2023).
      </li>
      <li>
        S.M. Mousavi Janbeh Sarayi, A. Rajabpoor Alisepahi, A. Bahrami.
        <strong>Wave Analysis of Thick Rectangular Graphene Sheets: Thickness and Small-Scale Effects on Natural and Bifurcation Frequencies.</strong>
        <em>Sustainability</em> 14(19), 12329 (2022).
      </li>
      <li>
        Daneshmehr, A., A. Rajabpoor, and A. Hadi.
        <strong>Size-Dependent Free Vibration Analysis of Nanoplates Made of Functionally Graded Materials Based on Nonlocal Elasticity Theory with High-Order Theories.</strong>
        <em>International Journal of Engineering Science</em>, 2015.
      </li>
      <li>
        Daneshmehr, A.R., M. Mohammad Abadi, and A. Rajabpoor.
        <strong>Thermal Effect on Static Bending, Vibration, and Buckling of Reddy Beam Based on Modified Couple-Stress Theory.</strong>
        <em>Applied Mechanics and Materials</em>, 2013.
      </li>
    </ul>
    <p style="font-size:0.9rem;">
      For a complete and up-to-date list of publications, please see my Google Scholar profile.
    </p>
  </section>

  <!-- EXPERIENCE -->

  <section id="experience" class="amir-section">
    <div class="amir-label">Experience</div>
    <h3>Professional & Academic Experience</h3>

    <h4>University of Vermont – Research Assistant</h4>
    <p><em>Jan 2022 – Present · Burlington, VT</em></p>
    <ul class="amir-list-tight">
      <li>Develop analytical and numerical models for mechanical and phononic metamaterials, including lattices with long-range coupling and localized edge states.</li>
      <li>Design and fabricate 3D-printed metamaterial structures; perform vibrational analysis using laser vibrometry and compare with FEM/analytical predictions.</li>
      <li>Serve as Teaching Assistant for <em>Energy Methods in Solid Mechanics</em> and mentor undergraduate researchers in modeling and experimentation.</li>
    </ul>

    <h4>FELEZ TABAN Construction Co. – Mechanical Engineer</h4>
    <p><em>Mar 2016 – Dec 2021</em></p>
    <ul class="amir-list-tight">
      <li>Managed production-line operations, equipment monitoring, and safety training for mechanical systems.</li>
      <li>Coordinated with suppliers and contractors on material specifications, pricing, and inventory / cost-control programs.</li>
      <li>Prepared isometric drawings and assisted in mechanical design, troubleshooting, and field issue resolution.</li>
    </ul>

    <h4>University of Tehran – Teaching Assistant (Workshop Tools)</h4>
    <p><em>Feb 2014 – Feb 2016</em></p>
    <ul class="amir-list-tight">
      <li>Prepared teaching materials and safety instructions for hands-on mechanical workshops.</li>
      <li>Trained students on CNC machines and machining processes; supported practical projects and lab exercises.</li>
    </ul>

    <h4>Talks & Presentations</h4>
    <ul class="amir-list-tight">
      <li>Poster Presentation – Structural Health Monitoring, Fall 2021.</li>
      <li><em>Topological Phononic Crystal</em> – Structural Health Monitoring, Fall 2021.</li>
    </ul>
  </section>

  <!-- SKILLS -->

  <section id="skills" class="amir-section">
    <div class="amir-label">Capabilities</div>
    <h3>Skills & Tools</h3>

    <div class="amir-columns">
      <div>
        <h4>Modeling & Simulation</h4>
        <ul class="amir-list-tight">
          <li>Finite Element Methods: COMSOL, Ansys, Abaqus, custom MATLAB/Python codes.</li>
          <li>Band-structure and dispersion analysis for periodic lattices and phononic crystals.</li>
          <li>Nonlocal elasticity, couple-stress theories, and GDQ-based formulations.</li>
          <li>Molecular dynamics simulations and phonon analysis (e.g., LAMMPS).</li>
        </ul>

        <h4>Experimental & Prototyping</h4>
        <ul class="amir-list-tight">
          <li>Laser vibrometer measurements of metamaterial samples.</li>
          <li>3D printing and prototyping of mechanical and acoustic lattices.</li>
          <li>Mechanical equipment design; interpreting standards, specifications, and drawings.</li>
        </ul>
      </div>

      <div>
        <h4>Programming & Data Science</h4>
        <ul class="amir-list-tight">
          <li>MATLAB, Python; numerical methods for PDEs and eigenproblems.</li>
          <li>TensorFlow, PyTorch, scikit-learn for supervised and unsupervised ML.</li>
          <li>R, R-INLA, SPDE methods for spatial and spatio-temporal modeling.</li>
        </ul>

        <h4>Domain Knowledge</h4>
        <ul class="amir-list-tight">
          <li>Mechanical and phononic metamaterials; wave propagation and vibration.</li>
          <li>MEMS & NEMS concepts; nano- and micro-scale structural behavior.</li>
          <li>Industrial drawing, CNC machining, and workshop practices.</li>
        </ul>
      </div>
    </div>
  </section>

  <!-- EDUCATION -->

  <section id="education" class="amir-section">
    <div class="amir-label">Background</div>
    <h3>Education</h3>

    <h4>Ph.D. in Mechanical Engineering – University of Vermont</h4>
    <p><em>Feb 2022 – Present</em></p>
    <p>
      Research focus: wave propagation and topological phenomena in acoustic/mechanical metamaterials;
      phononic crystals, edge and domain-wall states, long-range coupling, and nonlinear effects.
    </p>

    <h4>M.Sc. in Mechanical Engineering – University of Tehran</h4>
    <p><em>Feb 2014 – Feb 2016</em></p>
    <p>
      Thesis: vibration and buckling analysis of functionally graded nanoplates based on nonlocal elasticity and
      high-order plate theories.
    </p>

    <h4>B.Sc. in Mechanical Engineering – Razi University of Kermanshah</h4>
    <p><em>Sep 2006 – Sep 2011</em></p>
    <p>
      Project: effect of low-velocity impact on functionally graded circular plates.
    </p>
  </section>

</div>

<script>
  // Simple tab logic
  document.addEventListener("DOMContentLoaded", function () {
    function setupTabGroup(wrapper) {
      const buttons = wrapper.querySelectorAll(".amir-tab-button");
      const panels = wrapper.querySelectorAll(".amir-tab-panel");

      buttons.forEach(function (btn) {
        btn.addEventListener("click", function () {
          const tab = btn.getAttribute("data-tab");

          buttons.forEach(function (b) {
            b.classList.remove("active");
          });
          panels.forEach(function (p) {
            p.classList.remove("active");
          });

          btn.classList.add("active");
          const panel = wrapper.querySelector("#tab-" + tab);
          if (panel) {
            panel.classList.add("active");
          }
        });
      });
    }

    document.querySelectorAll(".amir-tabs").forEach(setupTabGroup);
  });
</script>

Create new homepage layout

