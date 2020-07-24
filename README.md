# TASK-1: Integration of GitHub and Jenkins

## JOB1- testing_env

If Developer pushes to dev branch then Jenkins will fetch from dev branch and deploy on dev-docker environment.


![alt text](https://github.com/ShivangiSharma77/GitHub_Jenkins-Integration/blob/master/Jenkins_SS/testing_env1.png?raw=true)

![alt text](https://github.com/ShivangiSharma77/GitHub_Jenkins-Integration/blob/master/Jenkins_SS/testing_env2.png?raw=true)

![alt text](https://github.com/ShivangiSharma77/GitHub_Jenkins-Integration/blob/master/Jenkins_SS/testing_env3.png?raw=true)

![alt text](https://github.com/ShivangiSharma77/GitHub_Jenkins-Integration/blob/master/Jenkins_SS/testing_env4.png?raw=true)

![alt text](https://github.com/ShivangiSharma77/GitHub_Jenkins-Integration/blob/master/Jenkins_SS/merging_env.png?raw=true)

![alt text](https://github.com/ShivangiSharma77/GitHub_Jenkins-Integration/blob/master/Jenkins_SS/merging_env2.png?raw=true)

![alt text](https://github.com/ShivangiSharma77/GitHub_Jenkins-Integration/blob/master/Jenkins_SS/production_env1.png?raw=true)

![alt text](https://github.com/ShivangiSharma77/GitHub_Jenkins-Integration/blob/master/Jenkins_SS/production_env2.png?raw=true)

![alt text](https://github.com/ShivangiSharma77/GitHub_Jenkins-Integration/blob/master/Jenkins_SS/production_env3.png?raw=true)

![alt text](https://github.com/ShivangiSharma77/GitHub_Jenkins-Integration/blob/master/Jenkins_SS/production_env4.png?raw=true)

![alt text](https://github.com/ShivangiSharma77/GitHub_Jenkins-Integration/blob/master/Jenkins_SS/production_output.png?raw=true)

![alt text](https://github.com/ShivangiSharma77/GitHub_Jenkins-Integration/blob/master/Jenkins_SS/pipeline1.png?raw=true)

![alt text](https://github.com/ShivangiSharma77/GitHub_Jenkins-Integration/blob/master/Jenkins_SS/pipeline2.png?raw=true)


JOB#2
If Developer push to master branch then Jenkins will fetch from master and deploy on master-docke environment.
both dev-docker and master-docker environment are on different docker containers.

JOB#3
Manually the QA team will check (test) for the website running in dev-docker environment. If it is running fine then Jenkins will merge the dev branch to master branch and trigger #job 2

Created a Build Pipeline.
