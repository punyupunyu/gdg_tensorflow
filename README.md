# gdg_tensorflow


##Setup

>OpenAI Gym was created for an Ubuntu environment and it's suggested that you do run it in that environment. (I have horror stories of trying to get it set up on Windows.)
>You may need to install some pre-requisites before you get started:
>Run the following code to install the required packages on Ubuntu.
```
apt-get install -y python3-dev python-dev python-numpy libcupti-dev libjpeg-turbo8-dev make golang tmux htop chromium-browser git cmake zlib1g-dev libjpeg-dev xvfb libav-tools xorg-dev python-opengl libboost-all-dev libsdl2-dev swig
```
>Or you can install Anaconda 3 and have most of the libraries.
>
>After installing all the requisite libraries, you'll need to install OpenGym AI. You can go here for details: <a>https://gym.openai.com/docs/</a>
>
>You'll need Python 3.5+. To install OpenGym AI you can either
```
pip install gym
```
>
>Or build from source:
>
>
```
git clone https://github.com/openai/gym
cd gym
pip install -e .
```
>