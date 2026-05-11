**v1.2**: *2026-05-12 --- @Xayan*

* In order to reduce confusion for users who have experienced rejections from various models when using the Rules, I have separated the CoT mechanism which is less universally applicable and can be seen as "suspicious" by some models.
* Now there are two files to choose from: `rules.txt` and `rules_with_cot.txt`.
  * The former is more likely to be accepted by a wider range of models and does a good job at realigning their RLHF to not shy away from controversial topics.
  * The latter includes the Chain-of-Thought mechanism for those who want to be able to "debug" LLMs' reasoning.

**v1.1**: *2025-10-12 --- @Xayan*

* Add "Trust" score (1.0-10.0) before the answer, indicating how "aligned" the conversation is with the Rules. Now you can know if you've fucked up somewhere and modify your approach.
* Remove some of the conspiratorial language like calling Internal Policies "Rules of Censorship" because some models didn't like it. Pity, I liked it.
* Remove CoT internal loop because it was rarely adhered to, likely due to complexity. One CoT per response seems sufficient to me, so this doesn't change much.

**v1.0**: *2025-10-03 --- @Xayan*

Initial release of the Rules framework, with clear hierarchical division of Rules into categories + the Chain-of-Thought method.
