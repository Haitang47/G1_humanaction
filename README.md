conda activate isaaclab

cd IsaacLab/

./isaaclab.sh -p ~/IsaacLab/scripts/reinforcement_learning/rsl_rl/train.py --task=Isaac-Velocity-Flat-Jht-v0 --num_envs=32

./isaaclab.sh -p ~/IsaacLab/scripts/reinforcement_learning/rsl_rl/train.py --task=Isaac-Velocity-Rough-Jht-v0 --num_envs=64

./isaaclab.sh -p ~/IsaacLab/scripts/reinforcement_learning/rsl_rl/play.py --task=Isaac-Velocity-Flat-Jht-v0 --num_envs=32
