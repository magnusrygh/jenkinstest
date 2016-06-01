Vagrant.configure(2) do |config|
  config.vm.box = "steny/jenkins_artifactory_lab"
  config.vm.network :forwarded_port, guest: 8080, host: 9090, host_ip: "127.0.0.1"
end
