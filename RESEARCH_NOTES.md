# RESEARCH_NOTES

**Domain:** Vision Language Models
**Upstream:** https://github.com/openai/whisper
**Fork:** https://github.com/sureshsolanki-labs/whisper
**Priority:** High
**Baseline date:** 2026-07-04

## Use case fit

**Note: whisper is ASR (automatic speech recognition), NOT a vision-language model.** Filed under VLM per user's requested taxonomy tag. Direct fit for voice-based field capture in Akshaya Dhara rural flows (low-literacy support) and audio transcription of verifier calls.

## Planned adaptation notes

Evaluate for regional-language ASR (Hindi, Kannada, Telugu, etc.); measure latency on low-end field hardware; strict T4 evidence tier — transcripts are advisory, never canonical evidence. Keep off consent/identity capture paths.

## Boundaries

- Advisory tier only unless explicitly upgraded via an approved gate.
- Do not conflate model output with sensor evidence — respect T3/T4/T5 evidence discipline.
- Do not enable Aadhaar/registry/beneficiary/payout paths from this repo.
- No server secrets or forbidden identity fields persisted from adaptation work here.

_This file is a research baseline. It is not a design decision, roadmap commitment, or claim of registry approval._
