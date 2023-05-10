Vagrant.configure("2") do |config|
  config.vm.box = "generic/ubuntu1804"
  config.vm.hostname = "app1"
  config.vm.network :public_network, ip: "192.168.1.98"
  config.vm.box_download_insecure=true

# Fournisseur
    config.vm.provider "virtualbox" do |v|
     # v.gui = true
      v.memory = 1024
      v.cpus = 1
    end
end
