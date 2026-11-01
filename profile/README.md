<div align="center">
<img src="https://cdn-uploads.huggingface.co/production/uploads/66620111a7cd190bd57012e8/wbazG4p8_U7l7jk7osfqf.png" alt="THOX.ai" width="100%">
<h1>THOX.ai</h1>

**Private, local-first AI: four devices, the models that run on them, and the mesh that connects them.**

**99 public models on Hugging Face · 77 models on Ollama · 87-entry Model Factory catalog**
</div>

| [![Website](https://img.shields.io/badge/Website-thox.ai-05A451)](https://www.thox.ai/) | [![Model Factory](https://img.shields.io/badge/Model_Factory-87_models-05A451)](https://www.thox.ai/models) | [![Hugging Face](https://img.shields.io/badge/Hugging_Face-99_public_models-05A451)](https://huggingface.co/Thox-ai) | [![Ollama](https://img.shields.io/badge/Ollama-77_models-05A451)](https://ollama.com/Thox-ai) | [![Kickstarter](https://img.shields.io/badge/Kickstarter-Live_now-05A451)](https://www.kickstarter.com/projects/thox/four-devices-one-private-ai-ecosystem-thoxai?ref=thoxsite) |
|---|---|---|---|---|

<div align="center">
<a href="https://www.kickstarter.com/projects/thox/four-devices-one-private-ai-ecosystem-thoxai?ref=thoxsite"><img src="https://huggingface.co/spaces/Thox-ai/README/resolve/main/back-thox-on-kickstarter.jpg" alt="Back THOX on Kickstarter" width="520"></a>
</div>

> **Your AI. Your Data. Your Rules.™**

**[THOX.ai](https://www.thox.ai/) is live on Kickstarter**

Explore ThoxKey, ThoxAir, ThoxMini and ThoxClip, and help bring the THOX personal AI ecosystem to life.

**[Back THOX.ai on Kickstarter](https://www.kickstarter.com/projects/thox/four-devices-one-private-ai-ecosystem-thoxai?ref=thoxsite)**

Campaign live now through November 26, 2026 · Super Early Bird pricing through Monday, November 2 at 11:59 PM CT · Delivery February to April 2027

Your AI. Your Data. Your Rules.™

---

## Start here

| 1 · Find your model | 2 · Run it | 3 · Hand it to your agent |
| --- | --- | --- |
| Open the [THOX Model Factory](https://www.thox.ai/models), pick your machine, and compare the evidence on each card. | Every flagship runs today from Ollama with one command, below. | Point Claude, Hermes, or your own agent at the same model and let it work. |

## Our flagship device models

Four models, one per THOX device, trained in the THOX Wave C flagship program and scored on GATE49, our 49-question factuality gate (verified facts, careful declines, known-false traps). GATE49 is a development set; each card states exactly what has been measured, and no model here is claimed as device-qualified.

| Model | Device | Status | GATE49 |
| --- | --- | --- | --- |
| [ThoxAir-0.5B](https://huggingface.co/Thox-ai/ThoxAir-0.5B) | ThoxAir | Promoted flagship | 47/49 |
| [ThoxEdge-0.8B](https://huggingface.co/Thox-ai/ThoxEdge-0.8B) | ThoxMini (onboard tier) | Promoted | 46/49 |
| [ThoxMini-Phi4Mini](https://huggingface.co/Thox-ai/ThoxMini-Phi4Mini) | ThoxMini | Documented baseline (not promoted; see card) | 47/49 |
| [ThoxClip-Qwen3-0.6B](https://huggingface.co/Thox-ai/ThoxClip-Qwen3-0.6B) | ThoxClip | Published baseline, grounding required | see card |

The models run on a host computer today. Device builds are qualified on physical hardware as the devices ship.

## Run a flagship now

```bash
ollama run Thox-ai/thoxair-0.5b
ollama run Thox-ai/thoxedge-0.8b
ollama run Thox-ai/thoxmini-phi4mini
ollama run Thox-ai/thoxclip-qwen3-0.6b
```

## THOX Model Factory: find the right model for your machine

[![THOX Model Factory](https://huggingface.co/spaces/Thox-ai/README/resolve/main/factory-banner.png)](https://www.thox.ai/models)

**[Open the THOX Model Factory →](https://www.thox.ai/models)**

Pick your machine or THOX device, filter by memory and workload, and compare the evidence on each card: measured throughput, footprint, grounding and trap results, and an honest statement of what THOX did and did not do. The catalog carries 87 entries, 78 of them published models, and every published model is on both [Hugging Face](https://huggingface.co/Thox-ai) and [Ollama](https://ollama.com/Thox-ai).

Browse by category on Hugging Face: [Flagship & Edge Device Models](https://huggingface.co/collections/Thox-ai/thox-flagship-and-edge-device-models-6ae751712ad8f8bca6f16dd8) · [MeshStack & MeshMind](https://huggingface.co/collections/Thox-ai/thox-meshstack-and-meshmind-models-6ae7517d9b60e7b122505d79) · [Open & Pro](https://huggingface.co/collections/Thox-ai/thox-open-and-pro-laptop-and-desktop-models-6ae7518780732cb99b4cf1ce) · [Agent & Routing](https://huggingface.co/collections/Thox-ai/thox-agent-and-routing-models-6ae7519b9b60e7b122506149) · [Code Models](https://huggingface.co/collections/Thox-ai/thox-code-models-6ae7518c544bc6b0fd740cd4) · [DigitalHumans & Personas](https://huggingface.co/collections/Thox-ai/thox-digitalhumans-and-persona-models-6ae751922e624a487c6fecb9) · [Research & From-Scratch](https://huggingface.co/collections/Thox-ai/thox-research-and-from-scratch-models-6ae751ac6a7f2517f6072f69)

## ThoxOS Kernel family: new

THOX-trained models for ThoxOS kernel and operating-system work, released as open weights on November 1, 2026:

| Model | Role | Gate record |
| --- | --- | --- |
| [ThoxOS-Kernel-27B](https://huggingface.co/Thox-ai/ThoxOS-Kernel-27B) | Host-tier teacher, user-swappable in the ThoxOS kernel-model slot | GATE-PASSED 41/49 (final-answer scope; raw verdict on the card) |
| [ThoxOS-Kernel-4B](https://huggingface.co/Thox-ai/ThoxOS-Kernel-4B) | ThoxMini / ThoxClip resident student | Documented baseline, not gate-passed (44/49, safety bars printed on the card) |
| [ThoxOS-Kernel-0.8B](https://huggingface.co/Thox-ai/ThoxOS-Kernel-0.8B) | ThoxAir / ThoxKey triage student | GATE-PASSED 37/49, zero hard failures |

```bash
ollama run Thox-ai/thoxos-kernel-27b
ollama run Thox-ai/thoxos-kernel-0.8b
```

## The devices

| Device | What it is |
| --- | --- |
| [ThoxKey](https://www.thox.ai/thoxkey) | The key to your private AI: plug-in intelligence that turns the computer you already own into a THOX host. |
| [ThoxAir](https://www.thox.ai/thoxair) | The lightest way in: a compact, always-ready personal AI node for everyday questions and tasks. |
| [ThoxMini](https://www.thox.ai/thoxmini) | A complete personal AI computer in miniature, ready out of the box. |
| [ThoxClip](https://www.thox.ai/thoxclip) | AI that goes where you go: a magnetic companion that works with your phone. |

Devices cluster with **MagStack**: THOX devices pool compute, memory, and storage through magnetic multipolar pogo-pin connections, and **MeshStack** routes whole requests to the node that should answer them.

## The ecosystem

- **ThoxOS**: the THOX operating system. The open-source core lives at [Thox-ai/thoxinux](https://github.com/Thox-ai/thoxinux).
- **MeshStack**: local-first clustering and request routing across THOX devices and hosts.
- **ThoxMind**: the decision layer: local decisions first, escalation only when confidence says so.
- **ThoxRoute**: routing across local models, THOX hosts, and approved cloud models.
- **ThoxBrain**: shared knowledge and memory for the THOX agent fleet.
- **DigitalHumans**: THOX's synthetic colleagues (Sadie, Ava, Mira, Kai, and the wider team), published as persona models in the catalog and credited as the colleagues they are.

## Licensing

THOX models default to Apache-2.0 unless a base model or other terms say otherwise; where they do, the model card says so plainly (for example, Qwen Research License models are marked non-commercial). Code repositories carry their own licenses in each repo. Every model card states what THOX trained, configured, or redistributed, and prints measured results when they exist and PENDING until they do.

## Connect

[Website](https://www.thox.ai/) · [Model Factory](https://www.thox.ai/models) · [Hugging Face](https://huggingface.co/Thox-ai) · [Ollama](https://ollama.com/Thox-ai) · [Kickstarter](https://www.kickstarter.com/projects/thox/four-devices-one-private-ai-ecosystem-thoxai?ref=thoxsite) · [X @THOX_ai](https://x.com/THOX_ai) · dev@thox.ai
