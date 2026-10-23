### Hi, I'm Dogwind 👋

I build AI applications — and I try to build them without pulling in a framework.

`1 developer · 0 runtime dependencies · 10 modules · 67 routes · 372+ assertions`

---

**What I'm building**

| Project | What it is |
| --- | --- |
| **[Dw-LiveWorkbench](https://github.com/Dogwind221/Dw-LiveWorkbench)** | Zero-dependency AI workbench for livestream content. Self-built RAG (BM25 + hashed n-gram vectors, **recall@5 0.974**), a hand-written ReAct loop (432 lines, 7 tools), multi-tenant RBAC, audit trail, quota — **372+ automated assertions**. |
| **[img2img-studio](https://github.com/Dogwind221/img2img-studio)** ★8 | Image-generation studio with vision-gated routing and multi-provider failover (DashScope / ChatGPT-web / OpenAI / Z.AI / Doubao / MiniMax). E-commerce sets and photo-art styles. |
| **[cinematic-whitebox](https://github.com/Dogwind221/cinematic-whitebox)** ★5 | Script → Blender whitebox previz: derives shots, blocking and camera movement in a cinematic style. |
| **[dsh-vision-skill](https://github.com/Dogwind221/dsh-vision-skill)** ★2 | Vision for text-only LLMs: multi-model failover vision API plus drag-and-drop image recognition in the DSH web UI. |

---

**DeepSeek Harness (DSH) ecosystem**

- **Plugin author** — [`dsh-img2img-config`](https://github.com/Dogwind221/img2img-studio/tree/main/plugins/dsh-img2img-config): a DSH plugin with a composer image editor and a vision/generation provider panel. Submitted to the community [plugin list](https://github.com/awesome-dsh-plugin/awesome-dsh-plugin).
- **Plugin DX reports** that maintainers engaged with: plugin hot-reload semantics ([#10774](https://github.com/deepseek-ai/deepseek-harness/discussions/10774)), query strings in registration paths ([#10775](https://github.com/deepseek-ai/deepseek-harness/discussions/10775)), plugin-load observability ([#10776](https://github.com/deepseek-ai/deepseek-harness/discussions/10776)).
- **Open to outside contributions.** Two community PRs with tests were reviewed, reproduced locally and merged into the workbench: first-authenticated-startup crash, and malformed request URLs taking the process down.

---

**How I work**

- **Measure, don't claim.** Every number above is reproducible from the repo — eval sets and smoke suites are committed, not quoted.
- **Write down the limits.** The workbench README has a known-limitations section, including what it does *not* have yet: no CI, no container image, no load test.
- **Prefer boring tech.** `node:` built-ins only, no build step, and no vector database where BM25 plus hashed char n-grams is enough.

---

<sub>Currently open to Developer Relations / developer-experience work around AI agents and developer tools.</sub>
