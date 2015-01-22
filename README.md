jenkins-swarm-slave
=========

Simple role to install the Swarm Slave from [Jenkins Swarm Slave Plugin](https://wiki.jenkins-ci.org/display/JENKINS/Swarm+Plugin).


Requirements
------------

None

Role Variables
--------------

- jenkins_url: url to the jenkins master
- jenkins_username: username for the slave to auth
- jenkins_password: password for the slave to auth
- swarm_slave_user: user for running the swarm slave service
- swarm_slave_version: version of the swarm slave plugin


Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
      - { role: kellyp.jenkins-swarm-slave, jenkins_url: 'http://jenkins.vagrant.dev:8080/', jenkins_username: 'jenkins', jenkins_password: 'jenkins' }

License
-------
TBD


Author Information
------------------

Github: [kellyp](http://github.com/kellyp)
