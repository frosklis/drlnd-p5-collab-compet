# Collaboration and competition

This is the last project from Udacity's deep learning nano degree where we
 have a multi-agent environment in which two agents have to collaborate.
 
# Details

This is a tennis environment where two players (agents) have to keep the
 ball in play. To meet that goal the rewards are designed this way:

- If an agent hits the ball over the net, it gets +0.1 points.
- If it misses (the ball bounces) or it throws the ball out of the field, it
 receives a reward of -0.01 points
- The "game reward" is computing by taking the maximum of each agent's reward

The task is considered solved if the average score over a period of 100
 games is greater than +0.5.
 

## To run this code

First create a python environment with python 3.6 and install the requirements from the requirements file. If using conda:

```bash
conda install -n myenv python=3.6
pip install -r requirements.txt
```

You also need jupyter notebook, install it if not already in your system. And make sure you add the environment you created to it.

```
conda install ipykernel
````

Finally, make sure you download the tennis environment (not part of this repo). Depending on yor platform, you can get it for: 
- [Linux](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Linux.zip)
- [Mac](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis.app.zip)
- [Windows 32-bit](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Windows_x86.zip)
- [Windows 64-bit](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Windows_x86_64.zip)

See the demo in Report.ipynb

Enjoy!
