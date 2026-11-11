# Start here: AI Toolbox

[Home](../README.md) · [Tools](../TOOLS.md) · [Sources](../SOURCES.md)

Select a task, inspect the complete pinned package, then try a bounded synthetic fixture. These are reading paths and prototype ideas, not tested integrations.

## Build a personal assistant

| Project | ใช้ทำอะไร | Evidence to collect |
| --- | --- | --- |
| [Hermes Agent](https://github.com/NousResearch/hermes-agent/tree/60f81635c28e825a233f7bb25ed93a2579d5b547) | Agent ส่วนตัวที่ใช้ tools, memory, skills และ messaging gateways | Version, configuration, one task result, failure behavior and data/permission boundaries |
| [Mem0](https://github.com/mem0ai/mem0/tree/f1791daa86d469249c9b002f62644d58a1eb96a0) | เพิ่ม memory layer ที่แยก user/session/agent context | Version, configuration, one task result, failure behavior and data/permission boundaries |
| [Graphiti](https://github.com/getzep/graphiti/tree/ebef986a0b2360211b65751c111cacb4a7d790eb) | เก็บ entities, relationships และ facts ที่มีช่วงเวลาความถูกต้อง | Version, configuration, one task result, failure behavior and data/permission boundaries |
| [Letta Code](https://github.com/letta-ai/letta-code/tree/ad308cd3cb8486afa0bb8ad624c690b828339ea7) | สร้าง stateful agent harness ที่มี memory, skills, channels และ scheduling | Version, configuration, one task result, failure behavior and data/permission boundaries |

## Run models

| Project | ใช้ทำอะไร | Evidence to collect |
| --- | --- | --- |
| [Ollama](https://github.com/ollama/ollama/tree/8a89b76cc7359805e48357ba7e5b99e845a4c211) | จัดการและเรียกโมเดลผ่าน local runtime และ REST API | Version, configuration, one task result, failure behavior and data/permission boundaries |
| [llama.cpp](https://github.com/ggml-org/llama.cpp/tree/f3b407ca1bfeeecebf9e9ef19fcd6eed565bd70a) | รัน LLM/VLM และ quantized models บน hardware หลายชนิด | Version, configuration, one task result, failure behavior and data/permission boundaries |
| [vLLM](https://github.com/vllm-project/vllm/tree/bafa5c6c30b8397e64fb6a73740b9ebe71a18f05) | ให้บริการโมเดลด้วย batching, KV cache และ API server | Version, configuration, one task result, failure behavior and data/permission boundaries |
| [SGLang](https://github.com/sgl-project/sglang/tree/5fbfcc7170235064125d23feac4b64e5dbe41414) | วาง inference serving สำหรับ LLM, multimodal และ agentic workloads | Version, configuration, one task result, failure behavior and data/permission boundaries |
| [LiteLLM](https://github.com/BerriAI/litellm/tree/3616014548d40020f508566620c5cd8745721f3c) | รวม model providers ผ่าน SDK/proxy พร้อม cost/routing controls | Version, configuration, one task result, failure behavior and data/permission boundaries |

## Use documents and the web

| Project | ใช้ทำอะไร | Evidence to collect |
| --- | --- | --- |
| [Browser Use](https://github.com/browser-use/browser-use/tree/7fdd63c03fd342aab4fe44507c77c3221ffd43c6) | ให้ Agent โต้ตอบ browser จริงและอ่านผลผ่าน browser harness | Version, configuration, one task result, failure behavior and data/permission boundaries |
| [Stagehand](https://github.com/browserbase/stagehand/tree/c8e096cb83b6c06ad73e49583fb79a87e78bdd3c) | ใช้ observe, act และ schema-based extraction ใน browser automation | Version, configuration, one task result, failure behavior and data/permission boundaries |
| [Skyvern](https://github.com/Skyvern-AI/skyvern/tree/26d2722b0fc9c7f3246389bdf7385ef18862b242) | ทำ browser workflows ด้วย vision/LLM และ workflow builder | Version, configuration, one task result, failure behavior and data/permission boundaries |
| [Crawl4AI](https://github.com/unclecode/crawl4ai/tree/cae74b203a33994f7e13b9052c3b0d5c93daa0e6) | แปลงเว็บเป็น Markdown หรือ structured data สำหรับ Agent/RAG | Version, configuration, one task result, failure behavior and data/permission boundaries |
| [Docling](https://github.com/docling-project/docling/tree/da1eda8a6b4ef62691eee6e72ced4891a30e654c) | แยก layout, tables, OCR และ export เอกสารเป็นข้อมูลสำหรับ AI | Version, configuration, one task result, failure behavior and data/permission boundaries |
| [MarkItDown](https://github.com/microsoft/markitdown/tree/ed178952a6672abdfd35b5f9e76a80b6cefc086e) | แปลงเอกสารหลายชนิดเป็น Markdown สำหรับ text-analysis pipelines | Version, configuration, one task result, failure behavior and data/permission boundaries |

## Create voice or visual workflows

| Project | ใช้ทำอะไร | Evidence to collect |
| --- | --- | --- |
| [LiveKit Agents](https://github.com/livekit/agents/tree/065deca6364096ce0cb79fd41dc1d3e53c64850e) | สร้าง real-time voice/video Agents ที่เชื่อม STT, LLM และ TTS | Version, configuration, one task result, failure behavior and data/permission boundaries |
| [Pipecat](https://github.com/pipecat-ai/pipecat/tree/caff2b489bfbee73be0f75e9de7601490205873d) | ประกอบ streaming voice/multimodal pipelines และ conversation flows | Version, configuration, one task result, failure behavior and data/permission boundaries |
| [faster-whisper](https://github.com/SYSTRAN/faster-whisper/tree/3ec025c4b7526e3fa121e527724ac43afa275a95) | ถอดเสียงด้วย Whisper ผ่าน CTranslate2 บน CPU/GPU | Version, configuration, one task result, failure behavior and data/permission boundaries |
| [ComfyUI](https://github.com/Comfy-Org/ComfyUI/tree/4d64a8bc072b81c9b47321789b4d83fb7348ae2a) | ประกอบ image/video/audio generation ผ่าน node-graph workflows | Version, configuration, one task result, failure behavior and data/permission boundaries |
| [Diffusers](https://github.com/huggingface/diffusers/tree/f598e6e6a99528858b962c1399c45b59a6c25484) | สร้าง diffusion pipelines และปรับ schedulers/models ใน Python | Version, configuration, one task result, failure behavior and data/permission boundaries |
| [CosyVoice](https://github.com/QwenAudio/CosyVoice/tree/074ca6dc9e80a2f424f1f74b48bdd7d3fea531cc) | สร้างเสียง TTS และศึกษาการ streaming/control ของ speech models | Version, configuration, one task result, failure behavior and data/permission boundaries |

