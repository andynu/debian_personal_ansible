Vagrant.configure("2") do |config|
  config.vm.box = "debian/buster64"
  config.vm.provision "ansible" do |ansible|
    ansible.playbook = "playbook.yml"
  end
end
