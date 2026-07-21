# Prompts Repository Overview

This directory holds prompt design, custom agent instructions, image-generation benchmarks, headless Linux setup guides, and a prototype automated brief-to-video pipeline.

## 1. Custom agents / instructions
- `agents/interactionManual.adoc`: primary custom instruction set for direct, technical, no-filler AI interaction.
- `agents/TechFormatting.asc`: formatting-focused prompt and style rules for structured technical output.
- `agents/TherapeuticPersonaAgent.asc`: persona prompt for a supervisory/therapeutic peer-style agent.

## 2. Image-generation test content
- `imgen/`: image-generation prompt tests and benchmark assets.
- `imgen/darthGarga.adoc`: a repeatable benchmark prompt used across tools and versions to measure evolution, consistency, and output quality.
- `imgen/blackHole-iterative.adoc`: iterative image prompt testing for refinement and debugging.

## 3. Linux headless system devops / setup guides
- `setup.arch/`: Final step-by-step guide for Arch Linux. Output from GPT.
- `setup.rpi/`: Raspberry Pi headless setup documentation covering input, output, and system configuration.

## 4. Automated brief → full video pipeline prototype
- `promptProductionPipeline/`: documentation and prompt source for a prototype pipeline that turns a brief into full video production output.
- `promptProductionPipeline/documentationStart.m.asc`: project overview covering workflow, results, prompt engineering, and automation observations.
- `promptProductionPipeline/documentationStart.m.pdf`: documentation file autoconversion to PDF.

## 5. How to use this area
1. Review `agents/` for instruction tuning and agent behavior design.
2. Use `imgen/` to benchmark image prompt performance. Start with `darthGarga.adoc` for tool comparisons.
3. Follow `setup.arch/` and `setup.rpi/` for Linux headless deployment and device configuration.
4. Explore `promptProductionPipeline/` for the end-to-end automated brief-to-video process, including prompt sets, workflow description, and output traces.

## Notes
- `darthGarga.adoc` is explicitly shaped as a repeatable prompt for benchmarking across multiple imaging tools and iterations.
- The pipeline documentation emphasizes multiple LLMs orchestrating logic, process, script iteration, and prompt adaptation.

