# Private-FairSwap
Experimental Implementation of Private FairSwap

This repository contains a Vagrantfile and a PDF document describing the vagrant box set up and how to run the experiments inside it. Vagrantfiles are used to spin up virtualized environments in a quick and easy way. This varantfile pulls a vagrant box which contains our pFairSwap experimentation environment. The provider is virtualbox. To use the vagrantfile and access our environment you will need to download vagrant and virtualbox from https://www.vagrantup.com/ and virtualbox from https://www.virtualbox.org/wiki/Downloads.

Once these are downloaded, place the Vagrantfile inside a directory you'd like to work from and run "$ vagrant up" command. This will launch the virtual environment. Then you can run "$ vagrant ssh" to open an ssh connection to the virtualized environment.
