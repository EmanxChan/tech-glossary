# Tech Glossary

A plain-English dictionary of technical terms for non-technical people.

---

## Vector Database (Vector DB)
**What it is:** A special kind of database that stores information as "vectors" — basically, lists of numbers that represent the *meaning* of text, not just the words themselves.

**Analogy:** Imagine you could turn every book in a library into a GPS coordinate. Books about similar topics would be close together on the map. A vector database lets you find "books near this topic" even if they don't use the exact same words.

**Why it matters:** It lets computers understand *concepts* and find similar ideas, not just exact word matches. We use Qdrant as our vector database.

**Related terms:** Embedding, Semantic Search, Qdrant

---

## Embedding
**What it is:** The process of turning words, sentences, or documents into a list of numbers (a vector) that captures their meaning.

**Analogy:** Think of it like translating a poem into a secret code. Two poems with similar emotions would have similar codes, even if they use different words. The embedding is that secret code.

**Example:** The sentences "The king sat on the throne" and "The monarch occupied the palace" would have very similar embeddings because they mean similar things, even though the words are different.

**Why it matters:** Once text is turned into numbers, computers can compare meanings mathematically — finding similar ideas even when the words don't match.

**Related terms:** Vector, Vector Database, all-MiniLM-L6-v2

---

## Semantic Search
**What it is:** Searching by *meaning* instead of exact words. Regular search finds "apple" when you type "apple." Semantic search finds "fruit," "iPhone," or "the company that makes Macs" because it understands those concepts are related.

**Analogy:** Regular search is like looking for a specific phone number in a phone book. Semantic search is like asking a knowledgeable friend "Who's that tall guy who fixes cars?" and they know you mean Mike from down the street.

**Why it matters:** You don't need to remember exact words or phrases — you can describe what you're looking for and find it anyway.

**Related terms:** Embedding, Vector Database, LLM

---

## Qdrant
**What it is:** An open-source vector database. It's the software that stores and searches our "meaning codes" (embeddings) locally on your computer.

**Analogy:** If embeddings are like translating books into GPS coordinates, Qdrant is like Google Maps — it stores all those coordinates and quickly finds "what's near here."

**Why it matters:** Qdrant runs entirely on your machine. No data leaves your computer. It's how we do "smart search" while keeping everything private.

**Related terms:** Vector Database, Embedding, Local Model

---

## Local Model
**What it is:** AI software that runs entirely on your own computer instead of calling out to the internet (the "cloud").

**Analogy:** It's the difference between having a calculator on your desk versus calling a math hotline every time you need to add numbers. The local calculator is faster, works without internet, and nobody else sees what you're calculating.

**Why it matters:** Privacy. Your data never leaves your machine. Also works offline and doesn't cost per-use like cloud APIs.

**Our local models:**
- `all-MiniLM-L6-v2` — for turning text into embeddings (semantic meaning)
- Local LLMs (like Kimi, via OpenRouter) — for generating responses

**Related terms:** Cloud API, Embedding, Privacy

---

## all-MiniLM-L6-v2
**What it is:** The name of the specific AI model we use to turn text into embeddings. It's made by Microsoft (the "MiniLM" part) and is small and fast (the "L6-v2" part means it's the 6-layer version 2).

**Analogy:** Think of it as a specific brand of measuring tape. Many brands exist, but this one is accurate, compact, and fast — perfect for our needs.

**Why it matters:** It creates 384-dimensional vectors (meaning codes) that capture the meaning of text. It's "small" by AI standards (~80MB) so it runs fast on your MacBook without needing a powerful GPU.

**Related terms:** Embedding, Local Model, Vector

---

## Cron Job
**What it is:** A scheduled task on your computer. "Cron" is a Unix/Linux program that runs things at specific times or intervals.

**Analogy:** It's like setting an alarm clock that doesn't just make noise — it actually does work. "Every morning at 9 AM, check my email" or "Every hour, clean up old files."

**Examples we use:**
- Daily health check at 9:00 AM
- Memory compaction every 2 hours
- Gateway watchdog every 5 minutes

**Related terms:** Automation, Scheduler

---

## Gateway (OpenClaw Gateway)
**What it is:** A background program that runs on your computer, waiting for connections. It's how OpenClaw receives messages from Telegram and other services.

**Analogy:** Like a receptionist at an office. They sit at the front desk, ready to receive visitors (messages) and route them to the right person (your AI agent). Even when you're not there, the receptionist is.

**Why it matters:** It needs to run 24/7 so Telegram can reach you even when your computer is asleep. It's the "always-on" part of the system.

**Related terms:** Daemon, Background Process, Port

---

## Daemon / Background Process
**What it is:** A program that runs without a visible window, doing its job quietly in the background.

**Analogy:** Like the furnace in your house. It's always running, keeping things warm, but you don't see it working. You only notice if it stops.

**Related terms:** Gateway, Cron Job, Process

---

## Port (Network Port)
**What it is:** A specific "doorway" on your computer that programs use to talk to each other or to the internet. Port numbers go from 0 to 65535.

**Analogy:** Think of your computer as an apartment building. The IP address is the building address. Ports are like apartment numbers — different services live behind different doors. Port 18789 is where our OpenClaw Gateway lives.

**Why it matters:** Multiple programs can run on the same computer by using different ports. The Gateway uses port 18789 so nothing else conflicts with it.

**Related terms:** Gateway, Localhost, IP Address

---

## Localhost
**What it is:** A special name that means "this computer." When a program connects to "localhost," it's talking to itself.

**Analogy:** It's like calling your own phone number from your phone. You're not going out to the phone network — you're just talking to yourself.

**Example:** `http://localhost:6333` means "connect to port 6333 on this same computer." That's how we talk to Qdrant.

