### Hi, I'm Gyeongpil Lee (이경필) 👋

> **I build small, dependable tools for LLM applications** — the parts that make them safe to run in production: output checks, secret-leak guards, evals, retrieval and agent tooling. Every project runs offline in a mock mode first, so you can try it without an API key.

LLM 앱을 **실제 서비스에서 믿고 쓸 수 있게 만드는 작은 도구**를 만듭니다. 출력 형식 검증, 비밀값 유출 차단, 평가·비용 진단, RAG, 에이전트·MCP를 주로 다룹니다. 모든 프로젝트는 키 없이 연습(mock) 모드로 먼저 돌려 볼 수 있습니다.

#### Focus

- **Output reliability** — make models follow format and length instructions, and verify answers deterministically
- **Agent safety** — keep secrets and data from leaking through tool calls and generated output
- **Evaluation & cost** — eval gates in CI, prompt-cache diagnostics, local inference benchmarks
- **Retrieval** — RAG with reranking, Korean documents

#### Projects

<!-- projects:start -->
| Project | Type | What it does |
|---|---|---|
| [cache-autopsy](https://github.com/LeeGyeongPil/cache-autopsy) | tool | Offline CLI that shows prompt cache hit rate, missed tokens and cost, and the likely cause of each miss from stored Anthropic and OpenAI request logs. |
| [pdf-redpen](https://github.com/LeeGyeongPil/pdf-redpen) | tool | CLI and library that ground quotes from an LLM review to real PDF coordinates and mark them as standard highlight and note annotations, with a recall pass for missed issues. |
| [known-secret-guard](https://github.com/LeeGyeongPil/known-secret-guard) | library | Library, CLI and PreToolUse hook that catch known secrets leaving an agent in encoded or split form by matching a precomputed variant set. |
| [llm-format-guard](https://github.com/LeeGyeongPil/llm-format-guard) | library | Dependency-free Python library that extracts format and length instructions from a chat, re-injects them, measures answers deterministically and repairs only when it strictly reduces violations. |
| [ai-lab-llm-eval-gate](https://github.com/LeeGyeongPil/ai-lab-llm-eval-gate) | demo | A dependency-free tool that scores prompt changes on a small test set and fails CI when scores drop below a floor or beyond the noise range. Runs offline by replaying recorded answers. |
| [ai-lab-llm-gateway](https://github.com/LeeGyeongPil/ai-lab-llm-gateway) | demo | Call several LLM providers through one interface, swap models by config, and try retry, fallback and routing. Compare tokens, estimated cost and latency per call. Mock mode needs no API key. |
| [ai-lab-local-llm-bench](https://github.com/LeeGyeongPil/ai-lab-local-llm-bench) | demo | Benchmark a local Ollama server with one command and see how input length and concurrency affect TTFT, tokens/s and memory. A keyless mock mode replays recorded timings. Quantization comparison and charts come in later milestones. |
| [ai-lab-agent-loop-mcp](https://github.com/LeeGyeongPil/ai-lab-agent-loop-mcp) | demo | A demo and beginner guide that shows an AI agent loop live: each thought, MCP tool call and observation on a timeline. Runs with a mock model or local Ollama. |

All 10 projects with Korean descriptions: [**ai-lab catalog**](https://github.com/LeeGyeongPil/ai-lab)
<!-- projects:end -->

#### How I build

- Mock mode first: every repo runs end to end without keys or GPUs
- Tests and CI on every repo; numbers in READMEs come from real runs
- Korean-language support where it matters

#### Stack

Python · TypeScript · Node.js · Next.js · Flutter · Docker · AWS · Ollama · MCP
