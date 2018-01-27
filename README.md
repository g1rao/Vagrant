# Vagrant
Vagrant is a tool for building and managing virtual machine environments in a single workflow
Vagrant provides easy to configure, reproducible, and portable work environments 
Vagrant provides the easiest and fastest way to create a virtualized environment!
In Vagrant, The Virtual Machines are provisioned on top of VirtualBox, VMware, AWS, or any other provider. 
Then, industry-standard provisioning tools such as shell scripts, Chef, or Puppet, can automatically install and configure software on the virtual machine

With an easy-to-use workflow and focus on automation, Vagrant lowers development environment setup time,increases production parity.

Once you or someone else creates a single Vagrantfile, you just need to vagrant up 
	and everything is installed and configured for you to work. 
	Other members of your team create their development environments from the same configuration,
	so whether you are working on Linux, Mac OS X, or Windows, all your team members are running code in the same environment,
	against the same dependencies, all configured the same way. Say goodbye to "works on my machine" bugs.



Vagrant is not the only tool to manage virtual machines and development environments.

Virtualization software like VirtualBox and VMware come with command line utilities
	for managing the lifecycle of machines on their platform

Many people make use of these utilities to write their own automation. Vagrant actually uses many of these utilities internally

The difference between these CLI tools and Vagrant is that Vagrant builds on top of these utilities in a number of ways
	while still providing a consistent workflow

Vagrant supports multiple synced folder types, multiple provisioners to setup the machine, automatic SSH setup,
	creating HTTP tunnels into your development environment, and more.
	All of these can be configured using a single simple configuration file

The command-line utilities provided by virtualization software often change each version or have subtle bugs with workarounds.
	
Vagrant automatically detects the version, uses the correct flags, and can work around known issues. 
	So if you're using one version of VirtualBox and a co-worker is using a different version, Vagrant will still work consistently.
	
Vagrant will allow you to run a Windows development environment on Mac or Linux, as well.

A primary benefit for Vagrant is a consistent workflow but there are many cases where a pure-Docker workflow does make sense	

Both Vagrant and Docker have a vast library of community-contributed "images" or "boxes" to choose from.

 Synced folders, automatic networking, HTTP tunneling, and more
 
Vagrant is a tool focused for managing development environments and Terraform is a tool for building infrastructure
Vagrant is for development environments. Terraform is for more general infrastructure management.
