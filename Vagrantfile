Vagrant.configure("2") do |config|
  # Configuration du maître
  config.vm.define "master" do |master|
    master.vm.box = "ubuntu/bionic64"
    master.vm.network "private_network", ip: "192.168.50.10"
  end

  # Configuration du nœud 1
  config.vm.define "node1" do |node|
    node.vm.box = "ubuntu/bionic64"
    node.vm.network "private_network", ip: "192.168.50.11"
  end

  # Configuration du nœud 2
  config.vm.define "node2" do |node|
    node.vm.box = "ubuntu/bionic64"
    node.vm.network "private_network", ip: "192.168.50.12"
  end
end
