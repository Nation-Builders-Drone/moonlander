# moonlander

A moon lander jupyter notebook with a simple demonstration of the classic problem. Why? To show a simple Neural Network implementation of this which can be improved and built on.

To install you will need a python v3 environment, if you do not have one, then anaconda is recommended : https://www.anaconda.com/products/individual

OpenAI gym is required too, this will probably require pip to install :

pip install gym

The other requirements should be included in the default conda install. In import required are :

numpy
matplotlib
collections
copy
tqdm
os

They should all be available with :

conda install <lib>
  
This takes about half an hour to run with the defaults, it may run faster with fewer hidden units or episode, but with poorer results. The challenge is to speed this up, create a gym model of the environment (see https://docs.google.com/document/d/10sXEhzFRSnvFcl3XxNGhnD4N2SedqwdAvK3dsihxVUA/edit#heading=h.wz5to0x8kqmr and https://github.com/openai/gym/blob/master/docs/environments.md#pybullet-robotics-environments )

A lot of work to do.
