<!-- GitHub profile README for aritraghosh215
     Create a PUBLIC repo named exactly "aritraghosh215" and put this file in it as README.md.
     Search for "TODO" and fill in your own links. Colours: violet #7c5cff, deep violet #4c3a9e, teal #0ea5a4. -->

<img width="100%" alt="header" src="https://capsule-render.vercel.app/api?type=waving&color=0:ffffff,55:ede9fe,100:c4b5fd&height=190&section=header&text=Hi%2C%20I'm%20Aritra&fontSize=46&fontColor=4c3a9e&fontAlignY=40&desc=I%20build%20AI%20agents%20that%20ship%20to%20production&descAlignY=62&descSize=18&descColor=6d5bd0" />

<div align="center">

<a href="https://github.com/aritraghosh215">
  <img alt="typing" src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=21&duration=3000&pause=900&color=7C5CFF&background=FFFFFF&center=true&vCenter=true&width=560&lines=Full-Stack+AI+Engineer;Multi-agent+systems+%7C+LangGraph+%7C+MCP;RAG+%2B+evals+%2B+real+deployments;The+AI+drafts.+People+approve." />
</a>

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/aritra-ghosh-041346420)
[![Email](https://img.shields.io/badge/Email-7c5cff?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ghosharitra18@gmail.com)
[![Resume](https://img.shields.io/badge/Resume-0ea5a4?style=for-the-badge&logo=googledrive&logoColor=white)](https://drive.google.com/YOUR-RESUME-LINK)
[![YouTube](https://img.shields.io/badge/Video_tours-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtu.be/bsqNIGMt4wU)

</div>

<br/>

## About me

I'm a full-stack AI engineer. I build agent products end to end: the backend, the tools the agents call, the UI, and the guardrails. Each project below is deployed, tested and has a video tour.

My rule of thumb: **the AI drafts, the system verifies, a person approves.**

<br/>

## Three projects

<table>
<tr>
<td width="38%" valign="top">
<a href="https://youtu.be/bsqNIGMt4wU"><img src="https://img.youtube.com/vi/bsqNIGMt4wU/maxresdefault.jpg" alt="OpsPilot video" width="100%"></a>
</td>
<td valign="top">

### OpsPilot
AI agents investigate a production incident, test several theories in parallel, and propose one fix. Nothing runs until you approve it.

`LangGraph` `MCP` `Django` `React`

[Live demo](https://opspilot-two-smoky.vercel.app) · [4 min video](https://youtu.be/bsqNIGMt4wU) · [Code](https://github.com/aritraghosh215/opspilot)

</td>
</tr>
<tr>
<td width="38%" valign="top">
<a href="https://youtu.be/rpPOwjLgjhA"><img src="https://img.youtube.com/vi/rpPOwjLgjhA/maxresdefault.jpg" alt="QuotePilot video" width="100%"></a>
</td>
<td valign="top">

### QuotePilot
Type a request in plain English and get a priced B2B quote. The AI drafts it, the server does the maths, and big discounts wait for a manager.

`LangGraph` `Django` `Pinecone` `React`

[Live demo](https://audiquotepilot.onrender.com/) · [3 min video](https://youtu.be/rpPOwjLgjhA) · [Code](https://github.com/aritraghosh215/quotepilot_audi)

</td>
</tr>
<tr>
<td width="38%" valign="top" align="center">
<br/><br/>
<b>RAG<br/>benchmark<br/>dashboard</b>
<br/><br/>
</td>
<td valign="top">

### SupportBench RAGOps
Compares models and retrieval settings for a support chatbot, then recommends which setup to ship based on quality, cost, speed and risk.

`FastAPI` `Next.js` `Pinecone` `BM25` `Evals`

[Code](https://github.com/aritraghosh215/supportbench-ragops) <!-- TODO: correct repo name, add live demo / video links when ready -->

</td>
</tr>
</table>

<br/>

## Play: Incident Commander

You're on call. Three alerts, one decision each. Click a round, then pick an answer.

<details>
<summary><b>Round 1:</b> The error rate on <code>checkout-api</code> jumped to 11% right after a deploy.</summary>

<br/>

<details><summary>A. Roll back to the previous version</summary>

**Correct.** A bad deploy plus a spike right after it points to the release. The safe move is a rollback, and you should check the error rate afterwards to prove it worked.
</details>

<details><summary>B. Restart every server</summary>

**Not quite.** A restart can't undo a bad release, and you would drop live traffic for nothing.
</details>

<details><summary>C. Wait and watch for an hour</summary>

**Not quite.** Customers are failing at checkout right now. Waiting costs money.
</details>

</details>

<details>
<summary><b>Round 2:</b> The AI agent suggests deleting a database table to "clean up". What do you do?</summary>

<br/>

<details><summary>A. Approve, the AI is usually right</summary>

**Not quite.** Writes that can't be undone need a human check and a dry run first.
</details>

<details><summary>B. Block it and ask for a dry run with evidence</summary>

**Correct.** This is the OpsPilot rule: agents get read-only tools, every write starts as a dry run, and a person makes the call.
</details>

<details><summary>C. Ignore the suggestion</summary>

**Not quite.** Ignoring it leaves no record. Rejecting it with a note keeps an audit trail.
</details>

</details>

<details>
<summary><b>Round 3:</b> A customer asks the AI for a 40% discount. Who sets the final price?</summary>

<br/>

<details><summary>A. The language model</summary>

**Not quite.** Models are bad at exact arithmetic and can be talked into anything.
</details>

<details><summary>B. The customer</summary>

**Not quite.** Nice try.
</details>

<details><summary>C. The server, with a manager approving big discounts</summary>

**Correct.** That's QuotePilot: the AI drafts, the backend prices from the catalog, and discounts above policy wait for approval.
</details>

</details>

<details>
<summary><b>Your score</b></summary>

<br/>

**3 out of 3:** you'd get hired as my on-call engineer. [Send me a message](mailto:ghosharitra18@gmail.com).<br/>
**1 or 2:** not bad. Watch the [OpsPilot tour](https://youtu.be/bsqNIGMt4wU) and play again.<br/>
**0:** please don't touch production.

</details>

<br/>

## Tech I use

<div align="center">

<img src="https://skillicons.dev/icons?i=python,django,fastapi,react,nextjs,ts,tailwind,postgres,docker,git,githubactions,vercel&theme=light" alt="tech icons" />

</div>

| Area | Tools |
|--|--|
| **AI** | LangGraph, OpenAI, MCP, RAG, Pinecone, evals |
| **Backend** | Python, Django, FastAPI, PostgreSQL |
| **Frontend** | React, Next.js, TypeScript, Tailwind |
| **Ship** | Docker, GitHub Actions, Render, Vercel, Neon |

<br/>

## GitHub stats

<div align="center">

<img height="160" alt="stats" src="https://github-readme-stats.vercel.app/api?username=aritraghosh215&show_icons=true&hide_border=true&bg_color=FFFFFF&title_color=7C5CFF&icon_color=7C5CFF&text_color=374151&count_private=true" />

</div>

<br/>

<div align="center">

**Open to AI Engineer and GenAI Engineer roles.** Let's talk.

<img width="100%" alt="footer" src="https://capsule-render.vercel.app/api?type=waving&color=0:c4b5fd,55:ede9fe,100:ffffff&height=110&section=footer" />

</div>
