# Super Mario Bros DQN

The goal of this project is to create a DQN (Deep Q-Learning Neural Network) in order to play Super Mario Bros. Everything is available in the `SMB-DQN.ipynb` notebook.

We tested several environment enhancement as well as several architectures for our models, in order to make our agent able to go the furthest in the first level of Super Mario Bros.

## Setting up the repository

### Creating a virtual environment

After cloning the repository, it is highly recommended to install a virtual environment (such as virtualenv) or Anaconda to isolate the dependencies of this project with other system dependencies.

To install virtualenv, simply run:

```
pip install virtualenv
```

Once installed, a new virtual environment can be created by running:

```
virtualenv env
```

This will create a virtual environment in the env directory in the current working directory. To change the location and/or name of the environment directory, change env to the desired path in the command above.

To enter the virtual environment, run:

```
source env/bin/activate
```

You should see (env) at the beginning of the terminal prompt, indicating the environment is active. Again, replace env with your desired directory name.

To get out of the environment, simply run:

```
deactivate
```

### Installing Dependencies

While the virtual environment is active, install the required dependencies by running:

```
pip -r requirements.txt
```

This will install all of the dependencies at specific versions to ensure they are compatible with one another.

### Launch Jupyter Lab

When the dependencies are installed, you can now launch Jupyter Lab to explore the notebook:

```
jupyter lab
```

And it should normally open a window in your browser, or you can follow the link given by the terminal.

## Results

![](test/world-1-1.gif)
