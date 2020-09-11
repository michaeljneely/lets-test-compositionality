# LET's Test Compositionality

## Abstract

In many Natural Language Processing (NLP) tasks, data-driven deep learning models have proven more effective than their traditional, symbolic counterparts. Neural networks can process large amounts of data and are therefore more robust to the intrinsic noise of natural language. However, does their success on isolated tasks mean they genuinely understand the languages they are processing? Or perhaps, are they just exploiting statistical patterns?

The principle of compositionality is a fundamental feature of natural language and serves as a rigorous test of the robustness of a model's learned representation. In its most broad definition, compositionality refers to "the meaning of a whole is a function of the meanings of the parts and of the way they are syntactically combined" ([Kamp and Partee, 1995](https://doi.org/10.1016/0010-0277(94)00659-9)). Note that this statement only refers to language itself, not the behavior of an entity using the language. To address this gap, ([Hupkes et al. 2019](https://arxiv.org/abs/1908.08351)) propose a suite of behavioral tests designed to evaluate the compositionality of a neural model across five dimensions. Of the five aspects, systematicity --- whether models systematically recombine known parts and rules --- and localism --- whether models' composition operations are local or global --- are of particular note.

In this research, we evaluate the compositionality of recurrent and attention-based neural models in terms of both localism and systematicity in the context of a sequence-to-sequence machine translation task on an artificial compositional language, which we call PFCG-LET.

## Authors

- Michael J. Neely
- Leila Talha

## Notes

This is a student project from the University of Amsterdam's Natural Language Processing 2, Spring 2020 course.
