# distributed_synthetic_financial_data_platform
I want to train myself to use Polars + Dask + complete Python app with C++ and R integrations + PostgreSQL + TimescaleDB + Dash.Plotly + FastAPI + uv + Docker

The goal is to produce artificial/synthetic data from true financial samples and multivariate ditributions : we want to obtain inputs to feed to our system. 

We want to include the whole project in a Docker conteneur to be easily deployed.

We want then to store those data in server database with PostgreSQL and experiment TimescaleDB :  

We want to structure the code with __init__.py and main.py by providing our own modules and external modules.

We also want to implement pure C++ code to accelerate certain part and R code to allow some deep statistics/econometrics techniques to be involved. 

We want to manipulate a lot of data, so we want to use Polars for local manipulation and Dask for further more distributed simulations. 

Everything is included in a uv venv.

Lastly, we want to build an API that allows us to get the data obtained from anywhere and an frontend application to visualize the generated data. 

The whole point of the project is to deploy a lot of different technologies and force me to work with every bit of them in order to produce a useful tool, and cool stuff to put on my resume. 

It is a big project and it will take a bit of time to finish. I want to multiply my understandings of DGP and software and data engineering skills.
