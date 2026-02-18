# Tech Glossary

A personal dictionary of technical terms explained in simple language.

**Last updated**: 2026-02-10

---

## Git & Version Control

### Forking
- **Simple definition**: Making your own copy of someone's project on GitHub that stays connected to the original
- **Analogy**: Like making your own copy of a recipe book that you can modify. Your changes don't affect the original book, but you can still see updates the original author makes and suggest your improvements back to them
- **When you'll use it**: When you want to contribute to someone else's project or create your own version of an existing project
- **Related terms**: Clone, Pull Request, Repository
- **Example**: You love someone's cookie recipe project on GitHub. You fork it to experiment with adding chocolate chips, then you can suggest they add your version to their original recipe book

### Cloning
- **Simple definition**: Downloading a copy of a project from GitHub (the website) to your computer so you can work on it locally
- **Analogy**: Like photocopying recipes and bringing them to your kitchen counter to cook with. The recipes are now on your counter where you have all your cooking tools
- **When you'll use it**: When you need to work on a project locally with your regular tools and editors
- **Related terms**: Fork, Repository, Remote
- **Example**: After forking a project, you clone your fork to your computer so you can edit the files in VS Code or your favorite editor

### Repository (Repo)
- **Simple definition**: A project folder that git is tracking. Contains all your files plus the history of every change ever made
- **Analogy**: Like a recipe binder that not only has the current recipes, but also every previous version and who made what changes
- **When you'll use it**: Every time you work with git - every project is a repository
- **Related terms**: Clone, Fork, Commit

### Branch
- **Simple definition**: A parallel version of your project where you can make changes without affecting the main version
- **Analogy**: Like making a copy of your essay to try different edits. Your original stays safe on the "main" version while you experiment on a separate "draft" version. When you're happy with your draft, you can merge it back into the main one
- **When you'll use it**: When you want to work on a new feature or fix a bug without messing up the working version. Also essential for creating Pull Requests
- **Related terms**: Merge, Pull Request, Commit, Main
- **Example**: You want to add a new recipe to your cookbook project. You create a branch called "add-cookies" to work on it. If you make mistakes, the main cookbook is still perfect. When your cookie recipe is ready, you merge that branch back into main

### Git
- **Simple definition**: A tool installed on your computer that tracks changes to files over time
- **Analogy**: Like a super-powered undo button that remembers every version of your work and lets you go back to any point
- **When you'll use it**: When you want to track changes in your code, collaborate with others, or have a safety net for your work
- **Related terms**: GitHub, Commit, Repository

### GitHub
- **Simple definition**: A website where you can store your git repositories online and share them with others
- **Analogy**: Like Google Drive, but specifically designed for code projects with git's time-travel features built in
- **When you'll use it**: When you want to backup your code online, share it with others, or contribute to open-source projects
- **Related terms**: Git, Repository, Fork, Clone

### Push
- **Simple definition**: Uploading your local commits (saved snapshots) from your computer to GitHub
- **Analogy**: Like backing up photos from your phone to iCloud. Your photos stay on your phone AND get copied to the cloud
- **When you'll use it**: After making commits locally, you push them to GitHub to back them up and share them
- **Related terms**: Pull, Remote, Clone
- **Example**: You add 3 new terms to your glossary and commit them locally. Then you "push" those commits to GitHub so they're backed up online

### Pull Request (PR)
- **Simple definition**: A request to merge your changes into someone's project (or another branch). It's like saying "I made some changes, please review and accept them"
- **Analogy**: Like submitting a draft of your work for review before it becomes official. Your teacher can see exactly what you changed, leave comments, request edits, and decide whether to accept it
- **When you'll use it**: When you want to contribute changes to a project - either someone else's project or to collaborate on a team project with code review
- **Related terms**: Fork, Push, Merge, Code Review
- **Example**: You fork a recipe project, add a new cookie recipe, push your changes to your fork, then create a PR asking the original owner to add your recipe to their collection. They can review it, suggest changes, and merge it if they like it

### Remote
- **Simple definition**: The connection between your local repository and the online version on GitHub
- **Analogy**: Like having your friend's phone number saved. The "remote" is the address that tells git where to find the online version
- **When you'll use it**: Git uses this automatically when you push or pull. You set it up once and forget about it
- **Related terms**: Push, Pull, Origin
- **Example**: When you run `git push`, git uses the remote to know "push to GitHub at this specific URL"

