Vagrant.configure(2) do |config|
  
  config.vm.box = "precise32"
  config.vm.provider "virtualbox" do |v|
  	v.memory = 3072
  	v.cpus = 3
  end


  config.vm.define :db do |db_config|
	db_config.vm.network :private_network, :ip => "192.168.33.10"
  end

  config.vm.define :web do |web_config|
	web_config.vm.network :private_network, :ip => "192.168.32.12"
  end

  config.vm.define :monitor do |monitor_config|
	monitor_config.vm.network :private_network, :ip => "192.168.33.14"
  end

  config.vm.define :build do |build_config|
  	build_config.vm.network :private_network, :ip => "192.168.33.20"
  end

 
end
