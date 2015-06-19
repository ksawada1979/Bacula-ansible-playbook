Vagrant.configure(2) do |config|
  config.vm.define "bacula" do |node|
        node.vm.box = "chef/centos-6.6"
        node.vm.hostname = "bacula"
        node.vm.network :public_network, ip: "192.168.0.162"
  end
end
