# Lab 03: Tooling with MCP & Copilot CLI


## Advanced Scenarios with Work IQ in GitHub Copilot CLI

You can run Work IQ inside GitHub Copilot CLI via MCP protocol.

Run the following command, to start GitHub Copilot

```
copilot --banner
```

If prompted, trust GitHub Copilot to access the files in your current folder.

Now, run the following prompt:

```
What are my meetings for next week? List all of them sorted by date and help me prepare for them.
```

GitHub Copilot will analyze your prompt and determine that the **ask_work_iq** MCP tool is needed to provide you with an answer. As such, it will ask your consent to use the tool. You can say **1. Yes** to consent it just once, or **2. Yes, and don't ask again for tool "ask_work_iq" from "workiq" in this repo** if you want to consent it from now on. Of course, you can also choose **3. No** and avoid using Work IQ.

If you consented, GitHub Copilot will start processing your request and will talk with the Work IQ MCP server to extract to requested information.

The response will be a list of events in your calendar for next week, including some useful information to prepare for them.

Now let's try with something more complex. Provide the following prompt to GitHub Copilot:

```
Generate a MD document with the information you just retrieved
```

GitHub Copilot will ask your consent to save the Markdown document in the local folder where you are running it.

## Complex Productivity Scenario with Work IQ and GitHub Copilot CLI



## Where to go next

- **Explore the IQ Series** — Continue learning with [Episode 2: Work IQ: A2A for Context‑Aware, Agentic Experiences](../../2-Work-IQ-A2A-for-Context‑Aware-Agentic-Experiences/) and [Episode 3: Tooling with MCP & Copilot CLI](../../3-Work-IQ-Tooling-with-MCP-and-Copilot-CLI/).