**Related terms:** Port, Loopback, IP Address

---

## Memory Compaction
**What it is:** The process of reviewing recent conversations, summarizing the important parts, and storing them for long-term memory.

**Analogy:** Like cleaning out your notebook at the end of each day. Instead of keeping every doodle and grocery list, you copy the important stuff into a permanent journal and toss the scratch paper.

**Why it matters:** Keeps the system fast (doesn't search through thousands of old messages) while preserving what's actually important.

**Related terms:** Vector Database, Embedding, Semantic Search

---

## Plugin
**What it is:** Add-on software that extends what a main program can do. OpenClaw has plugins for Telegram, voice calls, memory systems, etc.

**Analogy:** Like apps on your phone. Your phone works without them, but apps add new capabilities — camera, maps, games. OpenClaw's "memory-core" plugin adds vector memory capabilities.

**Related terms:** Extension, Module, Integration

---

## API (Application Programming Interface)
**What it is:** A standardized way for different programs to talk to each other. One program exposes an "interface" that others can call.

**Analogy:** Like a restaurant menu. The menu lists what you can order (the API). You don't need to know how the kitchen works — you just pick from the menu, and the food comes out. The menu is the "interface" between you and the kitchen.

**Why it matters:** APIs let different systems work together without knowing each other's internal details.

**Related terms:** Integration, Endpoint, REST

---

## Environment Variable
**What it is:** A setting stored in your computer's memory that programs can read. It's how you configure software without changing code.

**Analogy:** Like sticky notes you leave on your desk. Programs look for specific notes (like "OPENAI_API_KEY") and use what's written there.

**Example:** `OPENCLAW_MEMORY_EMBEDDING_PROVIDER=local` tells OpenClaw to use local embeddings instead of cloud APIs.

**Related terms:** Configuration, Settings, .env file

---

## LLM (Large Language Model)
**What it is:** AI trained on massive amounts of text to understand and generate human language. Examples include GPT-4, Claude, Kimi, etc.

**Analogy:** Like a super-librarian who's read every book in the library. They can answer questions, write stories, and explain concepts because they've "read" so much.

**Why it matters:** LLMs are what let me (Ebi) understand your questions and generate helpful responses.

**Related terms:** AI, Model, Prompt, Token

---

## Token
**What it is:** A unit of text that AI models process. Roughly, 1 token ≈ 0.75 words. "Hello world" is about 2-3 tokens.

**Analogy:** Think of it like Scrabble tiles. Each tile is a piece of a word. AI models process text tile-by-tile. Longer conversations need more tiles.

**Why it matters:** Most AI services charge by the token. Longer conversations cost more. Context windows (how much the AI can "remember") are measured in tokens.

**Related terms:** LLM, Context Window, Prompt

---

## Context Window
**What it is:** How much text an AI can pay attention to at once. Older models: 4,000 tokens (~3,000 words). Newer models: 100,000+ tokens.

**Analogy:** Like a student's notebook. A small notebook (small context window) means they can only reference recent notes. A big notebook means they can look back at everything from the semester while working on today's assignment.

**Why it matters:** A larger context window means I can remember more of our conversation history without losing track.

**Related terms:** Token, LLM, Memory

---

## Sentence Transformers
**What it is:** A Python library for creating embeddings. It turns sentences into those number vectors (embeddings) we use for semantic search.

**Analogy:** Like a specialized dictionary that doesn't just define words — it maps them to coordinates on a giant map of meaning.

**Why it matters:** It's what powers our local embedding model (`all-MiniLM-L6-v2`).

**Related terms:** Embedding, Python Library, all-MiniLM-L6-v2

---

## Python Library
**What it is:** Reusable code that other programmers have written and shared. You import it into your program instead of writing everything from scratch.

**Analogy:** Like buying pre-made ingredients instead of growing your own wheat and milking your own cows. `sentence-transformers` is a pre-made ingredient for creating embeddings.

**Related terms:** Package, Import, Dependency

---

## Venv (Virtual Environment)
**What it is:** A separate, isolated space on your computer where Python programs can install their own libraries without interfering with other programs.

**Analogy:** Like having separate toy boxes for each kid. Kid A's toys don't get mixed up with Kid B's toys. Each Python project gets its own "toy box" (venv) for its libraries.

**Why it matters:** Different programs might need different versions of the same library. Venvs keep them from fighting.

**Related terms:** Python, Dependency, Isolation

---

## GitHub
**What it is:** A website where programmers store and share their code. It tracks changes, allows collaboration, and hosts files.

**Analogy:** Like Google Docs for code — multiple people can work on the same project, see what changed, and roll back mistakes. But it also works like a public library where you can share your work with the world.

**Related terms:** Repository, Commit, Pull Request

---

## Repository (Repo)
**What it is:** A folder (on GitHub or your computer) that contains a project's files plus the complete history of all changes ever made.

**Analogy:** Like a photo album that not only holds photos but also remembers when each photo was taken, who took it, and what was changed in each edit.

**Related terms:** GitHub, Commit, Version Control

---

## Commit
**What it is:** A snapshot of your code at a specific moment, with a message explaining what changed. It's like "saving" in a video game, but you can go back to any previous save.

**Analogy:** Like writing a diary entry: "Today I added a new chapter to my book." The diary entry (commit message) explains what you did, and you can always flip back to see the book as it was yesterday.

**Related terms:** Repository, GitHub, Version Control

---

## Pull Request (PR)
**What it is:** A proposal to add your changes to a project. You "request" that the project owner "pull" your changes into their main code.

**Analogy:** Like submitting a draft of your essay to a teacher for review before it's finalized. They can suggest changes, approve it, or reject it.

**Related terms:** GitHub, Repository, Merge

---

*Last updated: February 10, 2026*
