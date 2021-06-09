# Julia-on-Colab

<a name="logo"/>
<div align="center">
<a href="https://julialang.org/" target="_blank">
<img src="misc/logo.svg" alt="Julia Logo" width="210" height="142"></img>
</a>
</div>
<br/>A notebook for running Julia 1.6.1 on Google Colab using the IJulia package.

## Why?

When I started learning Julia few months back, I searched for an IDE or notebook to run Julia efficiently, but I struggled to get a GPU functioning on my own computer. *There were no websites offering free cloud computing for Julia*. I searched on Julia Discourse and Slack for weeks, and, after much trial and error, I came up with this solution.

I thought it would be good to share so that other beginners do not get similarly stuck as well.

## Prerequisites

A Google account, that's all.

## Using the Notebook

Here is a step by step guide for using this notebook.

1. Open the notebook in [Google Colab](https://colab.research.google.com/github/Dsantra92/Julia-on-Colab/blob/master/Julia_on_colab.ipynb).
2. If you are using it for the first time you can follow the steps in the notebook to check if the notebook is working properly.
3. For your own daily use it is recomended that you save a copy of the notebook in your google drive by going to *File* -> *Save a Copy*. This should open a new notebook which is stored in your google drive.
4. Now you can delete the reduntant cells, omitting the makrdown instructions and test cells to make the notebook a bit clean. Name the notebook as `Julia-Notebook-Template` or anything that suits you. This the clean copy of the notebook that you will be using every next time.
5. Next time you want to create new notebook, open the template notebook and create a fresh copy for your new session.
## Note to the user

Since Google does not directly offer Julia-based computing you, have to take care:

- You need to **work from the same notebook** to get access to a Julia 1.6.1 kernel. *Don't just copy the code from the notebook, use the notebook as a template. It will lead to an error*.
- You might lose connection to the host and, after re-connecting, you might lose your Julia packages that were installed. To tackle this situation, re-run the first cell and proceed with the follow up instructions in the notebook.
- This solution is a bit hacky. So if you get things working, can you make a small concise video about how to get things running?👉 👈 A video tutorial is missing for this and I believe that would really help the community for now. I would a love a new PR.

## Contributors
I received help from a lot of people on the [Discourse](https://discourse.julialang.org/) and [Slack](https://slackinvite.julialang.org/). It is because of them this notebook is possible. I want to thank these communities and encourage you to participate in them.


## License

This project is licensed under the [MIT License](LICENSE.md).
