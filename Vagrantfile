
Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/xenial64"
  config.vm.network "private_network", ip: "192.168.30.60"
  config.vm.network "forwarded_port", guest: "9000", host: "9000"
  config.vm.provision "shell", path: "scripts/provisioner.sh", privileged: false

end
