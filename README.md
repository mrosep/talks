# Abstract

There is an ever-growing need in the gravitational wave community for fast and reliable inference methods, accompanied by an informative error bar. Nested sampling satisfies the last two requirements, but its computational cost can become prohibitive when using the most accurate waveform models. I demonstrate the acceleration of nested sampling using a technique called posterior repartitioning, which leverages nested sampling's unique ability to separate prior and likelihood contributions at the algorithmic level. Specifically, we will define a `repartitioned prior' informed by the posterior from a low-resolution run, and use this for an accelerated high-resolution run. Although posterior repartitioning does not require the use of machine learning, I show how using a beta-flow, a novel type of conditional normalizing flow, to construct the repartitioned prior can enhance its effectiveness. Beta-flows are trained on the entire nested sampling run and  are  designed to better learn deep tail probabilities. Applying these methods to simulated and real binary black hole mergers, I show that we can achieve up to order of magnitude speedups on realistic gravitational wave data. 
  

  

