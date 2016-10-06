Vagrant::Config.run do |config|
    config.vm.define "master" do |app|
        app.vm.box = "debian/jessie64"
        app.vm.network "hostonly", "192.168.33.10"
        # con-fig.vm.provision "ansible" do |ansible|
        #     ansible.playbook = "master.yml"
        # end
    end
end