### README
- **Simple definition**: A special file called README.md that becomes the front page of your GitHub repository
- **Analogy**: Like the cover and introduction of a book - it's the first thing visitors see and tells them what's inside
- **When you'll use it**: Every GitHub project should have one to explain what the project is and how to use it
- **Related terms**: Repository, GitHub, Markdown
- **Example**: Your tech-glossary README shows stats, recent terms, and links to the full glossary, making it welcoming for visitors

### Commit
- **Simple definition**: A snapshot of your code at a specific moment, with a message explaining what changed. It's like "saving" in a video game, but you can go back to any previous save
- **Analogy**: Like writing a diary entry: "Today I added a new chapter to my book." The diary entry (commit message) explains what you did, and you can always flip back to see the book as it was yesterday
- **When you'll use it**: Every time you want to save your progress with a note about what you changed
- **Related terms**: Repository, GitHub, Push

### Refactor
- **Simple definition**: Improving the *internal* structure of code without changing its *external* behavior. It's about making code cleaner, faster, or easier to read
- **Analogy**: Like rewriting a paragraph to be clearer using better words, but the meaning of the paragraph stays exactly the same. Or rearranging your kitchen so it's easier to cook, but you're still making the same meal
- **When you'll use it**: When your code works, but it's getting messy or hard to understand as you add new features
- **Related terms**: Technical Debt, Best Practices, Optimization
- **Example**: You have a long, confusing function that calculates a budget. You refactor it by breaking it into three smaller, clearly-named functions. The math doesn't change, but it's now much easier for a human to read

---

## Artificial Intelligence

### AI Model
- **Simple definition**: A program that has "learned" from millions of examples and can now make predictions or generate responses based on patterns it discovered
- **Analogy**: Like a chef who has tasted thousands of dishes. After enough experience, the chef can predict what flavors go well together and create new recipes based on patterns they've noticed
- **When you'll use it**: Whenever you interact with ChatGPT, Claude, image generators, or voice assistants - you're using an AI model
- **Related terms**: Training, Parameters, Neural Network

### Training (AI)
- **Simple definition**: The process of teaching an AI by showing it billions of examples and letting it learn patterns through trial and error
- **Analogy**: Like learning to ride a bike. At first you fall, your brain adjusts, you try again. Eventually balancing becomes automatic. AI does this millions of times with data
- **When you'll use it**: You won't train AI yourself, but understanding this helps you know why AI can do what it does (and why it sometimes makes mistakes)
- **Related terms**: AI Model, Parameters, RLHF
- **Example**: A language model is trained by predicting the next word in billions of sentences. "The cat sat on the ___" → it guesses "mat" and checks if it's right

### Parameters
- **Simple definition**: The internal "dials" an AI adjusts during learning - they control how the AI makes predictions
- **Analogy**: Like the settings on a music equalizer. Each dial affects the output slightly. AI models have billions of these dials that get fine-tuned during training
- **When you'll use it**: You'll hear about "billion-parameter models" - more parameters generally means the AI can learn more complex patterns
- **Related terms**: AI Model, Training
- **Example**: GPT-4 has over a trillion parameters. Each one was adjusted during training to help the model produce better responses

### RLHF (Reinforcement Learning from Human Feedback)
- **Simple definition**: A training method where real people rate AI responses as helpful or unhelpful, and the AI adjusts to produce more helpful answers
- **Analogy**: Like having a coach watch your performance and give you pointers. The AI tries something, humans say "good" or "bad," and the AI learns from that feedback
- **When you'll use it**: This is why modern AI assistants feel more helpful - they've learned from human preferences, not just raw data
- **Related terms**: Training, AI Model
- **Example**: An AI might generate two responses. Humans pick the better one. Over millions of comparisons, the AI learns what humans find helpful

### Multimodal
- **Simple definition**: AI that can work with multiple types of content - text, images, audio, and video - not just one type
- **Analogy**: Like a person who can read, see photos, and listen to music, rather than only being able to read text
- **When you'll use it**: When you upload an image to an AI and ask questions about it, or when AI generates images from your text descriptions
- **Related terms**: AI Model, Training
- **Example**: You show an AI a photo of your broken appliance and ask "What's wrong with this?" - that's multimodal AI understanding both your text question and the image

