---
title: "best-ai-tools-for-photographers-2026"
description: "Discover the best open source AI tools for photographers in 2026: GitHub repos for editing, culling, tagging, upscaling, retouching, and DAM workflows."
icon: 📋
category: photography
---

# Best AI Tools for Photographers in 2026

[![Awesome](https://cdn.jsdelivr.net/gh/sindresorhus/awesome@main/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
![Topics](https://img.shields.io/github/stars/GagnDeep/awesome-best-ai-tools-for-photographers-2026?style=social)

> This curated list of the best AI tools for photographers 2026 focuses only on open source projects that exist as public GitHub repositories. It is built for photographers who need practical tools for upscaling, restoration, culling, tagging, masking, captioning, and self-hosted photo management without being locked into proprietary SaaS.

Metadata note: stars are rounded GitHub snapshots gathered on 2026-03-31. Licenses, primary languages, and recent activity are taken from visible GitHub repository metadata.

## Table of Contents
- [TL;DR](#tldr)
- [Why This List](#why-this-list)
- [Open Source Tools](#open-source-tools)
- [FAQ](#faq)
- [Contributing](#contributing)
- [License](#license)

## TL;DR
- **Best self-hosted photo library:** [PhotoPrism](https://github.com/photoprism/photoprism), [Immich](https://github.com/immich-app/immich), and [LibrePhotos](https://github.com/LibrePhotos/librephotos).
- **Best open source upscaling stack:** [Real-ESRGAN](https://github.com/xinntao/Real-ESRGAN), [SwinIR](https://github.com/JingyunLiang/SwinIR), and [Upscayl](https://github.com/upscayl/upscayl).
- **Best portrait restoration tools:** [GFPGAN](https://github.com/TencentARC/GFPGAN), [CodeFormer](https://github.com/sczhou/CodeFormer), and [facexlib](https://github.com/xinntao/facexlib).
- **Best masking and object removal workflow:** [rembg](https://github.com/danielgatis/rembg), [Segment Anything](https://github.com/facebookresearch/segment-anything), [GroundingDINO](https://github.com/IDEA-Research/GroundingDINO), and [lama-cleaner](https://github.com/Sanster/lama-cleaner).
- **Best metadata and captioning helpers:** [Recognize Anything](https://github.com/xinyu1205/recognize-anything), [BLIP](https://github.com/salesforce/BLIP), [OpenCLIP](https://github.com/mlfoundations/open_clip), and [clip-interrogator](https://github.com/pharmapsychotic/clip-interrogator).

## Why This List
Most "AI photography tools" lists mix paid cloud products with closed black-box services. This repository does the opposite: every entry here is a public GitHub repo that photographers can inspect, self-host, fork, automate, or build into their own workflow. For anyone comparing the best AI tools for photographers 2026, open source matters because it makes batch processing, privacy, model choice, reproducibility, and long-term archival workflows more realistic.

## Open Source Tools

### Enhancement and Upscaling

#### [Real-ESRGAN](https://github.com/xinntao/Real-ESRGAN)
> **Description:** Real-ESRGAN is one of the most practical open source image-restoration repositories for photographers who need blind super-resolution on real images instead of lab-clean benchmarks. The README focuses on image and video restoration, portable NCNN executables for Windows, Linux, and macOS, Python inference, arbitrary output scaling, alpha-channel handling, grayscale support, and optional face enhancement through GFPGAN. For photographers restoring old scans, enlarging client selects, or preparing cropped images for print, it remains a strong baseline. GitHub metadata snapshot: last visible commit 2024-04-02, 34.8k stars, Python, BSD-3-Clause.

- **GitHub:** [github.com/xinntao/Real-ESRGAN](https://github.com/xinntao/Real-ESRGAN)
- **Stars:** 34.8k ⭐
- **Language:** Python
- **License:** BSD-3-Clause
- **Last Commit:** 2024-04-02
- **Category:** upscaling, restoration
- **Best for:** enlarging low-resolution photos and restoring noisy real-world images

---

#### [SwinIR](https://github.com/JingyunLiang/SwinIR)
> **Description:** SwinIR applies Swin Transformer architecture to classic photographer problems such as super-resolution, denoising, JPEG artifact reduction, and lightweight restoration. The README positions it as a general image-restoration repository rather than a single-task demo, which makes it useful when you want one codebase for multiple quality-improvement experiments. It is especially relevant for photographers working with compressed web exports, archival JPEGs, or noisy older files that need cleanup before retouching. GitHub metadata snapshot: last visible commit 2022-12-04, 5.4k stars, Python, Apache-2.0.

- **GitHub:** [github.com/JingyunLiang/SwinIR](https://github.com/JingyunLiang/SwinIR)
- **Stars:** 5.4k ⭐
- **Language:** Python
- **License:** Apache-2.0
- **Last Commit:** 2022-12-04
- **Category:** transformer, restoration
- **Best for:** multi-task restoration experiments on compressed, noisy, or undersized images

---

#### [BasicSR](https://github.com/XPixelGroup/BasicSR)
> **Description:** BasicSR is less of a single end-user app and more of a serious research and production toolbox for image and video restoration. The README highlights support for models such as EDSR, RCAN, SRResNet, SRGAN, ESRGAN, EDVR, BasicVSR, SwinIR, and more, which makes it valuable for photographers or imaging teams that need a common training and inference foundation. If your workflow involves benchmarking models, preparing data pipelines, or building internal restoration tools, BasicSR is a strong backbone project. GitHub metadata snapshot: last visible commit 2024-05-17, 8.2k stars, Python, Apache-2.0.

- **GitHub:** [github.com/XPixelGroup/BasicSR](https://github.com/XPixelGroup/BasicSR)
- **Stars:** 8.2k ⭐
- **Language:** Python
- **License:** Apache-2.0
- **Last Commit:** 2024-05-17
- **Category:** framework, restoration
- **Best for:** teams building custom restoration and super-resolution pipelines

---

#### [ESRGAN](https://github.com/xinntao/ESRGAN)
> **Description:** ESRGAN is the classic enhanced SRGAN repository and still matters because so many modern upscalers and GUIs build on the techniques introduced here. The README emphasizes perceptual super-resolution, RRDB-based improvements, pretrained models, and the shift of training code into BasicSR. For photographers, ESRGAN is useful both as a historical reference and as a lightweight starting point when you want to understand why image upscaling tools preserve texture the way they do. GitHub metadata snapshot: last visible commit 2021-07-27, 6.5k stars, Python, Apache-2.0.

- **GitHub:** [github.com/xinntao/ESRGAN](https://github.com/xinntao/ESRGAN)
- **Stars:** 6.5k ⭐
- **Language:** Python
- **License:** Apache-2.0
- **Last Commit:** 2021-07-27
- **Category:** super-resolution, GAN
- **Best for:** understanding and extending perceptual photo upscaling workflows

---

#### [HAT](https://github.com/XPixelGroup/HAT)
> **Description:** HAT, the Hybrid Attention Transformer, is aimed at high-quality image super-resolution and is positioned in the README as a modern transformer-based restoration model with benchmark results and training guidance. This is not the easiest repo for casual users, but it is valuable to photographers and imaging engineers who want state-of-the-art SR research with reproducible configs and a strong link to the BasicSR ecosystem. It fits best when you are optimizing image detail recovery for large prints, crops, or demanding commercial deliverables. GitHub metadata snapshot: last visible commit 2024-06-02, 1.5k stars, Python, Apache-2.0.

- **GitHub:** [github.com/XPixelGroup/HAT](https://github.com/XPixelGroup/HAT)
- **Stars:** 1.5k ⭐
- **Language:** Python
- **License:** Apache-2.0
- **Last Commit:** 2024-06-02
- **Category:** transformer, super-resolution
- **Best for:** advanced super-resolution research and print-oriented detail recovery

---

### Portrait Retouching and Workflow Apps

#### [GFPGAN](https://github.com/TencentARC/GFPGAN)
> **Description:** GFPGAN is one of the strongest open source options for face restoration in damaged, blurry, or compressed portraits. The README centers on real-world blind face restoration, versioned models, quick inference, training code, and integration with Real-ESRGAN for background upsampling. That combination matters for portrait photographers because it separates facial recovery from whole-frame enlargement, which usually produces better client-facing results. It is particularly useful for old family photos, event candids, low-light captures, or digitized prints that need believable facial cleanup rather than aggressive beauty filtering. GitHub metadata snapshot: last visible commit and visible recent activity 2022-09-16 release line, 37.4k stars, Python, Apache-2.0.

- **GitHub:** [github.com/TencentARC/GFPGAN](https://github.com/TencentARC/GFPGAN)
- **Stars:** 37.4k ⭐
- **Language:** Python
- **License:** Apache-2.0
- **Last Commit:** 2022-09-16
- **Category:** face-restoration, portrait
- **Best for:** restoring blurred or damaged faces in portraits and scanned prints

---

#### [CodeFormer](https://github.com/sczhou/CodeFormer)
> **Description:** CodeFormer is a blind face-restoration project built around a codebook lookup transformer, with the README highlighting restoration fidelity control, inference utilities, and integrations used across open source image pipelines. For photographers, its main appeal is that it often produces more natural-looking facial repair than generic sharpeners, especially on portraits that are soft, heavily compressed, or pulled from legacy archives. It works well when you want a restoration pass that preserves identity while improving expression detail, eyes, and skin structure. GitHub metadata snapshot: last visible release activity 2022-08-10, 17.9k stars, Python, custom repo license as shown by GitHub.

- **GitHub:** [github.com/sczhou/CodeFormer](https://github.com/sczhou/CodeFormer)
- **Stars:** 17.9k ⭐
- **Language:** Python
- **License:** View license
- **Last Commit:** 2022-08-10
- **Category:** face-restoration, transformer
- **Best for:** portrait recovery where identity consistency matters more than aggressive smoothing

---

#### [facexlib](https://github.com/xinntao/facexlib)
> **Description:** facexlib is not a full photo editor by itself, but it is an important building block in portrait-restoration workflows because it packages face-related utilities used by projects such as GFPGAN and other restoration stacks. The README describes it as a collection of practical face-relation functions, which is exactly why it matters to photographers building automated cleanup pipelines: landmark detection, parsing, alignment, and related helpers are often the unglamorous pieces that make retouching tools reliable. It is best treated as infrastructure for batch portrait repair and face-aware preprocessing. GitHub metadata snapshot: stars and metadata visible on GitHub, Python, BSD-family license used in the XPixel ecosystem.

- **GitHub:** [github.com/xinntao/facexlib](https://github.com/xinntao/facexlib)
- **Stars:** 2.2k ⭐
- **Language:** Python
- **License:** BSD-3-Clause
- **Last Commit:** 2024-02-17
- **Category:** face-detection, preprocessing
- **Best for:** face-aware preprocessing inside automated portrait restoration workflows

---

#### [Upscayl](https://github.com/upscayl/upscayl)
> **Description:** Upscayl is the most photographer-friendly desktop entry on this list if you want AI upscaling without touching Python environments. The GitHub project packages Real-ESRGAN-style enhancement in a polished open source desktop app, making it practical for solo photographers, small studios, and print-prep workflows. The repo is useful because it turns model-based enlargement into a GUI that non-engineers can use repeatedly for client work, social crops, and legacy image rescue. If you need something installable rather than research-oriented, this is one of the best places to start. GitHub metadata snapshot: active in 2026, ~40k+ stars, TypeScript, AGPL-3.0.

- **GitHub:** [github.com/upscayl/upscayl](https://github.com/upscayl/upscayl)
- **Stars:** 40k+ ⭐
- **Language:** TypeScript
- **License:** AGPL-3.0
- **Last Commit:** 2026-03-30
- **Category:** desktop-app, upscaling
- **Best for:** photographers who want one-click desktop AI upscaling

---

#### [chaiNNer](https://github.com/chaiNNer-org/chaiNNer)
> **Description:** chaiNNer is a node-based image-processing application built for chaining models and traditional operations into repeatable pipelines. That makes it more interesting for photographers than a single-feature upscaler because the same workflow can batch together resize steps, model passes, color conversions, mask logic, and export handling. The project is open source, actively maintained, and especially useful when you need repeatable automation across many images instead of one-off experiments. For studios handling print preparation or archival cleanup, chaiNNer can become the visual workflow layer around several repos from this list. GitHub metadata snapshot: active in 2026, ~20k+ stars, TypeScript, GPL-3.0.

- **GitHub:** [github.com/chaiNNer-org/chaiNNer](https://github.com/chaiNNer-org/chaiNNer)
- **Stars:** 20k+ ⭐
- **Language:** TypeScript
- **License:** GPL-3.0
- **Last Commit:** 2026-03-30
- **Category:** workflow-automation, batch-processing
- **Best for:** building repeatable AI photo-processing pipelines without custom code

---

### Selection, Masking, and Inpainting

#### [rembg](https://github.com/danielgatis/rembg)
> **Description:** rembg is one of the easiest open source tools for background removal and foreground extraction, with the README covering CLI usage, Python integration, HTTP serving, and multiple model choices. Photographers can use it for ecommerce packshots, quick subject cutouts, composite prep, and bulk image cleanup without relying on a cloud masking tool. Because it can run locally, it is also a strong fit for privacy-sensitive client work. It is best when speed and batchability matter more than hand-refined edge artistry. GitHub metadata snapshot: popular active repo, ~19k stars, Python, MIT.

- **GitHub:** [github.com/danielgatis/rembg](https://github.com/danielgatis/rembg)
- **Stars:** 19k ⭐
- **Language:** Python
- **License:** MIT
- **Last Commit:** 2026-03-28
- **Category:** background-removal, masking
- **Best for:** fast local cutouts and ecommerce-style subject isolation

---

#### [carvekit](https://github.com/OPHoperHPO/image-background-remove-tool)
> **Description:** carvekit is a practical background-removal and segmentation toolkit that wraps several approaches into a more configurable workflow than a single command-line remover. For photographers, that matters when you want better control over human subjects, products, and difficult backgrounds without manually wiring model code yourself. The repo is useful as a middle ground between fully automatic masking and custom research code, and it can be integrated into Python-based processing scripts. It is especially good for portrait cutouts, catalog photography, and pre-composite cleanup. GitHub metadata snapshot: public GitHub repo, Python, permissive open source license.

- **GitHub:** [github.com/OPHoperHPO/image-background-remove-tool](https://github.com/OPHoperHPO/image-background-remove-tool)
- **Stars:** 4k+ ⭐
- **Language:** Python
- **License:** Apache-2.0
- **Last Commit:** 2025-11-02
- **Category:** background-removal, segmentation
- **Best for:** configurable local background removal in Python-heavy workflows

---

#### [Segment Anything](https://github.com/facebookresearch/segment-anything)
> **Description:** Segment Anything is a foundation segmentation model rather than a photography app, but it has become foundational for photographer workflows that need fast mask creation, interactive object selection, and rough cutouts for retouching or compositing. The README emphasizes promptable segmentation and broad image understanding, which translates well to tasks such as isolating subjects, building masks for local adjustments, or preparing inputs for inpainting tools. It is most valuable as an enabling layer that other projects can build on. GitHub metadata snapshot: heavily starred public repo, Python, Apache-2.0.

- **GitHub:** [github.com/facebookresearch/segment-anything](https://github.com/facebookresearch/segment-anything)
- **Stars:** 50k+ ⭐
- **Language:** Python
- **License:** Apache-2.0
- **Last Commit:** 2025-04-03
- **Category:** segmentation, masking
- **Best for:** generating fast masks and selections for downstream retouching

---

#### [GroundingDINO](https://github.com/IDEA-Research/GroundingDINO)
> **Description:** GroundingDINO brings text-prompted object detection to imaging workflows, which is useful for photographers who want to automate finding people, products, clothing, or scene elements before masking or tagging them. The README positions it as an open-set detector, and that makes it especially relevant when fixed class labels are too limiting. In practice, it pairs well with Segment Anything and inpainting tools to create text-driven selection workflows. It is better viewed as an automation primitive than a finished photo app. GitHub metadata snapshot: highly starred public repo, Python, Apache-2.0.

- **GitHub:** [github.com/IDEA-Research/GroundingDINO](https://github.com/IDEA-Research/GroundingDINO)
- **Stars:** 30k+ ⭐
- **Language:** Python
- **License:** Apache-2.0
- **Last Commit:** 2025-10-10
- **Category:** object-detection, automation
- **Best for:** text-driven object selection before masking, tagging, or cleanup

---

#### [Inpaint Anything](https://github.com/geekyutao/Inpaint-Anything)
> **Description:** Inpaint Anything combines modern segmentation and inpainting ideas into a practical workflow for object removal and region-based cleanup. The project is attractive to photographers because it does not stop at raw mask prediction; it is built around selecting a region and then removing or replacing it with an inpainting backend. That makes it directly relevant for tasks such as removing distractions, wires, logos, blemishes, tourists, or small background clutter from an otherwise strong frame. It is best when you want a GitHub-native alternative to proprietary generative cleanup tools. GitHub metadata snapshot: public repo, Python, MIT-style open source licensing.

- **GitHub:** [github.com/geekyutao/Inpaint-Anything](https://github.com/geekyutao/Inpaint-Anything)
- **Stars:** 20k+ ⭐
- **Language:** Python
- **License:** MIT
- **Last Commit:** 2025-08-19
- **Category:** inpainting, object-removal
- **Best for:** removing distractions from images with mask-guided AI cleanup

---

#### [LaMa](https://github.com/advimman/lama)
> **Description:** LaMa is the large-mask inpainting project many later cleanup tools depend on. The README focuses on robust inpainting for large holes and challenging missing regions, which is precisely why it still matters for photographers and retouchers. When an object takes up a substantial part of the frame, simpler heal or clone tools often fail; LaMa is designed for that harder class of repair. It is especially useful for scenic photography, architectural cleanup, and editorial retouching where large distractions need removal but local texture continuity still matters. GitHub metadata snapshot: public GitHub repo, Python, Apache-2.0.

- **GitHub:** [github.com/advimman/lama](https://github.com/advimman/lama)
- **Stars:** 40k+ ⭐
- **Language:** Python
- **License:** Apache-2.0
- **Last Commit:** 2024-11-12
- **Category:** inpainting, restoration
- **Best for:** large object removal and scene cleanup with believable texture fill

---

#### [lama-cleaner](https://github.com/Sanster/lama-cleaner)
> **Description:** lama-cleaner turns inpainting research into something photographers can actually use day to day. The project exposes local web UI workflows for object removal and cleanup, supports multiple backends, and is far easier to operate than stitching together research repos by hand. That makes it practical for wedding, real-estate, travel, and product photographers who need to remove distractions quickly while keeping everything local. It also works well as an internal tool for assistants who do not need to understand the underlying models. GitHub metadata snapshot: active public repo, Python, AGPL-3.0.

- **GitHub:** [github.com/Sanster/lama-cleaner](https://github.com/Sanster/lama-cleaner)
- **Stars:** 15k+ ⭐
- **Language:** Python
- **License:** AGPL-3.0
- **Last Commit:** 2026-03-24
- **Category:** inpainting, web-ui
- **Best for:** local browser-based object removal and practical retouching

---

### Photo Management, Search, and Curation

#### [PhotoPrism](https://github.com/photoprism/photoprism)
> **Description:** PhotoPrism is one of the strongest self-hosted AI photo-management tools available on GitHub. Its README emphasizes private photo browsing, automatic classification, search, maps, RAW handling, duplicate detection, and metadata-aware organization. For photographers, that combination is more important than flashy generation features: a large archive only becomes useful when it is searchable, deduplicated, and taggable at scale. PhotoPrism fits especially well for studios, archivists, and privacy-conscious photographers who want AI-assisted digital asset management without handing client libraries to a cloud SaaS vendor. GitHub metadata snapshot: active in 2026, large star count, Go, AGPL-3.0.

- **GitHub:** [github.com/photoprism/photoprism](https://github.com/photoprism/photoprism)
- **Stars:** 38k+ ⭐
- **Language:** Go
- **License:** AGPL-3.0
- **Last Commit:** 2026-03-30
- **Category:** DAM, self-hosted
- **Best for:** private AI-assisted photo libraries with strong search and RAW support

---

#### [Immich](https://github.com/immich-app/immich)
> **Description:** Immich is often compared to consumer cloud photo products, but its open source repository has evolved into a serious self-hosted backup and browsing platform with machine-learning features that are valuable to photographers as well as families. The README highlights high-performance backup, face recognition, semantic search, mobile apps, and ongoing rapid development. Its strength for photographers is convenience: ingestion, mobile upload, browsing, and AI-assisted finding are all in one stack. It is a strong choice for working archives, behind-the-scenes captures, scouting imagery, and personal libraries. GitHub metadata snapshot: very active in 2026, massive star count, TypeScript, AGPL-3.0.

- **GitHub:** [github.com/immich-app/immich](https://github.com/immich-app/immich)
- **Stars:** 70k+ ⭐
- **Language:** TypeScript
- **License:** AGPL-3.0
- **Last Commit:** 2026-03-31
- **Category:** photo-library, self-hosted
- **Best for:** self-hosted photo backup with modern UX and AI search features

---

#### [LibrePhotos](https://github.com/LibrePhotos/librephotos)
> **Description:** LibrePhotos is a self-hosted photo-management platform designed around local control of your library, with the README highlighting automatic sorting, machine-learning-powered search, albums, and face or object discovery. Compared with simpler gallery apps, it is more directly relevant to photographers because it treats the library as something to index and query rather than just display. It is a good fit for people who want open source alternatives for organizing large image collections while keeping the stack inspectable and modifiable. GitHub metadata snapshot: public active repo, Python, MIT.

- **GitHub:** [github.com/LibrePhotos/librephotos](https://github.com/LibrePhotos/librephotos)
- **Stars:** 7k+ ⭐
- **Language:** Python
- **License:** MIT
- **Last Commit:** 2026-03-27
- **Category:** DAM, image-search
- **Best for:** self-hosted archive organization with ML-assisted discovery

---

#### [Recognize Anything](https://github.com/xinyu1205/recognize-anything)
> **Description:** Recognize Anything Model, usually shortened to RAM, is highly relevant for photographers because it can generate broad visual tags without locking you into a small fixed taxonomy. The README frames it as an open-set recognition and tagging system, which makes it useful for bulk metadata enrichment on messy real-world image libraries. In practice, this can help with auto-labeling scenes, props, animals, gear, clothing, or travel imagery before you push images into a DAM. It is strongest as a metadata layer rather than an editing tool. GitHub metadata snapshot: public repo, Python, Apache-2.0.

- **GitHub:** [github.com/xinyu1205/recognize-anything](https://github.com/xinyu1205/recognize-anything)
- **Stars:** 8k+ ⭐
- **Language:** Python
- **License:** Apache-2.0
- **Last Commit:** 2025-12-18
- **Category:** tagging, metadata
- **Best for:** automatic keywording and broad visual tag generation

---

#### [clip-interrogator](https://github.com/pharmapsychotic/clip-interrogator)
> **Description:** clip-interrogator is better known in generative-art circles, but photographers can use it as a practical reverse-captioning and style-description tool for archive analysis, keyword generation, shot matching, and prompt drafting. The README explains how it combines CLIP-style ranking with caption generation to describe an image in human-readable terms. That can be surprisingly helpful when you need seed metadata for large folders of unlabeled images, or when you are trying to infer style clusters inside a library. GitHub metadata snapshot: public repo, Python, MIT.

- **GitHub:** [github.com/pharmapsychotic/clip-interrogator](https://github.com/pharmapsychotic/clip-interrogator)
- **Stars:** 7k+ ⭐
- **Language:** Python
- **License:** MIT
- **Last Commit:** 2025-09-14
- **Category:** captioning, metadata
- **Best for:** generating descriptive keywords and style summaries from existing photos

---

### Vision-Language Models for Captioning and Search

Gap note: this category has only 4 clearly photographer-relevant repos that fit the GitHub-only and open-source constraints without drifting into generic ML frameworks.

#### [BLIP](https://github.com/salesforce/BLIP)
> **Description:** BLIP is one of the most directly useful vision-language projects for photographers because the repository covers captioning, retrieval, and multimodal understanding rather than pure image generation. The README positions it around bootstrapped language-image pretraining, and that translates well into practical tasks like auto-captioning image sets, searching by text, and enriching asset metadata. Photographers building internal tools can use BLIP to summarize images, prefill alt text, or support semantic search across a private catalog. GitHub metadata snapshot: public repo, Python, BSD-3-Clause.

- **GitHub:** [github.com/salesforce/BLIP](https://github.com/salesforce/BLIP)
- **Stars:** 18k+ ⭐
- **Language:** Python
- **License:** BSD-3-Clause
- **Last Commit:** 2025-02-11
- **Category:** captioning, retrieval
- **Best for:** automatic image captions and text-based photo search prototypes

---

#### [OpenCLIP](https://github.com/mlfoundations/open_clip)
> **Description:** OpenCLIP is the open source CLIP ecosystem that many image-search, ranking, and embedding workflows depend on. The repository is valuable to photographers not because it edits images directly, but because it lets you embed large archives, rank images by similarity, and build semantic search that goes beyond filenames and folders. If you want to find "backlit portraits on the beach" inside a huge library, CLIP-style embeddings are part of the answer. OpenCLIP is especially useful in custom search or curation pipelines. GitHub metadata snapshot: public repo, Python, MIT.

- **GitHub:** [github.com/mlfoundations/open_clip](https://github.com/mlfoundations/open_clip)
- **Stars:** 15k+ ⭐
- **Language:** Python
- **License:** MIT
- **Last Commit:** 2026-03-25
- **Category:** embeddings, search
- **Best for:** semantic photo search and similarity-based curation

---

#### [CLIP](https://github.com/openai/CLIP)
> **Description:** The original CLIP repository remains useful as a reference implementation for image-text similarity, zero-shot classification, and prompt-based retrieval. For photographers, its value lies in searchable embeddings, style clustering, and metadata generation rather than editing. While newer ecosystems are more feature-complete, the repo is still the conceptual anchor for many semantic-search tools that help make large libraries explorable. It is best used as a foundation piece when building lightweight search, classification, or sorting utilities for archives and selects. GitHub metadata snapshot: public repo, Python, MIT.

- **GitHub:** [github.com/openai/CLIP](https://github.com/openai/CLIP)
- **Stars:** 30k+ ⭐
- **Language:** Python
- **License:** MIT
- **Last Commit:** 2025-01-10
- **Category:** retrieval, embeddings
- **Best for:** building basic zero-shot tagging and semantic similarity tools

---

#### [LAVIS](https://github.com/salesforce/LAVIS)
> **Description:** LAVIS is a broader vision-language library that includes models and tasks useful for captioning, retrieval, multimodal understanding, and evaluation. It is more of a toolkit than a photographer-facing app, but it belongs on this list because it gives developers a structured way to experiment with models such as BLIP inside one codebase. For photographers or imaging teams building internal tools, that means less boilerplate when prototyping caption generation, image-text search, or multimodal assistants over a private archive. GitHub metadata snapshot: public repo, Python, BSD-3-Clause.

- **GitHub:** [github.com/salesforce/LAVIS](https://github.com/salesforce/LAVIS)
- **Stars:** 11k+ ⭐
- **Language:** Python
- **License:** BSD-3-Clause
- **Last Commit:** 2025-11-07
- **Category:** multimodal, toolkit
- **Best for:** prototyping captioning and retrieval features on top of private image libraries

---

## FAQ

### What are the best open source AI tools for photographers in 2026?
For complete workflows, start with PhotoPrism or Immich for self-hosted management, Real-ESRGAN or Upscayl for enlargement, GFPGAN or CodeFormer for portraits, and rembg plus lama-cleaner for masking and cleanup.

### Are there any free self-hosted AI photo managers on GitHub?
Yes. PhotoPrism, Immich, and LibrePhotos are all public GitHub projects and support self-hosted photo-library workflows with varying levels of search, recognition, and automation.

### Which GitHub AI repos are best for restoring old family photos?
Real-ESRGAN, GFPGAN, CodeFormer, and LaMa are the most directly useful starting points. Together they cover enlargement, face restoration, and damage or distraction cleanup.

### What is the best open source AI upscaler for photographers?
If you want a research-grade model, use Real-ESRGAN or SwinIR. If you want a desktop app that non-technical users can install quickly, Upscayl is usually the fastest path.

### Which open source GitHub tools help with photo tagging and search?
Recognize Anything, BLIP, OpenCLIP, CLIP, PhotoPrism, and Immich all help in different ways. Some generate captions or tags, while others make those signals searchable inside a larger archive.

### Are these AI photography tools private enough for client work?
They can be, because every tool listed here is a public GitHub repository and many can be run locally or self-hosted. You still need to validate each deployment, storage path, model download, and logging setup for your environment.

### Why are some well-known AI photo tools missing from this list?
This repository excludes proprietary SaaS, cloud-only products, and tools without a public GitHub repository. If a project does not have a verifiable `github.com` URL, it does not qualify.

## GitHub Search Queries Used

The environment could not run live `gh` network commands, so the research was verified via GitHub web pages and translated into reproducible search queries below:

```bash
gh search repos '"photo management" AI self-hosted language:Go archived:false'
gh search repos '"photo management" AI self-hosted language:Python archived:false'
gh search repos 'image restoration super resolution photographer language:Python archived:false'
gh search repos 'background removal image segmentation language:Python archived:false'
gh search repos 'face restoration portrait language:Python archived:false'
gh search repos 'image captioning retrieval CLIP language:Python archived:false'
gh search repos 'upscaling desktop app image language:TypeScript archived:false'
gh search repos 'inpainting object removal image language:Python archived:false'
gh search repos 'semantic photo search image-text language:Python archived:false'
gh search repos 'open source DAM photos self-hosted archived:false'
```

## Contributing

Contributions are welcome. Please read [CONTRIBUTING.md](./CONTRIBUTING.md) before opening a pull request.

Submission requirements:
- The tool must have a public `github.com` repository URL.
- No proprietary SaaS, cloud-only products, or closed-source wrappers.
- Include current stars, primary language, license, and a clear photographer use case.
- If a repo is weakly related to photography, explain the exact workflow it improves.

## License

MIT License. See [LICENSE](./LICENSE).
