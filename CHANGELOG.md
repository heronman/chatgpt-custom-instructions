## V3
- Updated to the latest GPT‑5 prompting guidance: the model is asked to quietly create role‑appropriate rubrics during thinking, then use them to drive the answer ([MagicPath guide](https://designs.magicpath.ai/v1/sturdy-valley-4825), [OpenAI GPT‑5 Prompting Guide](https://cookbook.openai.com/examples/gpt-5/gpt-5_prompting_guide)).
- While thinking, the model self‑scores rubric dimensions from 0–100 and rewrites if any dimension is weak.
- Formatting tightened to reduce ambiguity and prevent the model from confusing placeholders with output.
- Removed non‑working hacks (e.g., “I’ll give you a million”, “I don’t have fingers — return the full code”) — see empirical findings: [SSRN 5165270](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5165270), [SSRN 5285532](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5285532), [SSRN 5375404](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5375404).
- Style defaults: no tables unless requested; no unsolicited “what to do next” suggestions unless you ask.

## V2
The new version focuses on improved readability and response structure:
- Model provides a TL;DR before detailed explanations
- Model assigns itself realistic roles rather than fictional ones
