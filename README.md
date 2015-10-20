# Anchor Chain Plug-in for Jenkins

This plugin add links to the side bar of every build.

The side bar links are obtained from a text file, which is part of the project, located in the  working directory. The structure of the file is as follows:

- Each line in file describes one link to be added to the sidebar
- Each line must contain three fields divided by tabs: __name__, __url__, __icon__. One can omit icon field to use default.

AnchorChain complains to console log for any issues.

The file format: 

	name<tab>url<tab>icon

Sample file:

	Sonar	http://sonar.organisation.org	http://docs.sonarqube.org/download/attachments/1448390/SONAR?version=7&modificationDate=1432060800000&api=v2

	
See also:

- [Jenkins Wiki - Anchor Chain Plug-in](https://wiki.jenkins-ci.org/display/JENKINS/AnchorChain+plugin)
