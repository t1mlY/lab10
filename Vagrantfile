# -*- mode: ruby -*-
# vi: set ft=ruby :
Vagrant.configure("2") do |config|
  config.vm.box_check_update = false
  config.vm.hostname = "testing"  
  config.vm.box = "hashicorp/precise64"
  config.vm.provider "virtualbox" do |vb|
     vb.gui = false
     vb.memory = "1024"
  end
end
