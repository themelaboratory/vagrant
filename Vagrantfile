# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|

    config.vm.box = 'ubuntu164-php72-apache24-ssl'
    # config.vm.box_url =  "file://D:/VirtualBox VMs/vagrant_box/ubuntu164-php72-apache24-ssl.box"
    config.vm.network "private_network", ip: "192.168.33.10"
    config.vm.hostname = "scotchbox"
    config.vm.synced_folder "./project", "/home/project/public_html", :mount_options => ["dmode=777", "fmode=666"]
    
end