# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|

  
  config.vm.box = "erickills/testbed"
  config.vm.box_version = "1"

  # Create a private network, which allows host-only access to the machine
  # using a specific IP.
  # config.vm.network "private_network", ip: "192.168.33.10"

  # Bridged networks make the machine appear as another physical device on
  # your network.
   config.vm.network "public_network"

  config.vm.provider "virtualbox" do |vb|
  #
  #   # Customize the amount of memory on the VM:
     vb.memory = "512"
   end

end
