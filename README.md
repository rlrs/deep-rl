# deep-rl

Deep Reinforcement Learning in [Tensorflow](https://github.com/tensorflow/tensorflow).
Aiming to reproduce results from interesting papers. Features from some of the newer papers on deep reinforcement learning will hopefully be implemented soon.
Later some personal novel techniques might be implemented.

## Project plan
Currently implemented:
- Vanilla DQN
- Double Q-learning

Tentative list of potential features:
- Bootstrapping
- Prioritized experience replay
- Asynchronous actor-critic

## How to run
Install [Tensorflow](https://github.com/tensorflow/tensorflow) in Python 2.7.

Install [Sacred](https://sacred.readthedocs.org/en/latest/index.html) (only necessary for supplied run scripts, you can make your own).

Install [ALE](https://github.com/mgbellemare/Arcade-Learning-Environment).

Configure the run script you want to use (e.g. run_nature.py).

Run it!


## License
Copyright 2016 Rasmus Larsen

This software may be modified and distributed under the terms
of the MIT license. See the LICENSE.txt file for details.
