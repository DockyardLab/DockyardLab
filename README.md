# DockyardLab

I build source-available Google Cloud infrastructure for the Unbound Maker
Community, connecting technical research, community publishing, and hands-on
AI projects.

## From Research to Community Publishing

**Discover technical signals -> human editorial review -> publish reusable community knowledge.**

I built two complementary projects around this workflow.

### Strategic Signal Scanner

[Repository](https://github.com/unboundmakers/strategic-signal-scanner) |
[Architecture & Case Study](https://github.com/unboundmakers/strategic-signal-scanner/blob/main/docs/GOOGLE_CLOUD_CASE_STUDY.md)

A human-in-the-loop research pipeline that collects technical sources,
normalizes and deduplicates them, and uses Gemini on Vertex AI to prepare
research candidates.

Editorial selection and final publication remain human-led.

The reference implementation uses Cloud Run Jobs, Gemini on Vertex AI, and
Cloud Storage.

### Unbound Community Platform

[Repository](https://github.com/unboundmakers/unbound-community-platform) |
[Architecture & Case Study](https://github.com/unboundmakers/unbound-community-platform/blob/main/docs/GOOGLE_CLOUD_CASE_STUDY.md)

Google Cloud infrastructure references for community publishing and project
documentation.

The repository includes a Firestore document adapter, Firebase Hosting and
Cloud Run integration templates, Cloud Build and Artifact Registry configuration,
and guidance for IAM, ADC, and Secret Manager.

## Community

These projects support the Unbound Maker Community, where women, young people,
and cross-disciplinary creators explore AI, smart hardware, robotics, design,
and education.

[Read Signal Scanner](https://unboundmakers.github.io/signal-scanner/)
