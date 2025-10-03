# Expert Practices in AI Coding

This section collects **real experiences from expert programmers** using AI-assisted coding tools (Copilot, Claude Code, Cursor, ChatGPT, etc.).  
Unlike a generic resource list, each entry is based on **first-hand experience** and includes **distilled takeaways**. This is an intentional bias:
- I only add resources I have gone through myself.
- I only include experts I trust in some way.
- The distilled takeaways are very rough summaries and cannot replace the original text.

Entries are sorted in **reverse chronological order** (latest first).

## Entries

## 2025-09

- [Designing agentic loops](https://simonwillison.net/2025/Sep/30/designing-agentic-loops/) [@simonw](https://github.com/simonw)
  - > A critical new skill to develop is designing agentic loops.
  - > Any time you find yourself thinking “ugh, I’m going to have to try a lot of variations here” is a strong signal that an agentic loop might be worth trying!



### 2025-08

- [Your MCP Doesn't Need 30 Tools: It Needs Code](https://lucumr.pocoo.org/2025/8/18/code-mcps/) [@mitsuhiko](https://github.com/mitsuhiko)
  - Let AI use tools through code rather than MCP interfaces
  - AI understands code better than tool abstractions

### 2025-07
- [Vibe coding in prod | Code w/ Claude](https://www.youtube.com/watch?v=fHWFF_pnqDk) [@anthropics](https://github.com/anthropics)
  - Act as Claude's PM asking right questions, use Claude for leaf nodes not core infrastructure, ensure verifiability through testing
  - Line-by-line code review won't scale with exponential AI capabilities - need abstraction layers for verification without knowing implementation details

### 2025-06

- [How I Vibe Coding?](https://xuanwo.io/2025/03-how-i-vibe-coding/) [@Xuanwo](https://github.com/Xuanwo)
  - Treat coding agents like interns in isolated environments
  - Spend most time on code review rather than writing
  - Use testing frameworks to improve agent code quality

- [Agentic Coding Recommendations](https://lucumr.pocoo.org/2025/6/12/agentic-coding) [@mitsuhiko](https://github.com/mitsuhiko)
  - Tools must be fast, user-friendly, and protected against LLM chaos
  - Programming paradigm shift: building workflows rather than writing code
  - Focus on speed, stability, simplicity, and parallelizable tasks

- [How I Use Claude Code](https://spiess.dev/blog/how-i-use-claude-code) [@philipp-spiess](https://github.com/philipp-spiess)
    - Clear conversations frequently and provide extensive context - treat Claude like an "amnesiac new grad"
    - Incremental development with tight feedback loops works better than complex one-shot prompts

- [Claude Code is My Computer](https://steipete.me/posts/2025/claude-code-is-my-computer) [@steipete](https://github.com/steipete)
  - Coding agents as AI OS engines capable of complex multi-step tasks
  - Can do anything a human user can do in Linux through the CLI
  - Represents new paradigm for human-computer interaction

### 2025-05

- [Amp Is Now Available. Here Is How I Use It.](https://ampcode.com/how-i-use-amp) [@mrnugget](https://github.com/mrnugget)
    - Keep conversations small to avoid context window bloat - start new threads frequently rather than continuing long conversations
    - "Paint-by-numbers programming" - human handles architecture and planning, agent implements with detailed prompts containing constraints and edge cases

### 2025-03

- [Not all AI-assisted programming is vibe coding (but vibe coding rocks)](https://simonwillison.net/2025/Mar/19/vibe-coding/) [@simonw](https://github.com/simonw) 
    - Vibe coding is for throwaway projects where you "forget code exists"
    - Best tool for experienced developers to build intuition about LLM capabilities
    - Different from production AI-assisted programming

- [Here’s how I use LLMs to help me write code](https://simonwillison.net/2025/Mar/11/using-llms-for-code/) [@simonw](https://github.com/simonw) 
    - LLMs respond extremely well to function signatures - you design the interface, LLM fills the implementation
    - LLMs are less lazy than humans - they catch exceptions, add docstrings, and type annotations
    - Enables building features that would otherwise be too time-consuming to attempt

## Notes

- **Focus:** Expert practice, not tool lists or news.  
- **Format Example:**
```

YYYY-MM

- [Title](link) [@author](https://github.com/author)

  - takeaway 1
  - takeaway 2

```
- **Update:** Add new entries in reverse chronological order.

- In case the link is broken, you can try to find the resource in the [web archive](https://web.archive.org/).