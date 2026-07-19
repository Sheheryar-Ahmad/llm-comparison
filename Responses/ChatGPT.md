# Technical Research Summary: Claude 3.5 Sonnet

## Executive Summary

Claude 3.5 Sonnet is the first model in Anthropic’s Claude 3.5 family, delivering higher intelligence than both competitor models and Claude 3 Opus while maintaining the speed and pricing of the mid-tier Claude 3 Sonnet. The release also introduces **Artifacts**, a collaborative workspace that enables users to create, edit, and iterate on AI-generated content directly within Claude.

## Key Technical Contributions

- Achieves new benchmark performance across graduate-level reasoning (GPQA), undergraduate-level knowledge (MMLU), and coding proficiency (HumanEval), while operating at **2× the speed** of Claude 3 Opus.
- Available through Claude.ai, Anthropic API, Amazon Bedrock, and Google Cloud Vertex AI, with pricing of **$3 per million input tokens**, **$15 per million output tokens**, and a **200K-token context window**.
- In Anthropic’s internal agentic coding evaluation, Claude 3.5 Sonnet solved **64%** of tasks compared with **38%** for Claude 3 Opus, demonstrating autonomous code writing, editing, execution, troubleshooting, and code translation capabilities.
- Introduces enhanced vision performance, surpassing Claude 3 Opus on standard vision benchmarks, with improved visual reasoning and accurate transcription from imperfect images.
- Launches **Artifacts**, enabling real-time editing of generated code, documents, and web designs in a dedicated collaborative workspace.

## Methodology & Infrastructure

The document highlights extensive internal benchmarking across reasoning, knowledge, coding, and vision tasks, including an internal agentic coding evaluation that measures autonomous software modification using natural-language instructions and external tools. The model is deployed through Claude.ai, Anthropic API, Amazon Bedrock, and Google Cloud Vertex AI, supports a 200K-token context window, and underwent red-teaming, external safety evaluations, and policy refinement with domain experts before release.

## Limitations & Future Work

No explicit technical limitations are described. Future work includes releasing Claude 3.5 Haiku and Claude 3.5 Opus, expanding enterprise integrations, developing additional modalities, and introducing Memory to personalize user interactions while continuing improvements in intelligence, speed, and cost.
