# DockyardLab

I build AI-assisted research workflows and Google Cloud infrastructure for
Unbound Maker Community. My work connects technical research, community
publishing, workshops, and hands-on AI, smart hardware, and robotics projects.

## From Research to Community Publishing

**Discover technical signals -> human topic selection and editing -> publish for the community.**

I built two complementary projects around this workflow:

### Strategic Signal Scanner

[Repository](https://github.com/unboundmakers/strategic-signal-scanner) |
[Architecture and case study](https://github.com/unboundmakers/strategic-signal-scanner/blob/main/docs/GOOGLE_CLOUD_CASE_STUDY.md)

A research pipeline for collecting technical material, normalizing and
deduplicating it, and using model-assisted scoring to prepare research
candidates. I select topics and edit the final content.

The public implementation includes Cloud Run Jobs orchestration, Gemini via
Vertex AI, Cloud Storage state persistence, and an optional DeepSeek adapter.

### Unbound Community Platform

[Repository](https://github.com/unboundmakers/unbound-community-platform) |
[Architecture and case study](https://github.com/unboundmakers/unbound-community-platform/blob/main/docs/GOOGLE_CLOUD_CASE_STUDY.md)

Publishing infrastructure that carries research and project experience beyond
a single community event. The public repository contains the generic Google
Cloud integration layer rather than the full community application.

It includes a Firestore document adapter, Firebase Hosting and Cloud Run
integration templates, Cloud Build and Artifact Registry configuration, and
guidance for ADC, IAM, and Secret Manager integration.

## Community

Through [Unbound Maker Community](https://github.com/unboundmakers), I work with
women, young people, and cross-disciplinary creators to turn ideas into AI,
hardware, and robotics projects.

[Read Signal Scanner](https://unboundmakers.github.io/signal-scanner/)
