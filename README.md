# Directory Structure 
![image](https://github.com/joshking1/ansible-project/assets/88409463/3a316ac7-baa3-4432-80fc-5660840a0def)

# This will create the directory structure and the necessary files.

cd /path/to/your/ansible/project
mkdir -p roles/docker/{tasks,handlers,defaults,files,templates,meta}
touch roles/docker/tasks/main.yml
touch roles/docker/handlers/main.yml
touch roles/docker/defaults/main.yml
touch roles/docker/meta/main.yml

# You can also run a list of commands one by one:

cd /path/to/your/ansible/project
mkdir roles
cd roles
mkdir docker
cd docker
mkdir tasks
mkdir handlers
mkdir defaults
mkdir files
mkdir templates
mkdir meta
cd tasks
touch main.yml
cd ..
cd handlers
touch main.yml
cd ..
cd defaults
touch main.yml
cd ..
cd meta
touch main.yml



