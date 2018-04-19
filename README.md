# notebook-server-ubuntu
Our Labs notebook-server-ubuntu for quick setup

script to install jupyter notebook server on base ubuntu server

after successful deployment of ubuntu and logging into the VM execute:

    cd $HOME

    sudo apt-get install -y git-core

    git clone https://github.com/szsmith/notebook-server-ubuntu.git

if static network is required:

    nano ./notebook-server-ubuntu/interfaces

    source ./notebook-server-ubuntu/setup.sh

if connectivity to AZURE Data warehouse is required execute:

    source ./notebook-server-ubuntu/setup_odbc.sh
