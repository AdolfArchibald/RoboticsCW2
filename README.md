# RoboticsCW2

In this Repo, there is the Submission Jupyter Notebook File as well as the file used used to generate the AI model that is used in the project.

This file runs within the Yahboom environment, and it is assumed the person who intends to make use of this also has access to the Yahboom environment.

As such, no pip installs are required, and it can just be used as is. It is important to drop the generated AI model into the *SAME ROOT DIRECTORY* so that it can be loaded and used.

Should you wish to generate the AI model in a different environment, make use of the following pip installs:
`pip install tensorflow==2.13.1
pip install matplotlib
pip install PIL`

It is very important that should you wish to train the AI model in a different environment, Python version *3.8* MUST be used as well as tensorflow version *2.13.1*
You will recieve a mismatch error if you do not make sure to use the correct versions.
