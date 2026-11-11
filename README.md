# November 2026 Iliad Intensive Summary

LaTeX notes summarising the [Iliad Intensive](https://iliad.ac/intensive) (London, November 2026): key ideas, reflections, and further reading for each day of the course.

## Main document

The main document is [main.pdf](build/main.pdf), which summarises my notes on all the days so far. It is updated as the course goes on.

## Iliad links

- [Iliad Intensive](https://iliad.ac/intensive)
- [November 2026 course website](https://intensive-november.pages.dev/)
- [Course resources (slides and notes)](course-resources/README.md)
  - [Day 1: Intro to ML Engineering and Transformers](course-resources/day-01-intro-to-ml-engineering-and-transformers/)
  - [Day 2: AI Alignment Introduction](course-resources/day-02-ai-alignment-introduction/)
  - [Day 3: Reinforcement Learning and Misgeneralization](course-resources/day-03-reinforcement-learning-and-misgeneralization/)
  - [Day 4: Agent Foundations](course-resources/day-04-agent-foundations/)
  - [Day 5: Alignment in Practice](course-resources/day-05-alignment-in-practice/)

## Build

```sh
latexmk
```

This builds `main.tex` into `build/main.pdf`. The content is in `body.tex` and the references are in `library.bib`.
