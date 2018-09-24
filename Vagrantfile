# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|

	config.vm.define "oml-asterisk" do |app|
	app.vm.box = "centos-VAGRANTSLASH-7"
	app.vm.hostname = "oml-asterisk.example.com"
	app.vm.network "public_network", ip: "192.168.95.44"

	end

	config.vm.define "oml-kamailio" do |app|
	app.vm.box = "debian/jessie64"
	app.vm.hostname = "oml-kamailio.example.com"
	app.vm.network "public_network", ip: "192.168.95.45"
	end

	config.vm.define "oml-wd" do |app|
	app.vm.box = "centos-VAGRANTSLASH-7"
	app.vm.hostname = "oml-wd.example.com"
	app.vm.network "public_network", ip: "192.168.95.46"
	end

end
