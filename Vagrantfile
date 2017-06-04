Vagrant.configure("2") do |config|
  config.vm.define "ansible" do |myconf|
    myconf.vm.box = "centos/7"
    myconf.vm.hostname = "ansible.example.com"
  end

  config.vm.define "centos" do |myconf|
    myconf.vm.box = "centos/7"
    myconf.vm.hostname = "centos.example.com"
  end

  config.vm.define "ubuntu" do |conf|
    conf.vm.box = "yk0/ubuntu-xenial"
    conf.vm.hostname = 'ubuntu.exmample.com'
  end

end
