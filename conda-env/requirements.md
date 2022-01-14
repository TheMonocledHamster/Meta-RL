## Python Version
3.6 / 3.7
    
### Dependency issuesaila
 Box2D:
  version: 2.3.10
  Not available from conda repo
 gym:
  version: 0.17
  Not available from conda repo
 mujoco-py: 
  version: Depends on MuJoCo installation
  Not available from conda repo
 tensorflow + tensorboard, etc:
  version: 1.14
  Availabe version is tf-2.5, might break the code, will test that locally to confirm
 numpy:
  version: 1.18
  Using 1.19 or later will require minor modifications to the code, will do that if necessary
 scipy:
  version: 1.4.1
  Later versions of Scipy do not work with the necessary Python versions.