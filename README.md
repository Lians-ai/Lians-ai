<p align="center">
  <a href="https://github.com/Lians-ai/Lians">
    <img src="https://raw.githubusercontent.com/Lians-ai/Lians/master/plugins/lians-memory/assets/icon.png" width="112" alt="Lians lotus logo">
  </a>
</p>

<h1 align="center">Memory for any AI agent.</h1>

<p align="center">
  Open source. Local-first. Provider-neutral.
</p>

<p align="center">
  <a href="https://github.com/Lians-ai/Lians"><strong>View the repository</strong></a>
  ·
  <a href="https://www.lians.ai/docs">Read the docs</a>
  ·
  <a href="https://lians-memory.hashnode.dev/give-any-ai-agent-persistent-memory-locally">Five-minute setup</a>
  ·
  <a href="https://github.com/Lians-ai"><strong>Follow @Lians-ai</strong></a>
</p>

Lians gives AI agents durable memory across chats, sessions, tools, and models. Your agent stays the same; Lians gives it a shared place to remember.

- Runs locally with SQLite and needs no Lians account or API key.
- Works through MCP, plugins, and Python or TypeScript SDKs.
- Lets people inspect, correct, and explicitly delete stored memory.
- Licensed under Apache 2.0 and developed in public.

### Try the two-chat test

Gemini CLI users can install Lians directly from GitHub:

```bash
gemini extensions install https://github.com/Lians-ai/Lians
```

In any compatible agent with Lians configured, say:

```text
Remember that this project uses Python 3.12 and pytest.
```

Open a new chat and ask:

```text
What Python version and test runner does this project use?
```

If setup is confusing or recall fails, [open an issue](https://github.com/Lians-ai/Lians/issues/new/choose). If Lians solves a real problem for you, [star the repository](https://github.com/Lians-ai/Lians).
