Vagrant.configure("2") do |config|
  config.vm.box = "centos/8"
  config.vm.box_version = "1905.1"


  config.vm.provision "ansible" do |ansible|
    ansible.limit = "all"
    ansible.playbook = "playbook.yml"
  end
end
