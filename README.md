# Abstract

There is an ever-growing need in the gravitational wave community for fast and reliable inference methods, accompanied by an informative error bar. Nested sampling satisfies the last two requirements, but its computational cost can quickly become prohibitive, and current pipelines employing nested sampling will not scale well for the next generation of data. However, the integration of machine learning and the adoption of GPUs can accelerate nested sampling by several orders of magnitude, working towards addressing these challenges and providing a complementary approach to alternative techniques like simulation-based inference. I will discuss the acceleration of nested sampling using a technique called posterior repartitioning, combined with normalizing flows, which leverages nested sampling's unique ability to separate prior and likelihood contributions at the algorithmic level. I will also go on to discuss recent work by my group on a blackjax implementation of nested sampling, enabling GPU-accelerated pipelines for next generation gravitational wave inference.
  

  

