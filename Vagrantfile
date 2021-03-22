Vagrant.configure("2") do |config|

  config.vm.box = "mrlesmithjr/bionic64-desktop"
  config.vm.synced_folder ".", "/home/vagrant/lab3"
  config.vm.provision :shell, path: "https://gist.githubusercontent.com/khale/3471497bcaa21d6f8e6da599afe22f5b/raw/82000ac2061743fbbc756a25864596f82e8965e8/gistfile1.txt"

  config.vm.provider "vmware_desktop" do |v|
    v.gui = true
  end

  config.vm.provider "virtualbox" do |v|
    v.gui = true
  end

end
