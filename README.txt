
This is a project that attempts to utilise two Docker services to expand accessibility
and to implement CI/CD in Docker container deployment.

The first is Portainer, a graphical interface service for managing docker containers
that allows a more visual approach to managing containers and allows easier access to
the processes inside of the containers. It is similar to the AWS management console
that is it is easier to keep track of all the resources in the Docker resource network
than by examining it through CLI.
https://www.portainer.io/

The second is Watchtower, a service which monitors existing containers and their images
and should automatically start a new container if the image it is based on is updated.
Note: as of writing it is unsure that Watchdog is working in this project setup as
there is no indication within the CLI or Portainer that it is operating as intended.
The code will be included for Watchtower but it may not be working.
https://containrrr.github.io/watchtower/

How to use:
This project requires a machine with Vagrant installed. Simply download this repo
and "vagrant up" inside the folder. Once it is finished you should be able to access
Portainer with the URL http://192.168.30.60:9000
