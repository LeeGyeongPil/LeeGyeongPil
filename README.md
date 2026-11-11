### 이경필 (Gyeongpil Lee)

LLM 앱을 만들다 "이런 도구 하나 있으면 좋겠다" 싶던 것을 직접 만들어 오픈소스로 공개합니다.<br>
I build small open-source tools for the parts of LLM apps that are easy to skip: output checks, evals, RAG and local models.

**요즘 보는 것**

- 출력·도구 호출 검증 — 스키마 변환, tool-call 프로토콜, 가드레일 비교
- 평가 — LLM 심판 일치도, 임베딩 A/B, RAG 재현율
- 로컬 LLM 운영 — Ollama, LoRA, 컨텍스트 창
- 한국어 처리 — 개인정보 가명화, TTS 읽기 변환, 한글 입력 테스트

대부분 API 키 없이 모의 모드로 바로 돌려 볼 수 있고, 테스트·CI와 MIT 라이선스가 함께 있습니다.

#### Projects

<!-- projects:start -->
- [agreelens](https://github.com/LeeGyeongPil/agreelens): LLM 심판과 사람 라벨의 일치도 검증
- [modelfile-doctor](https://github.com/LeeGyeongPil/modelfile-doctor): Ollama Modelfile 검사기
- [guarddiff](https://github.com/LeeGyeongPil/guarddiff): 가드레일 켜고 끄기 비교 평가 도구
- [handoffmap](https://github.com/LeeGyeongPil/handoffmap): 에이전트 추적을 위임 흐름도로 접기
- [litellm-lint](https://github.com/LeeGyeongPil/litellm-lint): LiteLLM 프록시 설정 검사기
- [llm-batchkit](https://github.com/LeeGyeongPil/llm-batchkit): LLM Batch API 파일 검사·분할·병합·재시도 도구
- [loraport](https://github.com/LeeGyeongPil/loraport): LoRA 어댑터 형식 변환·검증
- [ollama-ctxguard](https://github.com/LeeGyeongPil/ollama-ctxguard): Ollama 컨텍스트 창 가드 프록시

전체 49개 목록은 [ai-lab](https://github.com/LeeGyeongPil/ai-lab)에 있습니다.
<!-- projects:end -->

Python · TypeScript · Dart
