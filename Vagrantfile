Vagrant.configure("2") do |config|
  config.vm.box = "centos/7"
    config.vm.provision "shell", inline: <<-SHELL
      sudo yum groups install -y "Server with GUI"
    SHELL
  config.vm.provider "virtualbox" do |v|
    v.gui = true
  end
end
