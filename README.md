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
- [flutter-llm-proxy](https://github.com/LeeGyeongPil/flutter-llm-proxy) — Hide LLM API keys behind a Dart proxy with App Check
- [lora-mergecheck](https://github.com/LeeGyeongPil/lora-mergecheck) — Verify merged LoRA checkpoints with numbers, not guesses
- [trace-codebook](https://github.com/LeeGyeongPil/trace-codebook) — Code LLM traces into failure modes with counts
- [baseline-modernize](https://github.com/LeeGyeongPil/baseline-modernize) — Find legacy web patterns and suggest Baseline replacements
- [flutter-key-audit](https://github.com/LeeGyeongPil/flutter-key-audit) — Scan Flutter builds for leaked AI API keys
- [langgraph-preflight](https://github.com/LeeGyeongPil/langgraph-preflight) — Check a LangGraph StateGraph before it runs
- [mcp-launch-doctor](https://github.com/LeeGyeongPil/mcp-launch-doctor) — Diagnose why stdio MCP servers fail to launch in apps
- [specpair](https://github.com/LeeGyeongPil/specpair) — Check draft-target pairs and bench speculative decoding

All 79 projects: [ai-lab](https://github.com/LeeGyeongPil/ai-lab)
<!-- projects:end -->

Python · TypeScript · Dart
