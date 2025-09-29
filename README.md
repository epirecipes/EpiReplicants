# EpiReplicants

`EpiReplicants` is a repository of epidemiological models that try to mimic published examples. There are two underlying aims:

1. To demonstrate the ability (or lack thereof) to replicate/reproduce results, which is important for trust in these models and their applications.
2. To highlight the capability of Julia as a language for epidemiological modeling, and to identify gaps in the current ecosystem.
3. As a testbed for the use of large language models to perform the following transformations:
   - Publication \leftarrow equations
   - Publication \leftarrow pseudocode
   - Publication \leftarrow code
   - Code (e.g. in R) to code in Julia

## List of replicants

## Guidelines

- The implementation should be in Julia
- Written as a Quarto document
- In a subdirectory with its own environment
- Preferably based on an open publication where the code is available under a permissive license
- Where artificial intelligence has been used, the prompts and local setup (e.g. GitHub Copilot + VS Code + GPT-5) should be described.
