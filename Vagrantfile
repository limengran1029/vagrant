Vagrant.configure("2") do |config|
	config.vm.box = "generic/ubuntu1804"
	config.vm.network "private_network", ip:"IPADRESS"

#set share folder
	config.vm.synced_folder "~/Desktop/share", "/home/meli/vagrant/sharedfolder"

#config shell
	config.vm.provision "shell", inline: <<-SHELL
	CONFIGFILE
	SHELL

end
