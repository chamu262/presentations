# From Prompts to Agent Teams: speaker notes

## 1. From prompts to agent teams

Open with the contrast: most prompt talks teach phrases. This one is about the system around the prompt. Everything shown runs on made-up demo data, and every repo is public, so the audience can try it tonight.

## 2. Prompt tricks were 2023’s answer

Acknowledge the classic prompt-pattern talks: they were right for their time. Then make the turn. With reasoning models, “think step by step” adds little, and a persona line changes tone more than accuracy. What changes outcomes is the system around the model.

## 3. From the sentence to the system

Walk the table row by row. Each “then” is a technique from the classic prompt talks; each “now” is where that idea moved. The right column is the demo we’ll look at for it.

## 4. Context beats clever prompts

A skill is a prompt you write once, with a description that tells the model when to use it. That “use when” line does the job the persona and recipe patterns used to do, without pasting anything. Show the three skills in the godfather repo.

## 5. Give it tools, read-only first

Few-shot examples were a way to show the model the shape of your data. Tools give it the data itself. Demo: ask Claude which devices are non-compliant; it calls the MCP server and answers from the demo data. Point out that the adapter interface has no write methods, and a test checks that.

## 6. Agents propose, people approve

This is the step most prompt talks skip: what happens when the model is wrong. The answer isn’t a better prompt, it’s a gate. Show the queue, approve one change and reject another, and show that the demo only simulates the change.

## 7. Rules decide, AI explains

Don’t ask a model to make a decision a rule can make. Seven deterministic rules find the problems; Claude explains them in plain words for the reviewer. Run it with no API key in mock mode, then with Claude mode, and compare.

## 8. From one agent to a team

The persona pattern grown up: instead of one model pretending to be an expert, several agents each own one area. Show a request being routed (the grey line says who it went to and why), then approve one item. It runs with no API key on demo data.

## 9. Check the work, not the claim

“Think step by step” was about getting better reasoning. Now the model reasons anyway; the job left for us is checking. Show a confidence footer that names what was verified and what wasn’t, and the dashboard flagging two sessions editing the same file.

## 10. A prompt for 2026

No persona, no “think step by step”. Six lines: the goal, where the context lives, the limits, what done means, how to check it, and how to report. Most of the weight is in the system already: the instructions file, the tools and the approval gate.

## 11. Write the system, not the sentence.

Pause here. If the audience keeps one thing: spend the effort on instructions files, skills, tools, approval gates and checks. They work on every prompt you’ll ever write, not just one.

## 12. Six things to try this week

Each card maps to a demo the audience can clone. Ask them to pick just one to try this week.

## 13. All five demos are open source

Leave this slide up for questions. Every repo is on github.com under chamu262; most run with one command and no API key.
