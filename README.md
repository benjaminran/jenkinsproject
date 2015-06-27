# jenkinsproject
A maven project skeleton that I will use in Jenkins to experiment with CI

# notes

### deployment
Jenkins polls the github repository's deploy branch, and for each new commit a full build is performed, with results deployed to my ec2 at http://52.11.81.109/jenkinsproject/. This is done via FTP with the maven deploy plugin using the ubuntu vsftpd daemon.
