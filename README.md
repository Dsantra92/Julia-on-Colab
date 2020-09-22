# Julia-on-Colab

<a name="logo"/>
<div align="center">
<a href="https://julialang.org/" target="_blank">
<img src="misc/logo.svg" alt="Julia Logo" width="210" height="142"></img>
</a>
</div>
<br/>A notebook for running Julia 1.5.0 on Google Colab using the IJulia package.

## Why?

When I started learning Julia few months back, I searched for an IDE or notebook to run Julia efficiently, but I struggled to get a GPU functioning on my own computer. *There were no websites offering free cloud computing for Julia*. I searched on Julia Discourse and Slack for weeks, and, after much trial and error, I came up with this solution.

I thought it would be good to share so that other beginners do not get similarly stuck as well.

## Prerequisites

A Google account, that's all.

## Using the Notebook

A step-by-step guide that tells you how to get the environment running:
1. Open the [Jupyter notebook](https://github.com/Dsantra92/Julia-on-Collab/blob/master/julia_on_collab.ipynb).
2. You can either download it or view it directly on [Google Colab](https://colab.research.google.com/github/Dsantra92/Julia-on-Colab/blob/master/julia_on_collab.ipynb).
3. Run the first cell to install Julia and IJulia.

#### Note to the user

Since Google does not directly offer Julia-based computing you, have to take care:

- You need to **work from the same notebook** to get access to a Julia 1.5.0 kernel._Don't just copy the code from the notebook, use the notebook as a template. It will lead to an error_.
- You might lose connection to the host and, after re-connecting, you might lose your Julia packages that were installed. To tackle this situation, re-run the first cell and proceed with the follow up instructions in the notebook.
- If you want to create your own notebook, I suggest you use this as a base notebook to work from.

## Contributing
I received help from a lot of people on the [Discourse](https://discourse.julialang.org/) and [Slack](https://slackinvite.julialang.org/). It is because of them this notebook is possible. I want to thank these communities and encourage you to participate in them.


## License

This project is licensed under the [MIT License](LICENSE.md).
