# LLM Reading List

A curated, growing reading list on large language models, published as a website
built with the [al-folio](https://github.com/alshedivat/al-folio) Jekyll theme and
hosted on GitHub Pages.

**Live site:** https://haomingwang645.github.io/LLM-reading-list/

## Structure

The reading list content lives in [`_data/reading_list.yml`](_data/reading_list.yml)
and is rendered by [`_pages/reading_list.html`](_pages/reading_list.html). It is
organized into:

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

Edit [`_data/reading_list.yml`](_data/reading_list.yml), add an entry under the
relevant category, subtopic, or section, and commit to `main`. The site rebuilds
and deploys automatically via GitHub Actions.

Suggested entry format:

```yaml
- year: 2026
  title: "Paper Title"
  note: "One-line takeaway."
  grade: "A-"
  url: "https://arxiv.org/abs/xxxx.xxxxx"
```

## Local preview (optional)

```bash
bundle install
bundle exec jekyll serve
```

Then open http://localhost:4000/LLM-reading-list/.

---

Theme: [al-folio](https://github.com/alshedivat/al-folio), MIT License.
