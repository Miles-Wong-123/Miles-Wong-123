<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:D97757,50:E8956F,100:C15F3C&height=200&section=header&text=Hey%20there%2C%20I'm%20Maoyu&fontSize=60&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=%E2%98%95%20Code%20%C2%B7%20Coffee%20%C2%B7%20Curiosity&descSize=18&descAlignY=60" width="100%" />

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=22&duration=3000&pause=1000&color=D97757&center=true&vCenter=true&width=720&lines=Just+a+human+who+writes+code+and+drinks+coffee+%E2%98%95;Currently+obsessed+with+LLM+Agents+%F0%9F%A4%96;I+build+things%2C+break+things%2C+learn+things+%F0%9F%9B%A0%EF%B8%8F;Java+on+weekdays%2C+curiosity+all+week+%E2%9C%A8" alt="Typing SVG" />
</a>

</div>

<br/>

## 👋 Hello, World

I'm **Maoyu** — a CS grad student who got nerd-sniped by large language models somewhere along the way.

I spend my days wiring up agents that can think a little, remember a lot, and occasionally surprise me. When I'm not doing that, I'm probably reading about distributed systems, brewing pour-over coffee, or wondering why my code worked yesterday but not today.

```yaml
🎓 currently  : Master's in CS @ The University of Hong Kong
🌱 before that: Electronic Information Engineering @ BUPT
🤖 obsessed by: LLM agents, RAG, MCP, and the magic of emergence
🛠️ comfortable: Java, Spring ecosystem, distributed messaging, Netty
☕ powered by : pour-over coffee and unreasonable curiosity
💭 belief     : the best engineers are the most patient debuggers
```

<br/>

## 🧪 What I'm Tinkering With

<table>
<tr>
<td valign="top" width="50%">

### 🤖 An Agent that Actually Remembers
> Trying to build something smarter than a chatbot

<p>
  <img src="https://img.shields.io/badge/Java_17-D97757?style=flat-square&logoColor=white" />
  <img src="https://img.shields.io/badge/LangChain4j-C15F3C?style=flat-square" />
  <img src="https://img.shields.io/badge/PgVector-E8956F?style=flat-square" />
  <img src="https://img.shields.io/badge/MCP-D97757?style=flat-square" />
  <img src="https://img.shields.io/badge/Redis-C15F3C?style=flat-square" />
</p>

A LangChain4j-based agent system that tries to actually be useful. It can read your docs, remember conversations across sessions, send emails on your behalf, and politely refuse when someone tries to jailbreak it.

The fun bits:
- **RAG with PgVector** — semantic chunking + dense retrieval so it doesn't hallucinate (much)
- **Self-evolving memory** — tell it something new in plain language, it syncs to the vector store
- **Distributed sessions** — Redis + `MemoryId` so 1000 users don't accidentally read each other's chats
- **Tool calling** — `@Tool` annotations turn natural language into actual function calls
- **Guardrails** — sensitive-word filter & prompt-injection detection at the input layer

</td>
<td valign="top" width="50%">

### 💬 A Chat App that Doesn't Drop Messages
> Because WebSocket alone isn't enough

<p>
  <img src="https://img.shields.io/badge/Netty-D97757?style=flat-square" />
  <img src="https://img.shields.io/badge/Kafka-C15F3C?style=flat-square" />
  <img src="https://img.shields.io/badge/Spring_Cloud-E8956F?style=flat-square" />
  <img src="https://img.shields.io/badge/MySQL-D97757?style=flat-square" />
  <img src="https://img.shields.io/badge/Redis-C15F3C?style=flat-square" />
</p>

A distributed instant messaging app I built when I was curious how WhatsApp-scale systems actually stay reliable. Turns out it's mostly Kafka and a lot of edge cases.

The fun bits:
- **Netty gateway** — long-lived connections with heartbeats & ACK confirmation
- **Consistent hashing** — figures out which server holds your connection
- **Snowflake IDs** — globally unique without a central coordinator
- **Kafka partitioning** — keeps group messages in order at high throughput
- **Lua-backed red envelopes** — atomic deduction, auto-expiry, no double-spending
- **Two-tier cache** — Redis + local cache because every millisecond matters

