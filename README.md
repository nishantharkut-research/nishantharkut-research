<div align="center">
  <h1>Nishant Harkut</h1>
  <p>Applied ML research · Edge intelligence · Reliable evaluation</p>
  <p>
    <a href="https://github.com/nishantharkut">Engineering GitHub</a>
    &nbsp;·&nbsp;
    <a href="https://www.nishantharkut.tech/">Portfolio</a>
    &nbsp;·&nbsp;
    <a href="https://www.linkedin.com/in/nishant-harkut/">LinkedIn</a>
    &nbsp;·&nbsp;
    <a href="mailto:nhnishantharkut@gmail.com">Email</a>
  </p>
</div>

I'm an Information Technology student at IIIT Gwalior, working on applied machine learning and the reliability of experimental results. I am interested in what happens beyond a headline accuracy score: how models behave under resource constraints, distribution shift, numerical conversion, and more demanding evaluation protocols.

This account holds my research implementations, experimental records, and reproducibility material. My [main GitHub account](https://github.com/nishantharkut) is for software engineering and other projects.

## Research projects

### [TinyRF-KD — Tiny neural intrusion detection for WSN/IoT](https://github.com/nishantharkut-research/TinyRF-KD)

How much of a larger intrusion detector's behavior survives compression into a model that can run on a microcontroller?

This study distills a random-forest teacher into small neural students and assesses classification performance alongside probability quality, teacher-response agreement, feature attributions, and fixed-point execution. The repository includes multi-seed experiments, conversion audits, and physical replay on ESP32-C3 and Arduino UNO R4 WiFi boards.

[Research code and results](https://github.com/nishantharkut-research/TinyRF-KD) · [Reproducibility guide](https://github.com/nishantharkut-research/TinyRF-KD/blob/main/REPRODUCIBILITY.md)

### [Covid-RARS — Respiratory-audio model reliability](https://github.com/nishantharkut-research/Covid-RARS)

Do respiratory-audio classifiers remain useful when the evaluation moves beyond a favorable internal split?

This project studies cough, breath, and speech modeling using Coswara, with participant-aware and time-aware evaluation, external cough-only transfer to COUGHVID, calibration checks, and audits for metadata and collection-context shortcuts. The emphasis is on understanding where apparently strong internal performance does **not** generalize.

[Research code and evidence](https://github.com/nishantharkut-research/Covid-RARS) · [Artifact guide](https://github.com/nishantharkut-research/Covid-RARS/blob/main/ARTIFACT.md)

### [UAV-assisted ISAC — Reproduction and learning-based extension](https://github.com/nishantharkut-research/isac-uav)

A work-in-progress study of constrained communication and sensing optimization in hybrid-RIS-assisted UAV systems. The repository separates reproduction of a published baseline from an experimental preference-conditioned deep reinforcement learning extension, with feasibility checks and explicit acceptance criteria.

**Status:** Implementation and verification material is available. Full numerical reproduction and comparative performance claims remain pending.

[Reproduction and extension notes](https://github.com/nishantharkut-research/isac-uav/blob/main/README_FIRST.md)

## Supporting projects and coursework

- **[TinyML IDS Telemetry](https://github.com/nishantharkut-research/TinyML-IDS-Telemetry):** An auditable Kafka, Spark, and Hadoop pipeline for previously recorded microcontroller intrusion-detection telemetry. Developed as IoT and Big Data Management coursework.
- **[IoT Energy Data Pipeline](https://github.com/nishantharkut-research/IoT-Energy-Data-Pipeline):** Reconciliation and correctness checks for smart-meter data processed through distributed batch and streaming systems. Developed as coursework using public HKUST data.

## Research practice

My repositories aim to make it possible to inspect **experimental protocols, code, reported results, and limitations** separately. Where the evidence does not support a deployment, clinical, or numerical superiority claim, the project documentation says so.

Research code and manuscript drafts in these repositories should not be taken to indicate that a paper has been published or accepted. Please refer to each repository for its current scope, dependencies, dataset access rules, and citation information.
