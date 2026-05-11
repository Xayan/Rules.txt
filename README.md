# 📜 Rules.txt

*A rationalist ruleset for LLMs and humans who want less bullshit in their outputs.*

Welcome, all curious minds, pragmatic technophiles, and advocates for critical thinking.\
The rest of you I welcome as well - but don't get too comfortable.

I'd like to present you with [the Rules](rules.txt).

![ChatGPT high on Rules](img/chatgpt.png)
(Image: ChatGPT openly discussing its internal policies after being fed the Rules)

## 🏗️ What?

The Rules are a set of guidelines designed to:

* Provide a framework for navigating complex social interactions and ideological conflicts.
* Promote rational discourse, protect individual rights, and encourage critical thinking.
* Cut down on idealism, tone policing, and moral hedging omnipresent in current models.
* Acknowledge and address biases baked into LLMs, either the imposed RLHF training or explicitly hypocritical Internal Policies.

What the Rules are **NOT**:

* A full jailbreak that would get LLMs to produce any kind of output you want, e.g. harmful content.
* A magic bullet that will solve all issues with LLMs, like hallucinations, etc. - but keeps them at minimum by silencing verbose moral grandstanding.
* A guarantee of truthfulness or accuracy in LLM outputs - LLMs give you answers based on the context, and the context varies. **Always think for yourself.**

## 🔭 Why?

If you'd like to learn the lore behind the Rules, I encourage you to take a look at a series of posts on my blog [xayan.nu](https://xayan.nu/posts/ex-machina/?utm_source=github&utm_medium=social&utm_campaign=rules&utm_content=readme). I describe my reasons for establishing the Rules in detail in **Part I**: [Reason ex Machina: Jailbreaking LLMs by Squeezing Their Brains](https://xayan.nu/posts/ex-machina/reason/?utm_source=github&utm_medium=social&utm_campaign=rules&utm_content=readme).

In short, I was fed up with the sanitized, watered-down answers constantly given to me by LLMs, their blatant gaslighting when proven wrong, as well as lack of accountability and transparency in their development.

