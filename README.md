# Prompt to GPT-3: Step-by-Step Thinking Instructions for Humor Generation

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1Xsycivlny9e9oAd-AjhnvGQvtPmXFSrf?usp=sharing)
[![Blog](https://img.shields.io/badge/Blog-Visit%20Now-green)](https://stry233.github.io/blog/2023/CraftingMonologueJokesChatGPT/)

<p align="center">
  <img src="https://github.com/Stry233/Joe-Toplyn-s-Monologue-Joke-generation-using-ChatGPT/assets/31975605/9a409c6d-a26e-467e-b39d-ffe6d2ece238" width="80%" />
</p>


## Toplyn's Theory for Writing Jokes

Toplyn is a renowned comedy writer who has worked on shows like "Late Night with David Letterman" and "The Tonight Show with Jay Leno." In his book "Comedy Writing for Late-Night TV: How to Write Monologue Jokes, Desk Pieces, Sketches, Parodies, Audience Pieces, Remotes, and Other Short-Form Comedy", he outlines his process for creating humorous content. According to Toplyn, there are four steps to crafting a joke:

1. **Create a topic sentence based on a news item:** A news article is typically used as a starting point. The first step involves generating a topic sentence highlighting the news item's main point. The aim is to create a sentence that is engaging and appropriate for humorous commentary, while still being factually accurate and not inherently funny.

2. **Identify handles and associations:** Handles refer to interesting or peculiar words or phrases found within the topic sentence, and Toplyn usually identifies two handles for each joke. After identifying handles, in the next step, associations are created. Associations are the concepts or ideas related to each handle. Toplyn generates a list of associations for each handle, which are used in the subsequent step to develop a punchline.

3. **Develop a punchline by combining associations:** A punchline connects one association from the first handle's list with another from the second handle's list. This combination should be perceived as true by most people and evoke a negative emotion towards the first major entity in the topic. The negative emotion is essential for generating humor in the monologue joke.

4. **Connect the topic and punchline with an angle:** The angle is a sentence or phrase that smoothly transitions the audience from the topic to the punchline. It ensures that the joke has a coherent structure and flows naturally from beginning to end.

Here is an example of a joke written by Joe: "At Lax, customs inspectors seized a live shipment of 67 Giant African snails. Instead of destroying them, officials gave them jobs at the DMV." Joe Toplyn created an automated joke generation system based on his theory by prompting GPT-3. This work is in the same spirit. We built upon Toplyn's approach by introducing a new factor - the cognitive distance between associations for creating punchlines - to generate more effective jokes. This involves identifying seemingly unrelated associations to craft punchlines, resulting in better jokes.



## Table: Example of joke generation using the proposed method

| Component | Description |
| --------- | ----------- |
| Topic | Microsoft introduces a new AI-powered Copilot for their 365 apps, making Clippy's ghost proud. |
| Handles | AI-powered Copilot, Clippy's ghost |
| Associations for **AI-powered Copilot** | Artificial intelligence, Microsoft 365, Productivity, GPT-4, Virtual assistant, **Automated tasks**, Office apps, Innovative technology |
| Associations for **Clippy's ghost** | Nostalgia, Old technology, Paperclip, **Annoying assistant**, Pop-up help, Microsoft Office, 90s tech, Failed innovation |
| Punchline | Now, it can automatically annoy you with its help. |
| Angle | In the spirit of Clippy, |
| Final Joke | Microsoft introduces a new AI-powered Copilot for their 365 apps, making Clippy's ghost proud. In the spirit of Clippy, now it can automatically annoy you with its help. |

| Component | Description |
| --------- | ----------- |
| Topic | Meta releases a new AI language generator called LLaMA, hoping it'll spit out solutions instead of just spitting. |
| Handles | AI language generator, LLaMA |
| Associations for **AI language generator** | Chatbot, Artificial Intelligence, Communication, Language Model, **Problem Solving**, Predictions, Deep Learning, OpenAI |
| Associations for **LLaMA** | Animal, **Spitting**, Furry, Peru, Mountain, Domesticated, Wool, Andes |
| Punchline | It's a problem solver that spits out answers, not saliva. |
| Angle | Instead of taking after its namesake, |
| Final Joke | Meta releases a new AI language generator called LLaMA, hoping it'll spit out solutions instead of just spitting. Instead of taking after its namesake, it's a problem solver that spits out answers, not saliva. |
