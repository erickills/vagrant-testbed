# -*- mode: ruby -*-
# vi: set ft=ruby :

# Just my personal minimal testing environment, nothing's special. :)
# Nov. 9, 2021
# by erickills

Vagrant.configure("2") do |config|

  
  config.vm.box = "erickills/testbed"
  config.vm.box_version = "1"

  # config.vm.network "private_network", ip: "192.168.33.10"

  # Bridged networks make the machine appear as another physical device on
  # your network.
   config.vm.network "public_network"

  config.vm.provider "virtualbox" do |vb|
   
     vb.memory = "512"
   end

end
