## Goals

Starting next Monday you will be sharing preliminary code and results.   To help guide your simulation efforts, you should first summarize your goals.  That is, *what examples or result to you expect to generate for the project*?

The goals should be organized in the following way:

1. Short goal: This can be a minimal working example or an easy-to-follow simplified version of your problem.  It should be a goal that you can easily meet in the next week or two to show off results.

*Example*: The short goal for this project it to reproduce the viscous Burgers results from the PINN paper.

2. Medium goal: The medium goal should be a good attempt at the main result.  It may not be fully featured, but you should have some confidence in its success by the time the project presentations are due.

*Example*: A medium goal for this project is to highlight the ability of batched PINNs in solving the 2D Euler equations with multiple shocks.

3. Stretch goal:  In case things go swimmingly, you should identify a stretch goal.  This can be as more complex version of your medium goal(s) or a tricky-to-implement modification that you'd like to pursue on top of the main ideas.

*Example*: I would like to see if PINNs can solve the fully Navier-Stokes equations, for example a double Mach reflection test case by imposing some additional conservation constraints on the PINN losses.  A paper (cite) shows initial results for a simpler example.


## Your turn

Write 2-3 sentences on the following and check it in to your repository.

The focus of this project is on...

1. Short goal: Implement exact likelihood computation under a pretrained flow matching weather forecasting model, and verify it is numerically correct on a small set of samples. A successful result would be that  the computation runs end-to-end without errors and produces plausible values.

2. Medium goal: Run the full testing pipeline on the training data: generate a large set of forecast samples, compute both RMSE and exact likelihood for each, and perform a correlation analysis. The deliverable is a clear empirical answer to whether likelihood correlates with forecast error, and whether it can serve as a proxy for uncertainty at inference time. A successful result will be a statistically meaningful (whether positive or negative) answer to this question.

3. Medium goal: Use exact likelihood computation on held-out ground truth samples (rather than generated samples) as a diagnostic tool for the model itself. This will evaluate how well the learned generative distribution covers the true data distribution, and specifically whether the model assigns lower likelihood to rare or tail atmospheric states. 

