### CoT Empowers Transformers to Solve Inherently Serial Problem
- **date**: Sep. 23, 2025
- **tag**: cot, reasoning, theory
- **arxiv**: https://arxiv.org/abs/2402.12875
- **tldr**: a theory paper to show 1) the problem solvable to constant depth transformer has a limit; 2) Cot can greatly exapnd the range especailly for inherently serial problems (e.g. circuit value problem).
- **why-interesting**: an interesting way to explain why cot is good and necessary: since some problems have to be solved "step by step". 
- **follow-up**: cot (or thinking mode) is one of the primary way today to push the limit of llms, good to see how people are teach model to "think" correctly and efficiently. good to think about why cot works and in which case it works the best.

### MCP-Bench
- **date**: Sep. 22, 2025
- **tag**: eval, agent, mcp, dataset
- **arxiv**: https://www.arxiv.org/abs/2508.20453
- **tldr**: A new agent benchmark with a larger number of MCP servers and tools. Together with a synthetic prompt eval set, rule + llm judges, and eval results.
- **why-interesting**: not sure about their eval set's quality, but interesting to see how everything is set up. They also introduced metrics to measure trajectory efficency, which is new for agent eval (compared to non-agent eval).
- **follow-up**: there are a lot of other benchmarks, maybe good to take a quick survey
