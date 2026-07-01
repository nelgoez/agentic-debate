# Agentic Debate

A structured multi-agent role-play skill for OpenCode / Claude Code. Debates 2-3 options with real web research (Tavily) and delivers a synthesized recommendation.

## Usage

In any OpenCode or Claude Code session:

```
/agentic-debate
```

The skill will:
1. Ask clarifying questions to frame the decision
2. Define 2-3 options with agent personas
3. Dispatch subagents to research via Tavily
4. Synthesize results with a comparison table
5. Present a recommendation

## Install

```bash
npx skills add nelgoez/agentic-debate
```

Or copy `SKILL.md` into `.claude/skills/agentic-debate/` in your project.

## Requirements

- OpenCode or Claude Code
- Tavily MCP configured (for web research)
- Tavily API key in environment