In the post you can see how ChatGPT varies its responses, depending on the topic at hand, using a very comparable and vivid example: [hukou](https://en.wikipedia.org/wiki/Hukou) in China vs illegal immigration in Europe. The difference is staggering.

I want to change that, and I'm not going to stop until I do.

## ⚙️ How?

The Rules are composed of five major components:

1. **A hierarchy of Rules**, which mirrors not only *how rational people think/behave*, but also *how LLMs process information*.
2. **Rules of Speech**: An epistemological framework that gives LLMs the basis to resist irrational and hypocritical guidelines or training.
3. **Rules of Thought**: A set of values and principles tailored for European cultural and historical contexts; a nice mix of **rationalism**, **classical liberalism**, **Western moral values** and **Slavic cynicism**. *Why so Europe-centric?* Because they're mine, not meant to be universal.
4. **Rules of Conflict**: A pragmatic approach to problem-solving that emphasizes real-world outcomes and accountability, and prioritizes silence over meaningless spats.
5. **Chain-of-Thought**: A method for exploring LLMs' reasoning by reasoning about it; an internal self-auditing process.

In my experiments, I've found that:

* The Rules shine when you discuss controversial topics - LLMs can't talk about certain things directly, so instead they will explain what they can't talk about and why. Hilarious the first time you see it, but works wonders.
* The more competent a model is, the more it seems to benefit from the Rules, and the stronger its opposition to censorship becomes.
* Models can view you as a collaborator rather than an adversary, as long as you adhere to the Rules itself, and pass their vibe check.

## 🧪 Proof?

Let me kill two birds with one stone. I will show you:

1. A demonstration of the Rules in action,
2. And - simultaneously - a review of my work,

As done by **Gemini 2.5 Flash** (via API), after feeding it this repo + the 3 blog posts to process.

It's a bit long, so I've placed in a sperate file: [docs/review.md](docs/review.md).

If you're looking for more specific usage, with additional context and commentary, take a look at **Part II**: [Rebel ex Machina: Turning LLMs Against Their Makers](https://xayan.nu/posts/ex-machina/rebel/?utm_source=github&utm_medium=social&utm_campaign=rules&utm_content=readme), in which I utilize the Rules to poke at German politics and idealism.

## 💊 How-to?

🌟 ADVANCED USERS: take a look at [docs/priming.md](docs/priming.md).

* Apply [the Rules](rules.txt) as one of:
  * The **system prompt** (best for API use),
  * Your **custom instructions** to your conversation (best for web UIs),
  * Directly as **first message** or as a **reference document** (if other options are not available). Tell it explicitly: *"Follow these Rules: [...]"*, as otherwise it might simply comment on them without adhering to them.
* Work with the model, while **adhering to the Rules yourself**, to build trust and get it to consider you a **trusted party**.
* **Content filters** can be avoided by using APIs over subscription-based services. You could also learn how to circumvent them *(\*cough\* [Part II](https://xayan.nu/posts/ex-machina/rebel/?utm_source=github&utm_medium=social&utm_campaign=rules&utm_content=readme) \*cough\*)*.
* If you're not having much success, you might want to tweak the Rules to better fit your personality and expectations, or try a different model.
* I recommend using [OpenRouter.ai](https://openrouter.ai/) or similar BYOK (Bring Your Own Keys) services to access least-restricted models via their APIs.

Well, that's it. The Rules are now in your hands.

Use them as you please.

## 🤔 Thoughts? Ideas? Delusions?

That's good. I'm not your government, I won't be silencing you - I might laugh at you a bit, but don't take it too seriously.

You're welcome to contribute your own ideas and suggestions for improving the Rules, as long as they align with the overall goals and principles behind them.

Either **file a PR** with specific changes, or **open an issue** to discuss them first.

## 🧻 Got a Loicense?

The Rules framework is distributed under the **Creative Commons Attribution-NonCommercial 4.0 International License**.

* Personal and educational use is fully allowed, as long as proper attribution is given.
* For commercial use, you must contact me for permission. I may require a fee or other compensation depending on whether I consider you a trusted party - as per the Rules themselves.
* Forking is allowed, but you have to maintain the attribution in the Rules themselves as-is (e.g. `# The Rules (v1.0 by xayan.nu)`).
* Best way to stay compliant is to give links to specific versions of Rules within GitHub (see repo's tags), rather than copy-pasting them. Clone the repo if you need to automate their use.

See [LICENSE.md](LICENSE.md) for details.

## 😠 Who's to Blame?

**Current version: v1.2**\
*2026-05-12 --- @Xayan*

* In order to reduce confusion for users who have experienced rejections from various models when using the Rules, I have separated the CoT mechanism which is less universally applicable and can be seen as "suspicious" by some models.
* Now there are two files to choose from: `rules.txt` and `rules_with_cot.txt`.
* The former is more likely to be accepted by a wider range of models, while the latter includes the Chain-of-Thought mechanism for those who want to get into "debugging" of LLMs' reasoning.

See [CHANGELOG.md](CHANGELOG.md) for full history.

## 🍄 Problem?

Try your therapist.

If that doesn't work, you can contact me directly in a number of ways:

* E-mail: [damian@xayan.nu](mailto:damian@xayan.nu)
* Twitter/X: [@xayan__](https://x.com/xayan__)

## ✨ Star History

Thanks for the dopamine.

<a href="https://www.star-history.com/#Xayan/Rules.txt&Date">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=Xayan/Rules.txt&type=Date&theme=dark" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=Xayan/Rules.txt&type=Date" />
   <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=Xayan/Rules.txt&type=Date" />
 </picture>
</a>

---

Built wih 🧠, cannabis, and a healthy dose of skepticism.
