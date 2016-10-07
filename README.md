# Item Catalog

This application was developed for the **Udacity**  _Full Stack Web 
Developer_ Nanodegree.  The Item Catalog is designed as a mock store  
inventory catalog, that can be modified by multiple users authenticating 
via Google or Facebook APIs.  Logged in users can add, edit, and delete 
categories as well as the products within them.  JSON endpoints also 
exist for easy third party integration.

## Software Requirements:

- [Git](https://git-scm.com/) for ease-to-use of command line.
- [Vagrant](https://www.vagrantup.com/) necessary for environment.
 
## Installation Instructions:

1. Install [Git](https://git-scm.com/).
2. Install [Vagrant](https://www.vagrantup.com/).  A restart of your computer
may be required.
3. Create a new folder in desired location for this project.
4. In this new folder, open a git bash shell by right clicking and selecting 
`Git Bash Here`.
5. Enter into the shell: `git clone https://github.com/Population96/UdacityCatalogProject.git`
6. Type the command `cd catalog` to change directory to the base
of the project.
7. Enter `vagrant up` in the shell to tell vagrant to initiate the environment 
setup.  Vagrant will install VirtualBox and the necessary environment.
8. Once completed, enter `vagrant ssh` to login to the virtual machine.
9. The prompt will change and you are now in the virtual environment.  Enter `cd ../../vagrant/catalog` in this new prompt to reach the program's files.
10. Run the python web server application with `python application.py`
11. Open a browser and navigate to `http://localhost:5000/`.
