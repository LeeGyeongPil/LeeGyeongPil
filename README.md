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
| [llm-page-lint](https://github.com/LeeGyeongPil/llm-page-lint) | tool | A CLI and library that deterministically measures eight visual defects in LLM-generated HTML pages using headless Chromium, with JSON/HTML reports and exit codes for CI gates. |
| [mcp-schema-shim](https://github.com/LeeGyeongPil/mcp-schema-shim) | tool | Checks MCP tool input schemas against Gemini, OpenAI strict and Anthropic strict function-calling rules, rewrites them to fit, and restores returned arguments to the original schema shape. |
| [sft-template-lens](https://github.com/LeeGyeongPil/sft-template-lens) | tool | Renders fine-tuning JSONL with a model's real chat template and tokenizer to show loss masks, truncation and format errors before training. Browser and Node CLI. |
| [awsglance](https://github.com/LeeGyeongPil/awsglance) | tool | A read-only web dashboard for one AWS account that shows who changed what, risky settings and what to check now using 12 plain rules; includes a no-credentials practice mode. |
| [cache-autopsy](https://github.com/LeeGyeongPil/cache-autopsy) | tool | Offline CLI that shows prompt cache hit rate, missed tokens and cost, and the likely cause of each miss from stored Anthropic and OpenAI request logs. |
| [ko-copycheck](https://github.com/LeeGyeongPil/ko-copycheck) | tool | Offline CLI that compares a folder of Korean prose submissions and ranks overlaps using winnowing fingerprints and sentence Dice similarity. |
| [pdf-redpen](https://github.com/LeeGyeongPil/pdf-redpen) | tool | CLI and library that ground quotes from an LLM review to real PDF coordinates and mark them as standard highlight and note annotations, with a recall pass for missed issues. |
| [hwpdown](https://github.com/LeeGyeongPil/hwpdown) | library | Pure-Python library and CLI that parses public HWP 5.0 and HWPX specs into Markdown for LLM/RAG, keeping merged tables, footnotes and numbering. |

All 17 projects with Korean descriptions: [**ai-lab catalog**](https://github.com/LeeGyeongPil/ai-lab)
<!-- projects:end -->

#### How I build

- Mock mode first: every repo runs end to end without keys or GPUs
- Tests and CI on every repo; numbers in READMEs come from real runs
- Korean-language support where it matters

#### Stack

Python · TypeScript · Node.js · Next.js · Flutter · Docker · AWS · Ollama · MCP
