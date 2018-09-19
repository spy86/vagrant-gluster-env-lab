# -*- mode: ruby -*-
# vi: set ft=ruby :


Vagrant.configure(2) do |config|

  config.vm.define "gluster-n01" do |ctl|
    ctl.vm.box = "ubuntu/trusty64"
    ctl.vm.hostname = "gluster-n01"
    ctl.vm.network "private_network", ip: "192.168.57.2"
    ctl.vm.provider "virtualbox" do |vb|
      vb.memory = 1024
    end
  end

  config.vm.define "gluster-n02" do |ctl|
    ctl.vm.box = "ubuntu/trusty64"
    ctl.vm.hostname = "gluster-n02"
    ctl.vm.network "private_network", ip: "192.168.57.3"
    ctl.vm.provider "virtualbox" do |vb|
      vb.memory = 1024
    end
  end
end
