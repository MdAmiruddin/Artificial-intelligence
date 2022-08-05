
                AI Documentation

To be installed inside a Terminal / Anaconda Prompt


For ​ Windows users, click the Windows button at the bottom left, then find anaconda in the list of
programs, and eventually click “Anaconda Prompt”.  https://stackoverflow.com/questions/47914980/how-to-access-anaconda-command-prompt-in-windows-10-64-bit?utm_medium=organic&utm_source=google_rich_qa&utm_campaign=google_rich_qa This is another way to find it.

For ​ Mac & Linux​ users, please open a terminal.

Then in the terminal (Mac/Linux users), or the Anaconda Prompt (Windows users), enter the
following commands one by one:

pip install gym==0.10.5
pip install pybullet==2.0.8
conda install -c conda-forge ffmpeg

These commands above only install what you need to get the PyBullet environments and
display them on your monitor. No AI framework such as TensorFlow or PyTorch needs to be
installed.


Dear Windows users,

we are about to launch the training and watch the final results, but before this you will need to download and install Visual C++ Build Tools on this link:

https://visualstudio.microsoft.com/visual-cpp-build-tools/

Basically Windows just needs this in the background to get the gym environments to work.

               The Half-Cheetah Environment

We will play with the Half-Cheetah environment, inside which we will train with our ARS a
cheetah to run across a field. The name of this environment is “HalfCheetahBulletEnv-v0”.

The environments of PyBullet belong to the “pybullet_envs” module, so we have to include the
following import at the beginning of our Python implementation (in the “Importing the libraries”
code section):

import pybullet_envs
And now, time to have fun!
