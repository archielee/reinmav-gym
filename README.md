# Assuming that you already installed openai gym (https://github.com/openai/gym)

# reinmav-gym
openai gym environment for reinforcement quadrotor

# Installation
(venv) Username@reinmav-gym $ pip install -e .

## Check installation
pip list

pip show gym-reinmav

``` pip show gym-reinmav
Name: gym-reinmav
Version: 0.0.1
Summary: UNKNOWN
Home-page: UNKNOWN
Author: UNKNOWN
Author-email: UNKNOWN
License: UNKNOWN
Location: /Users/Inkyu/Research/ETH_Postdoc/SideProjects/openai/venv/lib/python3.6/site-packages
Requires: gym
Required-by: 
```

# Testing
(venv) Username@reinmav-gym $python ./test/test_reinmav.py

``` __init__ called
reset() called
step() called
render() called
```

# openai gym example environments
* Continuous mountain car: https://github.com/openai/gym/blob/master/gym/envs/classic_control/continuous_mountain_car.py
* Cart pole: https://github.com/openai/gym/blob/master/gym/envs/classic_control/cartpole.py
* Pendulum: https://github.com/openai/gym/blob/master/gym/envs/classic_control/pendulum.py
