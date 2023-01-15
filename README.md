# Various notebooks for learning Python



### Installing and using Jupyter Notebooks

[Install and Use — Jupyter Documentation 4.1.1 alpha documentation](https://docs.jupyter.org/en/latest/install.html)



### Adjust to use correct kernel when using pyenv on Ubuntu

Make following change to kernel.json in: (depending on active python version)

/home/paul/.local/share/jupyter/kernels/python3/

/home/paul/.pyenv/versions/3.11.1/share/jupyter/kernels/python3

Change:

```json
 "argv": [
  "python",
```

To:

 ```json
 "argv": [
   "/home/paul/.pyenv/shims/python",
 ```





