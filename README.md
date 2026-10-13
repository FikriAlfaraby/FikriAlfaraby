### Fikri Alfaraby

Full-stack engineer in Bandung, Indonesia (UTC+7), open to remote work.
I'm Product Tech Lead at Ordonesia, where I own a B2B chat, WhatsApp broadcast and ticketing platform end to end: data model, NestJS services, Next.js/TypeScript frontend.

**Things I built recently**

- [**oracle-mutants**](https://github.com/FikriAlfaraby/oracle-mutants): mutation testing for AI benchmark graders. It breaks a task's reference answer in hundreds of small ways, reruns the real verifier on each, and reports what still scores full marks. On Terminal-Bench it found a verifier gap nobody had reported ([terminal-bench#2243](https://github.com/harbor-framework/terminal-bench/issues/2243)). Write-up: [Do benchmark verifiers reject wrong answers?](https://fikrialfaraby.com/notes/verifier-mutants/)
- [**terminal-bench-id**](https://github.com/FikriAlfaraby/terminal-bench-id): three Indonesian-language Terminal-Bench tasks (Javanese calendar, rupiah and messy encodings, pre-1972 spelling with Unicode noise). Each has a deterministic verifier, and a trap validator injects 11 typical agent mistakes to confirm every one is caught.
- [**wa-lead-extractor**](https://github.com/FikriAlfaraby/wa-lead-extractor): an LLM pipeline for WhatsApp sales leads. Every extracted fact must cite its source message or it is dropped. LLM-as-judge evals run in CI, and a human approves each outgoing message. 57 tests.
- [**ai-visibility-scan**](https://github.com/FikriAlfaraby/ai-visibility-scan): measures which brands LLMs recommend, across models, with resumable runs and rate-limit-aware retries.

**Stack:** TypeScript · Node.js · NestJS · Next.js · React · MongoDB · PostgreSQL · Prisma · Docker · Traefik · Python. I work AI-native with Claude Code (sub-agents, hooks, skills) and hold that output to the same review and test bar as hand-written code.

[fikrialfaraby.com](https://fikrialfaraby.com) · [LinkedIn](https://www.linkedin.com/in/fikri-alfaraby) · fikrialfaraby04@gmail.com
