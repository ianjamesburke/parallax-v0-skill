# Parallax — AI Video Production Skill

An AI agent skill for producing short-form video (Reels, TikToks, YouTube Shorts) from a YAML spec using the [Parallax CLI](https://github.com/ianjamesburke/parallax-v0) and the OpenRouter API.

## What it does

Install this skill into your AI assistant (Claude Code, OpenClaw, or any OpenClaw-compatible agent) and it gains full operator knowledge of the Parallax CLI:

- **Initialization** — checks if the CLI is installed, walks through OpenRouter API key setup, verifies credits before spending
- **Brief authoring** — helps you write `brief.yaml` for any video concept
- **Produce loop** — runs `parallax plan` + `parallax produce`, iterates until you approve
- **Asset locking** — locks approved stills, voiceovers, and clips in `plan.yaml` so only changed scenes re-run
- **Model selection** — explains draft/mid/premium tiers across image and video models (Seedance, Kling, Veo, Wan, Sora, nano-banana)
- **Cost management** — estimates spend before any real job, checks credits, uses 480p generation + upscale by default

## Requirements

- [OpenRouter API key](https://openrouter.ai/keys) with credits
- Claude Code, OpenClaw, or compatible AI assistant

## Get the skill

Available on ClawMart — $19 one-time:

**[shopclawmart.com/listings/parallax-cli-ai-video-production-12ad0f74](https://www.shopclawmart.com/listings/parallax-cli-ai-video-production-12ad0f74)**

## CLI source

The Parallax CLI itself is open source:

**[github.com/ianjamesburke/parallax-v0](https://github.com/ianjamesburke/parallax-v0)**
