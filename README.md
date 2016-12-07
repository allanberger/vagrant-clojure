vagrant-clojure
=====================

A repository with a Clojure ready Vagrant Environment.  

**Setup Requirements**  
- VirtualBox 5.1.x (https://www.virtualbox.org/wiki/Downloads)  
- Vagrant 1.9.x (https://www.vagrantup.com/downloads.html)  

**Pre-Installed on the VM**  
- Java Runtime (default-jre)  
- Leiningen (https://raw.githubusercontent.com/technomancy/leiningen/stable/bin/lein)  


Update your [Vagrant Synced Folder](https://www.vagrantup.com/docs/getting-started/synced_folders.html) by updating this line in to your preferred paths `Vagrantfile`:  
`config.vm.synced_folder "/HOST_PROJECT_DIR", "/VM_PROJECT_DIR"` e.g. `config.vm.synced_folder "/Users/yourname/projects", "/vagrant"`


## Booting the virtual machine

Boot the virtual machine using `vagrant up`. Use `vagrant ssh` to access the VM. In the VM you'll be in `/home/vagrant`, navigate to `/vagrant` to access your synced folder as set above.
