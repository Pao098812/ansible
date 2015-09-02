# -*- mode: ruby -*-
# vi: set ft=ruby :

VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|

  config.vm.box= "ubuntu12"
  config.vm.box_url= "https://cloud-images.ubuntu.com/vagrant/precise/current/precise-server-cloudimg-i386-vagrant-disk1.box"
  config.vm.network "private_network", ip: "192.168.33.2"
  #config.vm.network "forwarded_port", guest: 80, host: 8080
  config.vm.boot_timeout= 300
  #config.vm.synced_folder "/var/www/project"
  #config.vm.provision "shell", path: "main.yml"
  #config.vm.provision "ansible" do |ansible|
  	#ansible.playbook="main.yml"
  #end
end
