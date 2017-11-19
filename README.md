# Our NIPS 2017: Learning to Run approach

Write up: https://medium.com/@stelmaszczykadam/our-nips-2017-learning-to-run-approach-b80a295d3bb5

Main files:

- [`run_osim.py`](https://github.com/AdamStelmaszczyk/learning2run/blob/master/run_osim.py) to run baselines PPO
- [`baselines/baselines/pposgd/pposgd_simple.py`](https://github.com/AdamStelmaszczyk/learning2run/blob/master/baselines/baselines/pposgd/pposgd_simple.py) observation processing for PPO  
- [`example.py`](https://github.com/AdamStelmaszczyk/learning2run/blob/master/example.py) to run keras-rl DDPG (with old observation processing)
- [`es/localhost/launch.py`](https://github.com/AdamStelmaszczyk/learning2run/blob/master/es/localhost/launch.py) to run Evolution Strategies
- [`osim-rl/osim/env/run.py#L67`](https://github.com/AdamStelmaszczyk/learning2run/blob/master/osim-rl/osim/env/run.py#L67) reward hacking
