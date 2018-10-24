# py-repr-dina

In this project, we adapt Stan's education case study "DINA" (original work
http://mc-stan.org/users/documentation/case-studies/dina_independent.html
Copyright (c) 2017, Seung Yeon Lee licensed under BSD-3-Clause and CC BY).
We work in Python and follow the workflow outlined in our
[SciPy 2018 paper](http://conference.scipy.org/proceedings/scipy2018/vamvourellis_corvellec.html)
("A Bayesian’s journey to a better research workflow" first author
[Konstantinos Vamvourellis](https://github.com/bayesways)).

## Presentation

I first presented this work (in progress) at this seminar:
https://www.deib.polimi.it/eng/events/details/1629

## Setup

We work in a [conda](https://conda.io/) environment. If you are setting up the
environment for the first time, run:

    $ conda env create -f environment.yml

to install all dependencies in this isolated environment, named `py-repr-dina`.

If dependencies get updated, run:

    $ conda env update -f environment.yml

If you wish to remove the `py-repr-dina` environment, run:

    $ conda remove -n py-repr-dina --all

To work in the environment, we need to activate it:

    $ source activate py-repr-dina
