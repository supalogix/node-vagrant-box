Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/trusty64"

  #
  # Run Ansible from the Vagrant Host
  #
  config.vm.provision "ansible" do |ansible|
    ansible.playbook = "playbook.yml"
  end
end
