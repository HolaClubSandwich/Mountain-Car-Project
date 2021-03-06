Description:
  This is an implementation of an Expected Sarsa Control algorithm, and tile coding function approximation. Our goal is for the agent to reach the top of the mountain in as few steps as possible.


Link to Github Page:
  https://github.com/NicoCarpe/Mountain-Car-Project.git


Collaborators:

  Nicolas Carpenter, ID: 1533367
  Jun Li, ID: 1560231


File Descriptions:

  MountainCarEnvironment.py - The file that creates the environment, using the environment.py file, that is used in the Mountain Car Experiment

  ExpectedSarsaAgent.py - The file that creates the Expected Sarsa Agent, using the agent.py, tiles3.py, and utils.py files, that is used in the Mountain Car Experiment

  Experiment.py - Uses the MountainCarEnvironment.py, ExpectedSarsaAgent.py, and rl_glue.py files to run the Mountain Car Experiment

  agent.py - Base agent class used to create the Expected Sarsa Agent

  environment.py - Base environment class used to create the Mountain Car Environment

  utils.py - The argmax function from this file is used in the Expected Sarsa Agent

  rl_glue.py - A library that is used for the running the reinforcement learning experiment

  tiles3.py - A library that is used for tile coding

  Alternate_papameters.png - A picture of the learning curve generated by the alternate parameters

  Default_parameters.png - A picture of the learning curve generated by the default parameters


Alternate Parameter Settings:

  Note: Parameters we changed

  number of tiles = 4
  number of tilings = 32
  alpha = 0.7/(numTilings)
  epsilon = 0.1


Means and Standard Errors:

  Default Parameters:
    mean = -57432.04
    standard error = 55.927116571480774
    number of runs = 50

  Alternate Parameters:
    mean = -32409
    standard error = 71.11823535493552
    number of runs = 50


Command to run:

  In terminal go to the directory where files are stored. Use command "python3 Experiment.py". To obtain the default plot select "1" when prompted, and to obtain the alternate plot select "2" instead.
