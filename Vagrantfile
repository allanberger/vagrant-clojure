# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |config|
  config.vm.box = "bento/ubuntu-16.04"

  config.vm.network "private_network", ip: "10.61.6.31"
  config.vm.hostname = "clojure"

  config.vm.synced_folder "/Users/allanberger/Projects/learning", "/vagrant"

  config.vm.provision "shell", path: "provision.sh"
end
