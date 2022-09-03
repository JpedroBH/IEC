Vagrant.configure("2") do |config|
  config.vm.define "DevOps" do |svr|
      svr.vm.box = "centos/7"
          svr.vm.provider "virtualbox" do |vb|
              vb.name = "DevOps01"
              vb.memory = 512
              vb.cpus = 1
          end
  end

  config.vm.define "DevOps02" do |svr|
      svr.vm.box = "ubuntu/focal64"
        svr.vm.provider "virtualbox" do |vb|
            vb.name = "DevOps02"
            vb.memory = 1024
            vb.cpus = 1
        end
  end
end