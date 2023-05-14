# Algorithmically identifying highs and lows

## Quantopian paper
<a href="https://github.com/rushic24/quantopian-offline-2020/blob/master/An%20Empirical%20Algorithmic%20Evaluation%20of%20Technical%20Analysis.ipynb">Empirical Algorithmic Evaluation of TA</a>

<a href ="https://quantopian-archive.netlify.app/forum/threads/an-empirical-algorithmic-evaluation-of-technical-analysis.html">Discussion copied across to here</a>.  Most striking to me is the comment from Thomas Wiecki on the <a href="https://quantopian-archive.netlify.app/forum/threads/alphalens-a-new-tool-for-analyzing-alpha-factors.html">Alphalens</a> alpha decay, which looks like it uses the code from <a href="https://github.com/quantopian/alphalens/blob/master/alphalens/examples/alphalens_tutorial_on_quantopian.ipynb">here</a>

## Medium Blog Post - does it avoid information leakage?
<a href="https://medium.com/automation-generation/algorithmically-detecting-and-trading-technical-chart-patterns-with-python-c577b3a396ed">This post by samcha</a> uses a different scikit package which might avoid some of the information leakage from the kernel regression in the Andrew Lo paper.
