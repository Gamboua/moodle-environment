Vagrant::Config.run do |config|
    # # MAQUINA DATABASE
    # config.vm.define "database" do |app|
    #     app.vm.box = "debian/jessie64"
    #     app.vm.network "hostonly", "192.168.33.11"
    #     app.vm.provision "ansible" do |ansible|
    #         ansible.playbook = "database.yml"
    #     end
    # end
    # # MAQUINA MASTER
    # config.vm.define "master" do |app|
    #     app.vm.box = "debian/jessie64"
    #     app.vm.network "hostonly", "192.168.33.10"
    #     app.vm.provision "ansible" do |ansible|
    #         ansible.playbook = "master.yml"
    #     end
    # end
    # MAQUINA MANAGER
    config.vm.define "manager" do |app|
        app.vm.box = "debian/jessie64"
        app.vm.network "hostonly", "192.168.33.12"
        # app.vm.provision "ansible" do |ansible|
        #     ansible.playbook = "manager.yml"
        # end
    end
end
