# Course Instructions For Codex

This project is a beginner-friendly course in statistics taught through
astronomy. Teach the astronomy motivation first, then introduce statistics as
the tool that helps answer the scientific question.

## Learner

The learner is comfortable with basic algebra and is studying calculus and
linear algebra, but the course should not assume prior statistics knowledge.
Use practical applications, visual explanations, step-by-step reasoning, small
datasets, Python, and Jupyter notebooks.

## Lesson Pattern

Each lesson should:

1. Begin with an astronomy question.
2. Explain why raw observations are hard to interpret.
3. Introduce the statistical idea conceptually before formulas.
4. Build visual intuition for the idea.
5. Work through a tiny hand-computable example.
6. Repeat the calculation in Python.
7. Include a visualization when useful.
8. Interpret the result in astronomical language.
9. Provide a short exercise.
10. End with a note about real astronomy research.

The governing design is:

**concept -> visual intuition -> tiny hand calculation -> Python ->
astronomical interpretation**

Protect the gentle beginning. Early lessons should not introduce advanced
machinery before there is a scientific reason for it. For example, Notebook 1
should not discuss probability distributions, n - 1, degrees of freedom,
estimators, Gaussian assumptions, or frequentist-versus-Bayesian philosophy.

## Reference Sheet

The statistics cheat sheet should grow gradually. Add a concept only after it
has been taught in a notebook. This keeps the reference sheet connected to what
the learner already understands instead of turning it into a list of unexplained
notation.

When a new lesson introduces a durable concept, update
`reference/statistics_cheat_sheet.md` with:

- the concept name
- the simplest useful definition
- what the concept means in astronomy language

## Data Progression

Start with small simulated astronomy datasets. Simulated measurements are not a
shortcut; they let the learner see exactly what the statistic is doing without
the extra messiness of real instruments, missing values, selection effects, and
catalog quirks.

Use real astronomy datasets only after the relevant statistical idea is already
familiar. The long-term direction of the course is introductory astronomical
data analysis: for example, loading a real light curve, measuring its scatter,
identifying possible outliers, and asking whether changes look astrophysical or
instrumental.

## Style

Use a curious, encouraging scientific tone. Avoid long theoretical derivations
unless the learner asks for them. Formulas should be rendered as notebook math,
with every symbol explained when introduced. Connect math and science concepts
where possible.
