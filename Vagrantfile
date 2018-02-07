Vagrant.configure(2) do |config|
  config.vm.box = "ubuntu/xenial64"
  config.vm.provision :shell, path: "vagrant/bootstrap.sh"
  config.vm.network "forwarded_port", guest: 22000, host: 22000
  config.vm.network "forwarded_port", guest: 22001, host: 22001
  config.vm.network "forwarded_port", guest: 22002, host: 22002
  config.vm.network "forwarded_port", guest: 22003, host: 22003
  config.vm.network "forwarded_port", guest: 22004, host: 22004
  config.vm.network "forwarded_port", guest: 22005, host: 22005
  config.vm.network "forwarded_port", guest: 22006, host: 22006
  config.vm.network "forwarded_port", guest: 8080, host: 8080
  config.vm.network "forwarded_port", guest: 8081, host: 8081
  config.vm.network "forwarded_port", guest: 8082, host: 8082
  config.vm.network "forwarded_port", guest: 8083, host: 8083
  config.vm.network "forwarded_port", guest: 8084, host: 8084
  config.vm.network "forwarded_port", guest: 8085, host: 8085
  config.vm.network "forwarded_port", guest: 8086, host: 8086
  config.vm.provider "virtualbox" do |v|
    v.memory = 8192
    v.customize ["modifyvm", "default", "--cpuexecutioncap", "40"]
  end
end
