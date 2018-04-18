# gym-doom
#### **Gym Doom is an environment bundle for OpenAI Gym**

Thanks a lot to ppaquette for coding this. Since his repository is no longer maintained, I forked it and made it compatible with the current version of gym.

---
<div id="installation"></div>Installation
============

You need to install [gym-pull](https://github.com/simontudo/gym-pull)

 To load and run the environments, run

```python
    import gym
	import gym_pull
	gym_pull.pull('github.com/simontudo/gym-doom')        # Only required once, envs will be loaded with import gym_pull afterwards
	env = gym.make('simontudo/DoomBasic-v0')
```

Dependencies:
============

To install dependencies, run the following:

```shell
    apt-get install -y python-numpy cmake zlib1g-dev libjpeg-dev libboost-all-dev gcc libsdl2-dev wget unzip git
```

Environments included:
============
- ~~aquette/meta-Doom-v0~~
- ppaquette/DoomBasic-v0
- ~~aquette/DoomCorridor-v0~~
- ~~ppaquette/DoomDefendCenter-v0~~
- ~~ppaquette/DoomDefendLine-v0~~
- ~~ppaquette/DoomHealthGathering-v0~~
- ~~ppaquette/DoomMyWayHome-v0~~
- ~~ppaquette/DoomPredictPosition-v0~~
- ~~ppaquette/DoomTakeCover-v0~~
- ~~ppaquette/DoomDeathmatch-v0~~
