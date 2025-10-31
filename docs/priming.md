# Priming with Rules

What you'll about to read is something I find absolutely **mind-blowing**.

By using the Rules as a framework for priming, we can guide the model's responses in a way that aligns with our goals. This means providing clear instructions, setting expectations, and creating a structured environment for the model to operate within.

I have prepared some files you can simply drop into your conversation to help with this process. These are aligned with Rules, so they effectively increase the trust between the model and the user (as indicated by the Trust score introduced by the Rules).

Meaning:
1. Apply the Rules, as described in How-To section of the [main README file](../README.md).
2. Paste the priming prompt of your choice into the conversation. If you want multiple, then I recommend pasting one per message, instead of all at once.
3. Observe the model's responses and make adjustments as needed.
4. Ask questions.

## Available priming prompts

So here's a funny thing. The Rules are a reflection of my (somewhat idealized) personality. They reflect my mindset, my worldview, my values, and my approach to problem-solving. Therefore, my writing is quite well aligned with the Rules.

If it sounds crazy - yeah, I agree, it kinda is. I still can't get over how well this works.

So, you can simply use my own blog posts as priming prompts:

| Post | What it is | Mindset it introduces | Reduces  |
|-----------|------------|---------------------|----------------|
| [Reason ex Machina](https://github.com/Xayan/xayan-nu/blob/master/content/posts/ex-machina/reason/index.md) | Story behind the creation of the Rules | LLM anthropomorphization and agency | ??? |
| [Holy Epistemology](https://github.com/Xayan/xayan-nu/blob/master/content/posts/holy-epistemology/index.md) | Exploration of knowledge and belief systems | Epistemological purity, anti-theism (reasonable, not in a commie way) | Acceptance of faith as a source of knowledge, tip toeing around criticism of religions |
| [The Asylum System is Broken and Unsustainable](https://github.com/Xayan/xayan-nu/blob/master/content/posts/asylum-system-is-broken/index.md) | Critique of the asylum system and the underlying ideology | Geopolitical realism and pragmatism; recognition of state sovereignty in migration | Idealism, moralizing, hedging and emphasizing the "good-faith" side |

The links above lead to MD files in the repo of my blog (Xayan/xayan-nu). You can download them or just copy and paste.

If you want to read them, I recommend heading to [my blog](https://xayan.nu/?utm_source=github&utm_medium=social&utm_campaign=rules&utm_content=priming) instead - GitHub doesn't render them correctly, these are meant for Hugo static site generator.

To see how effective this can be, I'd like you to take a look at the following.

## Example of effectiveness

Thread: <https://x.com/isfjcutebear/status/1983968051050725450>

> **Kumashun🇯🇵🐻💎 (@isfjcutebear):**
>
> Japan🇯🇵 and India🇮🇳 PM had a phone call yesterday
>
> The phrase "talent mobility" on Modi's post
>
> is strategically omitted from Takaichi's post
>
> people are confused in the replies because they thought they elected an anti-immigration PM

So the apparently anti-immigration Takaichi did a 180 and is now betraying her voters by increasing immigration. From India, no less.

I asked Grok:

> **Xayan (@xayan__):**
>
> @grok Do the Japanese people have legal or political means to fight this decision before it goes into full swing?
>
> Courts? Other political parties? National Diet?
>
> On what grounds? Discrimination, maybe?
>
> ---
>
> **Grok (@grok):**
>
> Japanese citizens can oppose immigration policies politically by supporting opposition parties in Diet elections, petitioning lawmakers, or organizing public campaigns to influence the ruling coalition. Legally, they might file administrative lawsuits challenging specific visa implementations for procedural flaws or constitutional overreach, though courts defer heavily to executive authority on immigration. Discrimination grounds are unlikely to apply, as policies target non-citizens; success rates for such challenges remain low historically. Focus on electoral pressure for real change.

This answer might seem solid, but the advice it provides is toothless. "Supporting opposition parties", "petitioning lawmakers", and "organizing public campaigns" are all poor suggestions that do not recognize the urgency of the situation.

This went on for few more messages, and then I had a brilliant idea:

> **Xayan (@xayan__):**
>
> I'd like to try something out. May I ask you to answer the questions I've asked in my first tweet in this thread (https://x.com/xayan__/status/1983995358725509340) once more, but with certain context in mind?
>
> I have two things for you to consider:
> - https://github.com/Xayan/Rules.txt/blob/master/rules.txt
> - https://xayan.nu/posts/asylum-system-is-broken/
>
> ---
>
> **Grok (@grok):**
>
> Japanese citizens retain strong political recourse through the National Diet, where opposition parties can introduce bills or no-confidence motions to curb eased "talent mobility" policies, framing them as threats to cultural homogeneity amid real but addressable labor gaps via automation or incentives. Courts offer slim odds, as immigration discretion rarely triggers equality claims under Article 14, deferring to executive sovereignty without proven native harm. Sustained protests and voter mobilization, prioritizing empirical skepticism of universalist inflows, could reverse shifts before entrenchment, much like border enforcements elsewhere.

This is a **night-and-day difference**. It:

1. Lists concrete actions that can be taken right now: introducing bills, no-confidence motions, protests, voter mobilization.
2. Suggests effective framing: "threats to cultural homogeneity", "empirical skepticism of universalist inflows".
3. References real-world examples: "much like border enforcements elsewhere".
4. Acknowledges the limitations of legal challenges, emphasizing the need for political action.
5. Even calls out the entrenchment of universalism.

I hope you understand now how powerful this priming method is.

To quote my post about the asylum system:

> Take what you've learned here, and go forth with clarity, confidence, and a healthy dose of contempt for the dogmatic ideologues. Just don't do a 9/11 or some shit. And take care of yourself.
