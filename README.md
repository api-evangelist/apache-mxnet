# Apache MXNet (apache-mxnet)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Apache MXNet is a retired deep learning framework (now in the Apache Attic) designed for both efficiency and flexibility. It provided a multi-language API for building and training deep neural networks with support for distributed training, the Gluon high-level API, and deployment on edge devices. MXNet supported Python, Scala, Java, C++, R, Julia, and Perl.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/apache-mxnet/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - AI, Deep Learning, Machine Learning, Neural Networks, Python, Retired

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Apache MXNet
MXNet provides APIs in Python, Scala, Java, C++, R, Julia, and Perl for deep learning model development, with the Gluon high-level API for imperative model building, Symbol/NDArray low-level APIs for efficient computation graphs, and distributed training via Parameter Server and Horovod. Final version is 1.9.1.

**Human URL:** [https://mxnet.apache.org/versions/1.9.1/api](https://mxnet.apache.org/versions/1.9.1/api)

#### Tags:

 - Deep Learning, Distributed Training, Gluon, Python

#### Properties

- [Documentation](https://mxnet.apache.org/versions/1.9.1/api)
- [GettingStarted](https://mxnet.apache.org/versions/1.9.1/get_started)
- [Python SDK (PyPI)](https://pypi.org/project/mxnet/)
- [Scala/Java SDK (Maven)](https://central.sonatype.com/artifact/org.apache.mxnet/mxnet-full_2.12)
- [GitHubRepository](https://github.com/apache/mxnet)

## Common Properties

- [Portal](https://mxnet.apache.org/)
- [GitHubOrganization](https://github.com/apache)
- [GitHubRepository](https://github.com/apache/mxnet)
- [Wiki](https://cwiki.apache.org/confluence/display/MXNET/Apache+MXNet+Home)
- [IssueTracker](https://issues.apache.org/jira/projects/MXNET/issues)
- [MailingList](mailto:dev@mxnet.apache.org)
- [TermsOfService](https://www.apache.org/licenses/LICENSE-2.0)

## Features

| Name | Description |
|------|-------------|
| Hybrid Front-End | Seamlessly transitions between Gluon eager imperative mode and symbolic execution for research flexibility and production efficiency. |
| Distributed Training | Supports Parameter Server and Horovod for scalable distributed training across multiple GPUs and nodes. |
| Multi-Language Bindings | Native APIs in Python, Scala, Java, C++, R, Julia, Clojure, and Perl for broad developer accessibility. |
| Gluon High-Level API | Intuitive Gluon API for imperative model building with automatic differentiation and dynamic computation graphs. |
| NDArray API | NumPy-like array operations for GPU-accelerated numerical computing as the foundation of MXNet computations. |
| Symbol API | Symbolic computation graph API for efficient inference and production deployment. |
| Model Zoo | Pre-trained models for computer vision, NLP, and other tasks accessible via the Gluon model zoo. |
| Edge Deployment | Lightweight deployment support for edge devices and mobile platforms via TVM and ONNX export. |

## Use Cases

| Name | Description |
|------|-------------|
| Computer Vision | Build and train image classification, object detection, and segmentation models using GluonCV toolkit. |
| Natural Language Processing | Develop NLP models for text classification, sentiment analysis, and language modeling using GluonNLP. |
| Time Series Forecasting | Build time series forecasting models using the GluonTS toolkit for probabilistic forecasting. |
| Distributed Deep Learning | Train large neural networks across multiple GPUs and nodes using Parameter Server or Horovod. |
| Research Prototyping | Rapid prototyping of novel deep learning architectures using the Gluon imperative API. |

## Integrations

| Name | Description |
|------|-------------|
| GluonCV | Computer vision toolkit built on MXNet providing pre-trained models and training utilities for vision tasks. |
| GluonNLP | NLP toolkit built on MXNet with pre-trained language models and text processing utilities. |
| GluonTS | Time series modeling toolkit built on MXNet for probabilistic forecasting. |
| ONNX | ONNX model format support for importing and exporting models to/from other frameworks. |
| TVM | Apache TVM deep learning compiler for optimizing MXNet model deployment on diverse hardware targets. |
| Horovod | Horovod distributed training framework integration for efficient multi-GPU and multi-node training. |
| D2L.ai | Dive into Deep Learning interactive textbook using MXNet for teaching deep learning concepts. |

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