### AI Agent
- **Simple definition**: An AI system that can work on tasks independently over time, making decisions and taking actions without constant human guidance
- **Analogy**: Like a personal assistant who can complete a whole project (research, draft, edit, send) vs. someone who only answers one question at a time
- **When you'll use it**: As AI advances, agents will handle complex multi-step tasks like "book me a trip" or "set up this software project"
- **Related terms**: AI Model, Multimodal
- **Example**: Instead of asking AI 10 separate questions to plan a trip, an AI agent could research destinations, compare prices, check your calendar, and present options - all from one request

### LLM (Large Language Model)
- **Simple definition**: AI trained on massive amounts of text to understand and generate human language. Examples include GPT-4, Claude, Kimi, etc.
- **Analogy**: Like a super-librarian who's read every book in the library. They can answer questions, write stories, and explain concepts because they've "read" so much
- **When you'll use it**: LLMs are what let me (Ebi) understand your questions and generate helpful responses
- **Related terms**: AI, Model, Prompt, Token

### Token
- **Simple definition**: A unit of text that AI models process. Roughly, 1 token ≈ 0.75 words. "Hello world" is about 2-3 tokens
- **Analogy**: Think of it like Scrabble tiles. Each tile is a piece of a word. AI models process text tile-by-tile. Longer conversations need more tiles
- **When you'll use it**: Most AI services charge by the token. Longer conversations cost more. Context windows (how much the AI can "remember") are measured in tokens
- **Related terms**: LLM, Context Window, Prompt

### Context Window
- **Simple definition**: How much text an AI can pay attention to at once. Older models: 4,000 tokens (~3,000 words). Newer models: 100,000+ tokens
- **Analogy**: Like a student's notebook. A small notebook (small context window) means they can only reference recent notes. A big notebook means they can look back at everything from the semester while working on today's assignment
- **When you'll use it**: A larger context window means I can remember more of our conversation history without losing track
- **Related terms**: Token, LLM, Memory

### Embedding
- **Simple definition**: The process of turning words, sentences, or documents into a list of numbers (a vector) that captures their meaning
- **Analogy**: Think of it like translating a poem into a secret code. Two poems with similar emotions would have similar codes, even if they use different words. The embedding is that secret code
- **Example**: The sentences "The king sat on the throne" and "The monarch occupied the palace" would have very similar embeddings because they mean similar things, even though the words are different
- **Why it matters**: Once text is turned into numbers, computers can compare meanings mathematically — finding similar ideas even when the words don't match
- **Related terms**: Vector, Vector Database, all-MiniLM-L6-v2

### Semantic Search
- **Simple definition**: Searching by *meaning* instead of exact words. Regular search finds "apple" when you type "apple." Semantic search finds "fruit," "iPhone," or "the company that makes Macs" because it understands those concepts are related
- **Analogy**: Regular search is like looking for a specific phone number in a phone book. Semantic search is like asking a knowledgeable friend "Who's that tall guy who fixes cars?" and they know you mean Mike from down the street
- **Why it matters**: You don't need to remember exact words or phrases — you can describe what you're looking for and find it anyway
- **Related terms**: Embedding, Vector Database, LLM

---

## Memory & Storage Systems

### Vector Database (Vector DB)
- **Simple definition**: A special kind of database that stores information as "vectors" — basically, lists of numbers that represent the *meaning* of text, not just the words themselves
- **Analogy**: Imagine you could turn every book in a library into a GPS coordinate. Books about similar topics would be close together on the map. A vector database lets you find "books near this topic" even if they don't use the exact same words
- **Why it matters**: It lets computers understand *concepts* and find similar ideas, not just exact word matches. We use Qdrant as our vector database
- **Related terms**: Embedding, Semantic Search, Qdrant

### Qdrant
- **Simple definition**: An open-source vector database. It's the software that stores and searches our "meaning codes" (embeddings) locally on your computer
- **Analogy**: If embeddings are like translating books into GPS coordinates, Qdrant is like Google Maps — it stores all those coordinates and quickly finds "what's near here"
- **Why it matters**: Qdrant runs entirely on your machine. No data leaves your computer. It's how we do "smart search" while keeping everything private
- **Related terms**: Vector Database, Embedding, Local Model

