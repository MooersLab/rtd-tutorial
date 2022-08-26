Template for the Read the Docs tutorial
=======================================

This GitHub template includes fictional Python library
with some basic Sphinx docs.

You can edit the README.st document on GitHub and then
you have to go through several steps:

- Add a commit message.
- Click on 'Create a new branch for this commit and start a pull request'. 
- Click on 'Propose Changes'. This action takes you to a new page.
- Click on 'Create pull requst'. A message in yellow appears about check in progress.
- When the checks are done, the yellow text changes to green. Click on 'merge pull request'.
- Navigate to the github repo page. Click on the browser's refresh button to get view.

The document is written in ReStructuredText (.rst), 
which takes LaTeX multi-line equations in special math blocks.
The backslashes have to to escaped and the double $$ removed.

.. math::

\\begin{aligned}
y_{i} & \\sim \\operatorname{Normal}\\left(\\mu_{i}, \\sigma\\right) \\\\
\\mu_{i} &=\\alpha+\\beta x_{i} \\\\
\\alpha & \\sim \\operatorname{Normal}(0,100) \\\\
\\beta & \\sim \\operatorname{Normal}(0,1) \\\\
\\sigma & \\sim \\operatorname{Exponential}(1)
\\end{aligned}


Read the tutorial here:

https://docs.readthedocs.io/en/stable/tutorial/

