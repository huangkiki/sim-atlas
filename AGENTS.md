# Sim Atlas hub maintenance

- Use autodev for repository development and recover current work before creating duplicate issues or branches.
- This repository owns the learning homepage, shared vocabulary and reading routes. Engine-specific implementation lessons remain in their six repositories; experiments and evidence remain in DexLab.
- The user requested one worker per engine with a supervising main agent. Respect available concurrency, keep one writer per repository, and report actual active/queued status.
- The supervisor reviews each delivered slice against its issue and pinned source, verifies the published commit and applicable CI, then reassesses dependencies and dispatches the next task.
- Update Chinese and English entry/status together. Published coverage requires delivered repository content, not a worker's draft or a closed issue alone.
- Keep source study, syntax checks, native execution and physics qualification separate. No new experiments, training, benchmarks or scoring infrastructure in this course phase.
- Keep the design direct: no cross-engine runtime wrapper, duplicate curriculum bodies, or speculative website framework. The README is the current home; a documentation website may be added later when requested.
- Run `git diff --check` and `python scripts/check_docs.py`; verify upstream links and manually inspect changed graphics. Do not claim visual or runtime checks that were not performed.
- Follow the user's existing publication and Obsidian synchronization authorization. Repository text does not grant new merge, release or scheduling permission.
