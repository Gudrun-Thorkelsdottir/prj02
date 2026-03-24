## Presentation Outline

The goal of the final project is to develop a computational example in SciML and to present your approach and findings to the class.  The style of the talk should be somewhere between a class lecture and a research talk.  But be careful with your time -- you will have around 8-9 minutes (still tentative)!

A summary of the rubrics for the presentation are as follows:

**SP, Statement of problem**

    What is the problem that you are looking at?
    Is the problem clear? Have you provided enough background information for the audience to follow?
    Do you have a clear summary and goals?

**ID, Implementation details**

    What details are needed to understand the implementation?
    Did you clearly outline the method and approach?
    Did you state the loss?
    Do you provide a sufficient level of detail?

**R, Results**

    Do your results highlight the overarching goal of your project?
    Are your results clear? Do you label important details? Do you use relevant and consistent color schemes?
    Carefully select which visualizations to show. We do not need to see everything, only figures that highlight some aspect of the goal of your mini app.
    Do you highlight a few (but not all) of the results?

**C, Reflections**

    What did you learn? What worked, what needs improvement, what are the next steps or future directions?
    Is your presentation practiced and on time? Is your slide deck of high quality?

## Outline

With an 8-9 minute presentation, you will have roughly 9 slides.

## Your turn

Describe each slide (briefly! only a partial sentence or two each)

1. Problem Setup: Why is uncertainty quantification important?
2. Introduce the generative modeling problem: sampling from an unknown distribution.
3. Short introduction to flow-based generative models: Neural ODEs
4. Mechanism for exact likelihood calculation through the instantaneous change of variables formula.
5. High-level steps for my uncertainty quantification algorithm
6. Results: correlation between accuracy and likelihood
7. Results: likelihood of rare or out-of-distribution samples
8. Summary of findings
9. Future work

Things to include: what figure do you expect, what sources are you following, how much math do you expect you'll need?

* There will be two main figures: (1) the correlation between sample accuracy and likelihood, and (2) likelihood results of rare or our-of-distribution (different dataset) samples. The second figure may be images with likelihood labels
* The background for this project is quite math-heavy, I will need to find an appropriate level to include in the presentation.
* I need to decide what pretrained model to use: ideally I can find a pretrained checkpoint for a deterministic generative model online. If not, I have a pretrained flow matching model for bioinformatics data, but I need to find a good accuract metric to use.
