# LLM Reading List

A curated, growing reading list on large language models, published as a website
built with the [al-folio](https://github.com/alshedivat/al-folio) Jekyll theme and
hosted on GitHub Pages.

**Live site:** https://haomingwang645.github.io/LLM-reading-list/

## Structure

The reading list (see [`_pages/reading_list.md`](_pages/reading_list.md)) is organized into:

1. ML and LLM basics
2. Modern LLM architecture
3. LLM infrastructure (optimization for modern LLMs)
4. LLM reasoning
5. Reinforcement learning
6. Topic 1: Spatial reasoning
7. Topic 2: LLM explainability
8. Topic 3: World models
9. Topic 4: Diffusion LLMs
10. Others

## Adding papers

Edit [`_pages/reading_list.md`](_pages/reading_list.md), add a bullet under the
relevant heading, and commit to `main`. The site rebuilds and deploys automatically
via GitHub Actions.

Suggested entry format:

```markdown
- [Paper Title](https://arxiv.org/abs/xxxx.xxxxx) — *Authors, Venue Year.* One-line takeaway.
```

## Local preview (optional)

```bash
bundle install
bundle exec jekyll serve
```

Then open http://localhost:4000/LLM-reading-list/.

---

Theme: [al-folio](https://github.com/alshedivat/al-folio), MIT License.
