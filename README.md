[![Click to access video lectures](https://i.imgur.com/OpDza8d.png)](https://wandb.me/m4ml-videos)

# Math for Machine Learning

This short course introduces the core concepts and intuitions
of the three most important branches of mathematics
for machine learning:
linear algebra,
calculus,
and probability.

These notebooks are supplementary to
a [YouTube lecture series](https://www.youtube.com/watch?v=uZeDTwWcnuY&list=PLD80i8An1OEGZ2tYimemzwC3xqkU0jKUg)
and presume proficiency with Python.


## Local Install -- Docker

If you'd like to run the materials locally,
the best option is to use
[Docker](https://docs.docker.com/get-docker/),
one of the virtualization technologies
on which Binder is based.

After following the installation instructions for Docker,
build the container with the command
```
docker build -t math-for-ml .
```
and then start it with the command
```
docker run -p 8888:8888 math-for-ml
```
Open a browser window and navigate to
```
localhost:8888
```
and enter, as the password, the token that appears after
`?token` in the URLs printed to the terminal by Jupyter.
