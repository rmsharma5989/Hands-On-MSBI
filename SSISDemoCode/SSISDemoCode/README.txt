This project is in package deployment model mode and i am using package aocnfiguraiton to define the values dynamically.

To deploy the package i enabled the CreateDeploymentUtility to True and used DeploymentUtility (metadata) file to install the package.

during deployment you will have two options, File system deployment and SQL server deployment.

i used file system deployment and deployed the package on a path, it gave the package file and configuration file at the given path.
using that we can update the config file and setup a SQL job to run this package