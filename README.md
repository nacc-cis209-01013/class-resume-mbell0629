# CIS209 Resume Project

## See it in action
Assuming Hugo is already installed, you just need to clone the Github repository and run the Hugo server

    $ git clone https://github.com/nacc-cis209-01013/cis209-resume 
    $ git submodule init
    $ git submodule update
    
    $ hugo server

Then browse to https://localhost:1313 to see the demo site.

## Make changes
This Hugo template is generated using variables assigned in the `config.yaml` file. When you save changes to the file and Hugo server is still running, Hugo will rebuild the public files. If Hugo is not still running, you can rebuild the files with the command

    $ hugo -D