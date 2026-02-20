Terrain-Driven Egocentric Walking Dataset — Santa Marta Onward
Overview
This dataset captures long-horizon egocentric locomotion, beginning in Santa Marta, Colombia, using a triggered, environment- and state-driven capture paradigm. Videos are recorded only when meaningful transitions occur, where allowed due to battery, and consistently from a forward-facing, stable POV.
All footage is silent, providing clean visual input optimized for computer vision, machine learning, and robotics applications.
The dataset provides continuous real-world sequences of human traversal across heterogeneous terrains, capturing dynamic environmental interactions, biomechanical adaptation, and context-dependent locomotor decision-making. Segments are GPS-anchored to enable geospatial correlation, trajectory analysis, and mapping without revealing sensitive or private locations.
Capture Paradigm
Continuous expeditional capture: The subject progresses daily, generating temporally coherent sequences suitable for long-horizon modeling.
Trigger-based acquisition: Video segments are initiated by:
Terrain topology and geometric transitions (flat → incline → decline, path curvature, obstacle density)
Surface composition variability (paved, dirt, sand, rocky, loose aggregates)
Meteorological perturbations (precipitation, wind, fog, temperature extremes)
Biophysical state shifts (subjective fatigue, heat stress, gait adaptation)
Infrastructure encounters (settlements, bridges, signage, anthropogenic obstacles)
Sparse, opportunistic capture: Recording occurs where permitted by power availability, naturally clustering footage around highly informative environmental and physiological events.
Metadata
Externally logged metadata preserves ground-truth context without contaminating the visual data stream.
Supports optional GPS anchoring for each segment, enabling geospatial analysis, path reconstruction, and trajectory studies.
Provides descriptors for environmental conditions, terrain typology, infrastructure context, and human state variables.
Supports algorithmic supervision, multi-modal correlation, and domain adaptation experiments.
Storage and Integrity
Videos are stored both locally on a desktop and in cloud storage in their original, unaltered format.
No compression, encoding, editing, or modification is applied — what is captured is exactly what is stored.
Verification workflow ensures all video files are complete, playable, and fully intact prior to storage.
Metadata is maintained separately from video files, preserving authenticity and integrity while enabling geospatial analysis.
Intended Applications
This dataset is designed for high-value AI, robotics, and human factors applications, including:
Egocentric perception & navigation: Long-horizon trajectory modeling, SLAM evaluation, path prediction, and scene understanding.
Human locomotion & biomechanics modeling: Fatigue adaptation, gait variability, and energy expenditure analysis.
Robotics & autonomous systems: Real-world terrain traversal, obstacle negotiation, and adaptive planning.
Environmental and geospatial research: Terrain usage patterns, infrastructure impact studies, and anthropogenic interaction modeling.
Key Technical Features
Forward-facing, egocentric perspective: Ensures consistent visual frame-of-reference for downstream CV/ML pipelines.
Sparse, high-information capture: Prioritizes segments with maximal environmental and physiological variance.
Continuous, long-horizon sequences: Enables temporal modeling, recurrent learning, and trajectory analysis.
GPS-anchored segments: Supports geospatial correlation, trajectory reconstruction, and mapping studies.
Heterogeneous terrain and environmental representation: Supports robustness testing, domain generalization, and multi-condition evaluation.
Silent capture: Eliminates audio confounds and privacy issues, enhancing usability for vision-based AI systems.
Unaltered storage: Raw, uncompressed files maintain complete fidelity and trustworthiness.
Notes
Environmental conditions are naturally variable and not artificially controlled.
Dataset reflects a single-subject, first-person perspective, capturing authentic human locomotion.
Sparse capture reflects informational prioritization, not continuous coverage, emphasizing signal over redundant frames.
