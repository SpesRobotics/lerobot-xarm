# LeRobot + xArm Integration

Brings a simple integration with [LeRobot](https://github.com/huggingface/lerobot) and [xArm](https://github.com/xArm-Developer).

## Getting Started

```bash
pip install lerobot-xarm

python -m lerobot.teleoperate \
    --robot.type=lerobot_xarm.xarm.Xarm \
    --robot.id=black \
    --teleop.type=keyboard_ee \
    --fps=60
```

## Development

Install the package in editable mode:
```bash
git clone https://github.com/SpesRobotics/lerobot-xarm.git
cd lerobot-xarm
pip install -e .
```
