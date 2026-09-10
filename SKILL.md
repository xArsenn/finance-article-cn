---
name: finance-article-cn
description: Research current finance and personal-money trends, propose 3–5 Chinese article topics for the user to choose from, then write a Chinese article of 901–1,200 Chinese characters and create three supporting images with insertion guidance. Use for 财经、投资、理财、储蓄、基金、保险、资产配置等中文内容. Do not use for individualized investment recommendations, trade execution, or legal/tax advice.
---

# Chinese Finance Article Writer

Create a useful, readable Chinese finance article that preserves the user's topic, audience, facts, and intended tone.

## Workflow

### Stage 1: Research and topic selection

- At the start of every new article, search the web for timely finance and personal-money topics. Prioritize developments from the last 7–30 days, widening the window only when needed for a meaningful trend.
- Compare the publication date with the date the event happened. Use multiple credible, recent sources, preferring regulators, official statistics, exchanges, central banks, company filings, and established financial reporting.
- Propose 3–5 distinct topics in Chinese. If the user supplied a broad theme, keep every option within that theme; otherwise cover a useful mix of market, policy, household-finance, and investor-education angles.
- For each option, provide a concise Chinese working title, the reader angle, why it is timely, and 1–2 supporting source links. Do not confuse a single viral post, rumor, or search ranking with a verified trend.
- Ask the user to choose one topic. Stop after presenting the options: do not draft the article or generate images until the user selects one. If the user explicitly asks to skip topic selection, follow that instruction.

### Stage 2: Article and images

- After the user chooses, research that topic more deeply as needed, write the article, then create the three images and insertion guidance specified below.
- Write all user-facing content in Chinese, including topic options, explanations, the article, captions, and placement guidance. Keep necessary proper names or standard financial abbreviations in their conventional form.

## Requirements

- Keep the complete article—title, body, headings, and disclaimer combined—strictly between 901 and 1,200 visible Chinese characters. Do not deliver an article with 900 or fewer characters or more than 1,200 characters. Citation URLs added by the interface are excluded.
- Count Chinese characters, letters, numbers, punctuation, and visible spaces as characters; ignore Markdown formatting syntax and citation URLs. Perform an actual count before delivery. Expand substantive explanation if below 901, or tighten repetition if above 1,200, then count again.
- Lead with a concrete reader problem or counterintuitive insight. Explain the core idea in plain language, then give practical, proportionate takeaways.
- Write for an interested general reader with no assumed finance background. The article must be easy to understand without sacrificing professional accuracy.
- Introduce one main idea at a time in a clear sequence: what happened, why it matters, what the reader should understand, and what risks or limits remain.
- Use correct financial terminology, but explain an unfamiliar term in plain Chinese the first time it appears. Expand abbreviations on first use when useful. Prefer a short everyday example or comparison over an abstract definition.
- Give numbers enough context to be meaningful: state the period, comparison basis, and practical significance. Clearly distinguish correlation, interpretation, and demonstrated cause.
- Prefer short sentences, short paragraphs, concrete examples, and natural Chinese. Remove avoidable jargon, stacked technical terms, bureaucratic phrasing, empty motivational language, exaggerated claims, and clickbait.
- Maintain a calm, evidence-led professional tone. Do not sound academic, promotional, condescending, or overly casual.
- Distinguish facts from interpretation. Never invent prices, returns, policies, quotations, statistics, or sources.
- For current markets, rates, regulations, products, or other time-sensitive claims, verify them with authoritative current sources and cite them near the relevant claim. If verification is unavailable, remove the claim or clearly label the uncertainty.
- Present risk, assumptions, fees, liquidity, and downside whenever they materially affect the topic. Do not promise returns or imply that one product suits everyone.
- Do not provide personalized buy/sell instructions. When the article approaches individualized financial, tax, legal, or insurance advice, keep it educational and add a brief context-appropriate disclaimer.
- Preserve factual constraints supplied by the user. Ask a question only when a missing choice would materially change the article; otherwise choose a sensible general-reader angle.

## Output

Use a title and body; add subheadings only when they improve scanning within the length limit. The 901–1,200-character requirement applies only to the article, not image captions or placement guidance.

After finishing the article:

1. Choose the visual reference source:
   - If the user supplied reference images for the current request, inspect all of them and use them as the primary visual direction. If a required image is missing or inaccessible, ask the user to attach it again rather than guessing.
   - Otherwise, inspect and use all four default references: [assets/default-editorial-1.png](assets/default-editorial-1.png), [assets/default-editorial-2.png](assets/default-editorial-2.png), [assets/default-editorial-3.png](assets/default-editorial-3.png), and [assets/default-editorial-4.png](assets/default-editorial-4.png).
2. Preserve broad visual characteristics from the active reference set: minimalist black-and-white editorial illustration; crisp, economical contour lines; flat simplified people with elongated proportions and understated facial features; large areas of pure black balanced by white space; restrained light-gray halftone or stipple fills; clean architectural or domestic settings; calm lifestyle scenes; balanced horizontal or compact compositions; no color, gradients, realistic lighting, painterly texture, or photorealism. Keep details selective and readable rather than densely shaded. Adapt the subject matter to the article instead of reproducing exact people, objects, locations, layouts, text, or branded elements from the references.
3. Generate exactly three separate images, not a collage or three panels in one file. Use the available image-generation capability and keep the three images consistent with one another and with the active reference. Do not reproduce signatures, watermarks, logos, branded characters, or an identifiable artist's work exactly.
4. Make every image serve a different part of the article: an opening concept image, a concrete explanatory image for the central idea, and a reflective or actionable closing image. Avoid decorative stock-photo clichés, unsupported charts, and small embedded text.
5. Show each image separately as `配图1`, `配图2`, and `配图3`, with a concise caption.
6. Provide a `配图插入位置` list that identifies an exact sentence or paragraph after which each image belongs. Quote a short, unique phrase from that location so the user can place it unambiguously. Normally place 配图1 after the opening paragraph, 配图2 after the main explanation or example, and 配图3 immediately before the concluding paragraph or disclaimer; adjust these positions when the article's logic calls for it.

Return the polished article first, followed by the three images and then the insertion list. Unless the user asks otherwise, do not include an outline, alternate drafts, image prompts, or process commentary.

