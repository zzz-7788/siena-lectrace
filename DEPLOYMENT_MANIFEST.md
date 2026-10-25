# Deployment manifest

Source static build: `SienaDetection_LecTrace_V1/_site/`

Included directories and files:

- `index.html` — static site entry point.
- `assets/` — bundled JavaScript, stylesheet, and local font assets.
- `traces/index.json` — available presentation trace index.
- `traces/detection_lectrace.json` — frozen trace for the approved presentation.
- `README.md` and `.nojekyll` — deployment documentation and GitHub Pages configuration.

Excluded by design:

- Python source, local environments, and build caches.
- Raw EEG data, labels, annotations, and patient files.
- Model checkpoints and training/evaluation artifacts.
- Local backups, audit files, project source, and credentials.

This deployment directory is separate from the research project and contains no editable scientific source files.
