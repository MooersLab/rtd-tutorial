Blaine's Read-the-Docs Tutorial
===============================

Log into into your read the docs account.
Then import your new project from a GitHub repo
or select an existing project.

You can edit the README.rst document on GitHub and then
you have to go through a number of steps. It is probably
best to prepare the bulk of the docment in an editor
that is configured for handling ReStructuredText files. 
Otherwise, you will get a alot of practice cycling 
through the following steps. This will increase the 
chance of making mistakes and learning from them, :octocat: :

- Add a commit message.
- Click on 'Create a new branch for this commit and start a pull request'. 
- Click on 'Propose Changes'. This action takes you to a new page.
- Click on 'Create pull requst'. A message in yellow appears about check in progress.
- When the checks are done, the yellow text changes to green. Click on 'merge pull request'.
- Navigate to the github repo page. The text will be updated but not the math.
- Click on the browser's refresh button to get MathJax to render the equations.

The document is written in ReStructuredText (.rst), 
which takes LaTeX multi-line equations in special math blocks.
The backslashes have to to escaped and the double $$ removed.

.. math::
$$
\\begin{aligned}
y_{i} & \\sim \\operatorname{Normal}\\left(\\mu_{i}, \\sigma\\right) \\\\
\\mu_{i} &=\\alpha+\\beta x_{i} \\\\
\\alpha & \\sim \\operatorname{Normal}(0,100) \\\\
\\beta & \\sim \\operatorname{Normal}(0,1) \\\\
\\sigma & \\sim \\operatorname{Exponential}(1)
\\end{aligned}
$$
:label: abc

Read the tutorial here:

https://docs.readthedocs.io/en/stable/tutorial/

