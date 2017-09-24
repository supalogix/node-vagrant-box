Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/trusty64"

  #
  # Run Ansible from the Vagrant Host
  #
  config.vm.provision "ansible" do |ansible|
    ansible.playbook = "playbook.yml"
  end

  config.vm.provider "virtualbox" do |v|
  	 v.memory = 2048
  	 v.cpus = 2
  end
end
