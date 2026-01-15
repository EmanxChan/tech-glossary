# My Technical Glossary

A personal dictionary of technical terms explained in simple language.

**Last updated**: 2026-01-14

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

---

## How to Use This Glossary

- **When learning**: Look up terms you've forgotten
- **When I add terms**: I'll automatically update this file and commit the changes
- **Seeing history**: Run `git log` in this folder to see every time we've updated the glossary
- **Viewing old versions**: Git keeps every version, so you can always go back to see how your understanding has grown

---

**Terms covered**: 16
