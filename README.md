# Agent AAS Demo Repo

## GitHub Pages

URL: https://mhuynh-agentsonly.github.io/agent-aas/agent-portal-coaching-idcompare.html

**ID comparison only (current MVP).** Before every test, the agent photographs the same type of ID they gave at onboarding. There's no selfie or liveness check. During the test, the camera takes a few photos at random times without telling the agent. The face match happens after the test. If identity can't be confirmed, the result becomes "Invalid" and the test can't be retaken.

URL: https://mhuynh-agentsonly.github.io/agent-aas/agent-portal-coaching-proctoring.html

**ID + selfie check (earlier direction, kept for reference).** Before the first test, the agent takes a photo of their ID and a live selfie (look straight, then left, then right). The face is matched to the ID right away, so the agent can't start the test until they're verified. After 3 failed tries, tests are locked. On later tests, a quick face check in the camera setup replaces the selfie. During the test, the camera, mic and screen share stay on the whole time. This direction may come back, but it's not the MVP.

> Main difference: the ID + selfie version checks the face against the ID **before** the test starts; the MVP checks it **after** the test.

URL: https://mhuynh-agentsonly.github.io/agent-aas/agent-review-multimodal-v2.html

URL: https://mhuynh-agentsonly.github.io/agent-aas/agent-sim-flow.html

URL: https://mhuynh-agentsonly.github.io/agent-aas/index.html

## About

This repo contains sim demo prototypes.
Agent AAS Github Pages: https://mhuynh-agentsonly.github.io/agent-aas/index.html

Please note:
- Files in the `archive/` folder are deprecated
- They are kept only for reference
- Please do not use them as the source of truth for implementation

For the latest demos, please refer to the files in the root directory and the links in `index.html`.
