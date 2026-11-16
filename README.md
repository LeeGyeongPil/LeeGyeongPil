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
- [genai-span-doctor](https://github.com/LeeGyeongPil/genai-span-doctor) — Audit OTLP traces for LLM token dialects and emit OTTL fixes
- [kube-llm-lint](https://github.com/LeeGyeongPil/kube-llm-lint) — Lint vLLM, SGLang and TGI Kubernetes manifests offline
- [mcp-skillpin](https://github.com/LeeGyeongPil/mcp-skillpin) — Verify, pin and install MCP-served agent skills
- [arb-guard](https://github.com/LeeGyeongPil/arb-guard) — Catch broken placeholders and plurals in translated ARBs
- [hookparity](https://github.com/LeeGyeongPil/hookparity) — Check pre-tool-use hooks across Claude, Codex and Gemini
- [plugslim](https://github.com/LeeGyeongPil/plugslim) — Keep only the Claude Code plugin skills you use
- [flutter-llm-proxy](https://github.com/LeeGyeongPil/flutter-llm-proxy) — Hide LLM API keys behind a Dart proxy with App Check
- [lora-mergecheck](https://github.com/LeeGyeongPil/lora-mergecheck) — Verify merged LoRA checkpoints with numbers, not guesses

All 97 projects: [ai-lab](https://github.com/LeeGyeongPil/ai-lab)
<!-- projects:end -->

Python · TypeScript · Dart
