jekyll-vagrant
==============

Environment for developing jekyll projects locally

## Setup
1. Make sure Vagrant and your favorite vitual machine are installed.
2. Clone this repository
3. Open command prompt to location of the Vagrantfile and run ```vagrant up```
4. Jekyll and all it's dependencies are installed!

## Existing Jekyll Projects
1. Copy the projects folder to the folder that contains the vagrantfile.  
2. Open a command prompt to location of the Vagrantfile and run ```vagrant ssh```
3. Once on the VM prompt ```cd /vagrant/<YourProjectFolder>```
4. Start the jekyll server ```jekyll serve --force_polling``` (force polling is required with vagrant because of share)

## New Jekyll Projects
1.  Open a command prompt to location of the Vagrantfile and run ```vagrant ssh```
2.  Once on the VM prompt ```cd /vagrant```
3.  Create new site with ```jekyll new <sitename>```
4.  Start the jekyll server ```jekyll serve --force_polling``` (force polling is required with vagrant because of share)