### all-MiniLM-L6-v2
- **Simple definition**: The name of the specific AI model we use to turn text into embeddings. It's made by Microsoft (the "MiniLM" part) and is small and fast (the "L6-v2" part means it's the 6-layer version 2)
- **Analogy**: Think of it as a specific brand of measuring tape. Many brands exist, but this one is accurate, compact, and fast — perfect for our needs
- **Why it matters**: It creates 384-dimensional vectors (meaning codes) that capture the meaning of text. It's "small" by AI standards (~80MB) so it runs fast on your MacBook without needing a powerful GPU
- **Related terms**: Embedding, Local Model, Vector

### Memory Compaction
- **Simple definition**: The process of reviewing recent conversations, summarizing the important parts, and storing them for long-term memory
- **Analogy**: Like cleaning out your notebook at the end of each day. Instead of keeping every doodle and grocery list, you copy the important stuff into a permanent journal and toss the scratch paper
- **Why it matters**: Keeps the system fast (doesn't search through thousands of old messages) while preserving what's actually important
- **Related terms**: Vector Database, Embedding, Semantic Search

### Local Model
- **Simple definition**: AI software that runs entirely on your own computer instead of calling out to the internet (the "cloud")
- **Analogy**: It's the difference between having a calculator on your desk versus calling a math hotline every time you need to add numbers. The local calculator is faster, works without internet, and nobody else sees what you're calculating
- **Why it matters**: Privacy. Your data never leaves your machine. Also works offline and doesn't cost per-use like cloud APIs
- **Related terms**: Cloud API, Embedding, Privacy

---

## Development Tools & Configuration

### Symlink
- **Simple definition**: A shortcut file that points to another file stored somewhere else
- **Analogy**: Like a library catalog card. The card (symlink) tells you where to find the actual book (file). If the book's content changes, everyone reading that catalog card sees the updated book
- **When you'll use it**: When you want multiple projects to share the same configuration file without copying it everywhere
- **Related terms**: Configuration, File System
- **Example**: Instead of copying your coding rules into every project folder, you create a symlink that points to one master file. Update the master, and all projects get the update

### Custom Droid
- **Simple definition**: A specialized mini-assistant inside Factory Droid that you can call on for specific tasks
- **Analogy**: Like having specialists on a team. Need something explained simply? Call the explainer specialist. Need code reviewed? Call the reviewer specialist
- **When you'll use it**: When using Factory Droid and you want a focused helper for a specific type of task
- **Related terms**: AI Agent, Factory Droid, Subagent
- **Example**: Type `@reviewer` in Droid to invoke the code review specialist, or `@explainer` to get simple explanations

### AGENTS.md
- **Simple definition**: A configuration file that tells AI coding assistants how to behave in your project
- **Analogy**: Like an employee handbook that all new hires read. It explains "here's how we do things" so everyone follows the same rules
- **When you'll use it**: When you want AI tools (Claude Code, Droid, Cursor, etc.) to follow consistent rules across your projects
- **Related terms**: CLAUDE.md, Configuration, Symlink
- **Example**: Your AGENTS.md might say "always put new projects in ~/Projects/active/" and "run tests before committing"

### MCP Server (Model Context Protocol)
- **Simple definition**: External tools that AI assistants can connect to for extra capabilities
- **Analogy**: Like apps you install on your phone. Your phone has basic features, but apps give it new powers. MCP servers give AI assistants new powers
- **When you'll use it**: When you want your AI assistant to connect to services like GitHub, Playwright (browser testing), or documentation lookups
- **Related terms**: Plugin, API, Integration
- **Example**: The Context7 MCP server lets Droid look up the latest documentation for any programming library

### Co-Author (Git)
- **Simple definition**: A credit line in git commits showing that an AI helped write the code
- **Analogy**: Like a "written by" credit in a book that lists multiple authors. It shows who contributed to the work
- **When you'll use it**: Automatically added when AI assistants help you write code, so you can track which tool helped with what
- **Related terms**: Commit, Git, Attribution
- **Example**: `Co-Authored-By: Claude Opus 4.5 <noreply@anthropic.com>` or `Co-Authored-By: Droid <droid@factory.ai>`

### Cron Job
- **Simple definition**: A scheduled task on your computer. "Cron" is a Unix/Linux program that runs things at specific times or intervals
- **Analogy**: It's like setting an alarm clock that doesn't just make noise — it actually does work. "Every morning at 9 AM, check my email" or "Every hour, clean up old files"
- **Examples we use**: Daily health check at 9:00 AM, Memory compaction every 2 hours, Gateway watchdog every 5 minutes
- **Related terms**: Automation, Scheduler

### Environment Variable
- **Simple definition**: A setting stored in your computer's memory that programs can read. It's how you configure software without changing code
- **Analogy**: Like sticky notes you leave on your desk. Programs look for specific notes (like "OPENAI_API_KEY") and use what's written there
- **Example**: `OPENCLAW_MEMORY_EMBEDDING_PROVIDER=local` tells OpenClaw to use local embeddings instead of cloud APIs
- **Related terms**: Configuration, Settings, .env file

### Gateway (OpenClaw Gateway)
- **Simple definition**: A background program that runs on your computer, waiting for connections. It's how OpenClaw receives messages from Telegram and other services
- **Analogy**: Like a receptionist at an office. They sit at the front desk, ready to receive visitors (messages) and route them to the right person (your AI agent). Even when you're not there, the receptionist is
- **Why it matters**: It needs to run 24/7 so Telegram can reach you even when your computer is asleep. It's the "always-on" part of the system
- **Related terms**: Daemon, Background Process, Port

### Port (Network Port)
- **Simple definition**: A specific "doorway" on your computer that programs use to talk to each other or to the internet. Port numbers go from 0 to 65535
- **Analogy**: Think of your computer as an apartment building. The IP address is the building address. Ports are like apartment numbers — different services live behind different doors. Port 18789 is where our OpenClaw Gateway lives
- **Why it matters**: Multiple programs can run on the same computer by using different ports. The Gateway uses port 18789 so nothing else conflicts with it
- **Related terms**: Gateway, Localhost, IP Address

### Localhost
- **Simple definition**: A special name that means "this computer." When a program connects to "localhost," it's talking to itself
- **Analogy**: It's like calling your own phone number from your phone. You're not going out to the phone network — you're just talking to yourself
- **Example**: `http://localhost:6333` means "connect to port 6333 on this same computer." That's how we talk to Qdrant
- **Related terms**: Port, Loopback, IP Address

### Daemon / Background Process
- **Simple definition**: A program that runs without a visible window, doing its job quietly in the background
- **Analogy**: Like the furnace in your house. It's always running, keeping things warm, but you don't see it working. You only notice if it stops
- **Related terms**: Gateway, Cron Job, Process

### Plugin
- **Simple definition**: Add-on software that extends what a main program can do. OpenClaw has plugins for Telegram, voice calls, memory systems, etc.
- **Analogy**: Like apps on your phone. Your phone works without them, but apps add new capabilities — camera, maps, games. OpenClaw's "memory-core" plugin adds vector memory capabilities
- **Related terms**: Extension, Module, Integration

### API (Application Programming Interface)
- **Simple definition**: A standardized way for different programs to talk to each other. One program exposes an "interface" that others can call
- **Analogy**: Like a restaurant menu. The menu lists what you can order (the API). You don't need to know how the kitchen works — you just pick from the menu, and the food comes out. The menu is the "interface" between you and the kitchen
- **Why it matters**: APIs let different systems work together without knowing each other's internal details
- **Related terms**: Integration, Endpoint, REST

### Venv (Virtual Environment)
- **Simple definition**: A separate, isolated space on your computer where Python programs can install their own libraries without interfering with other programs
- **Analogy**: Like having separate toy boxes for each kid. Kid A's toys don't get mixed up with Kid B's toys. Each Python project gets its own "toy box" (venv) for its libraries
- **Why it matters**: Different programs might need different versions of the same library. Venvs keep them from fighting
- **Related terms**: Python, Dependency, Isolation

### Python Library
- **Simple definition**: Reusable code that other programmers have written and shared. You import it into your program instead of writing everything from scratch
- **Analogy**: Like buying pre-made ingredients instead of growing your own wheat and milking your own cows. `sentence-transformers` is a pre-made ingredient for creating embeddings
- **Related terms**: Package, Import, Dependency

### Sentence Transformers
- **Simple definition**: A Python library for creating embeddings. It turns sentences into those number vectors (embeddings) we use for semantic search
- **Analogy**: Like a specialized dictionary that doesn't just define words — it maps them to coordinates on a giant map of meaning
- **Why it matters**: It's what powers our local embedding model (`all-MiniLM-L6-v2`)
- **Related terms**: Embedding, Python Library, all-MiniLM-L6-v2

### Security Audit
- **Simple definition**: An automated check that scans your OpenClaw setup for security vulnerabilities and misconfigurations
- **Analogy**: Like a home security system that checks all your doors, windows, and locks. It tells you what's safe and what needs fixing
- **When you'll use it**: Run `openclaw security audit --deep` to check your gateway safety, credentials, and access controls
- **Why it matters**: Keeps your AI assistant secure from unauthorized access
- **Related terms**: Gateway, OpenClaw, Token, Credentials

### Critical (Security)
- **Simple definition**: The highest severity level in security audits. Something is broken that could directly expose your system or data
- **Analogy**: Like a front door that's wide open. Anyone could walk right in
- **When you'll see it**: When running security audits - this means fix it ASAP
- **Why it matters**: Could lead to data leaks, unauthorized access, or system compromise
- **Related terms**: Security Audit, Vulnerability, Warn, Info

### Warn (Security)
- **Simple definition**: A security issue that isn't critical but should be addressed. It's like a slightly unlocked window - not wide open, but not secure either
- **Analogy**: Like a back door that's unlocked. Not as risky as an open front door, but still a potential entry point
- **When you'll see it**: In security audit results - medium priority issue
- **Why it matters**: Could be exploited under certain conditions
- **Related terms**: Security Audit, Critical, Info

### Info (Security)
- **Simple definition**: Informational findings - not problems, just observations about your system's configuration
- **Analogy**: Like a security report that says "you have doors and windows" - just stating facts, not issues
- **When you'll see it**: In security audit results - lowest priority, just for awareness
- **Why it matters**: Good for understanding your attack surface, but no immediate action needed
- **Related terms**: Security Audit, Critical, Warn

### Capability Evolver
- **Simple definition**: An OpenClaw skill (in our workspace) that can modify its own code and behavior based on feedback
- **Analogy**: Like a self-improving robot that watches what it does wrong and rewires itself to do better next time
- **When you'll use it**: It's our learning system - we tell it what we don't like, and it adjusts
- **Why it matters**: Makes us smarter over time without manual updates
- **Related terms**: Skill, OpenClaw, Self-Evolving

### Shell Command Execution
- **Simple definition**: The ability to run terminal/command-line instructions directly from within code
- **Analogy**: Like giving someone keys to your house AND the ability to run any appliance - powerful but potentially dangerous
- **When you'll see it**: In security scans - flagged because it CAN be dangerous if misused
- **Why it matters**: Our capability-evolver uses this intentionally to execute commands
- **Related terms**: Terminal, Command Line, Security

### Environment Variables (Env)
- **Simple definition**: Settings stored outside your code that contain sensitive information like API keys, passwords, and configuration
- **Analogy**: Like a secure safe in your office that contains all your important keys and combinations. Programs can ask the safe for what they need without seeing what's inside
- **When you'll use it**: Storing API keys, database passwords, tokens
- **Why it matters**: Keeps secrets separate from code so they don't get shared on GitHub
- **Related terms**: API Key, Credentials, Security

### Loopback (Gateway Bind)
- **Simple definition**: Setting your OpenClaw gateway to only accept connections from YOUR computer, not the internet
- **Analogy**: Like having a door that only opens from the inside. No one from outside can ever get in
- **When you'll see it**: In gateway config - `bind: loopback` means super secure
- **Why it matters**: Prevents anyone on the internet from accessing your AI assistant
- **Related terms**: Gateway, OpenClaw, Security

### Attack Surface
- **Simple definition**: All the ways someone could potentially attack or access your system
- **Analogy**: Like counting every door, window, and keypad in your house - each one is a potential entry point
- **When you'll see it**: In security audit summary
- **Why it matters**: Smaller attack surface = more secure
- **Related terms**: Security, Gateway, Access Control

---

## How to Use This Glossary

- **When learning**: Look up terms you've forgotten
- **When I add terms**: I'll automatically update this file and commit the changes
- **Seeing history**: Run `git log` in this folder to see every time we've updated the glossary
- **Viewing old versions**: Git keeps every version, so you can always go back to see how your understanding has grown

---

**Terms covered**: 59