</td>
</tr>
</table>

<br/>

## 🛠️ My Toolbox

<table>
<tr>
<td valign="top" width="50%">

**🤖 Where the magic happens**

![Java](https://img.shields.io/badge/Java-D97757?style=for-the-badge&logo=openjdk&logoColor=white)
![LangChain4j](https://img.shields.io/badge/LangChain4j-C15F3C?style=for-the-badge&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-E8956F?style=for-the-badge&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-D97757?style=for-the-badge&logoColor=white)
![PgVector](https://img.shields.io/badge/PgVector-C15F3C?style=for-the-badge&logoColor=white)

**☕ My daily drivers**

![SpringBoot](https://img.shields.io/badge/Spring_Boot-D97757?style=for-the-badge&logo=springboot&logoColor=white)
![SpringCloud](https://img.shields.io/badge/Spring_Cloud-C15F3C?style=for-the-badge&logo=spring&logoColor=white)
![MyBatis](https://img.shields.io/badge/MyBatis-E8956F?style=for-the-badge&logoColor=white)
![Netty](https://img.shields.io/badge/Netty-D97757?style=for-the-badge&logoColor=white)

</td>
<td valign="top" width="50%">

**🗄️ Where data lives**

![MySQL](https://img.shields.io/badge/MySQL-D97757?style=for-the-badge&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-C15F3C?style=for-the-badge&logo=redis&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-E8956F?style=for-the-badge&logo=postgresql&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-D97757?style=for-the-badge&logo=apachekafka&logoColor=white)
![RocketMQ](https://img.shields.io/badge/RocketMQ-C15F3C?style=for-the-badge&logoColor=white)

**🐳 The plumbing**

![Docker](https://img.shields.io/badge/Docker-D97757?style=for-the-badge&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-C15F3C?style=for-the-badge&logo=linux&logoColor=white)
![Git](https://img.shields.io/badge/Git-E8956F?style=for-the-badge&logo=git&logoColor=white)
![Nacos](https://img.shields.io/badge/Nacos-D97757?style=for-the-badge&logoColor=white)

</td>
</tr>
</table>

<br/>

## 📊 The Numbers (if you're into that)

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=Miles-Wong-123&show_icons=true&hide_border=true&bg_color=FAF9F5&title_color=D97757&icon_color=C15F3C&text_color=3D3929&include_all_commits=true&count_private=true" />
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Miles-Wong-123&layout=compact&hide_border=true&bg_color=FAF9F5&title_color=D97757&text_color=3D3929&langs_count=8" />

<br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=Miles-Wong-123&hide_border=true&background=FAF9F5&stroke=D97757&ring=C15F3C&fire=D97757&currStreakLabel=D97757&sideLabels=3D3929&dates=3D3929&currStreakNum=3D3929&sideNums=3D3929" />

<br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Miles-Wong-123&bg_color=FAF9F5&color=D97757&line=C15F3C&point=3D3929&hide_border=true&area=true" width="98%" />

</div>

<br/>

## 🌱 Things I'm Thinking About Lately

- How do you make agents that **don't lie** about what they did?
- Is RAG just a stopgap, or the future of memory? (probably both)
- Why does every distributed system eventually reinvent message queues?
- The line between "framework" and "abstraction leak" gets thinner every year
- ~~How to make my code work~~ Why my code stopped working

<br/>

## 📬 Say Hi

If anything here resonates, or you just want to swap notes on agents, distributed systems, or coffee brewing methods — my inbox is open.

<p>
  <a href="mailto:1471506321@qq.com">
    <img src="https://img.shields.io/badge/Email-D97757?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://github.com/Miles-Wong-123">
    <img src="https://img.shields.io/badge/GitHub-3D3929?style=for-the-badge&logo=github&logoColor=white" />
  </a>
</p>

<br/>

<div align="center">

<em>"The best way to predict the future is to build it — one commit at a time." ☕</em>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:C15F3C,50:E8956F,100:D97757&height=100&section=footer" width="100%" />

</div>
