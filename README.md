### Gyeongpil Lee (이경필)

I build small open-source tools for the parts of LLM apps that are easy to skip: output checks, evals, RAG and local models.

**Lately**

- Output and tool-call checks — schema shims, tool-call protocol, guardrail comparison
- Evals — LLM-judge agreement, embedding A/B tests, RAG recall
- Local LLM ops — Ollama, LoRA adapters, context windows
- Korean text for LLMs — PII masking, TTS readout, IME testing

Most projects run offline with a mock mode, no API key needed. Each comes with tests, CI and an MIT license.

<details>
<summary>한국어 소개</summary>

LLM 앱을 만들다 "이런 도구 하나 있으면 좋겠다" 싶던 것을 직접 만들어 오픈소스로 공개합니다.
요즘은 출력·도구 호출 검증, 평가, 로컬 LLM 운영, 한국어 처리를 주로 봅니다.
대부분 API 키 없이 모의 모드로 바로 돌려 볼 수 있습니다.

</details>

#### Projects

<!-- projects:start -->
- [agreelens](https://github.com/LeeGyeongPil/agreelens) — Check how well an LLM judge agrees with humans
- [latency-steps](https://github.com/LeeGyeongPil/latency-steps) — Find when latency stepped up and which slice caused it
- [modelfile-doctor](https://github.com/LeeGyeongPil/modelfile-doctor) — Lint Ollama Modelfiles before ollama create
- [next-route-impact](https://github.com/LeeGyeongPil/next-route-impact) — Find which Next.js routes a change affects
- [sandbox-drift](https://github.com/LeeGyeongPil/sandbox-drift) — Catch coding-agent sandbox regressions with canary probes
- [worktree-shelve](https://github.com/LeeGyeongPil/worktree-shelve) — Back up and remove stale git worktrees, restore in one step
- [guarddiff](https://github.com/LeeGyeongPil/guarddiff) — Compare guardrail variants on the same prompts
- [handoffmap](https://github.com/LeeGyeongPil/handoffmap) — Turn agent traces into a handoff flow diagram

All 56 projects: [ai-lab](https://github.com/LeeGyeongPil/ai-lab)
<!-- projects:end -->

Python · TypeScript · Dart
