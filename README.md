# Multi Machine vagrant - Ansible Playbook

## Objective:
- Multivagrant machine provisioned with ansible instead of bash script 

## Usage
- clone the repo

- On git bash enter the following commands:

    - ```vagrant up```
    - ```vagrant ssh```
    - check your location - make sure you are in ```/app```. If not, write the following commands:
      - ```cd ..``` --> ensure you're in the location home
      - ```cd ubuntu```
      - ```cd app```
      - Once you're in the right path write, ```npm install```
      - ```npm start```
- You should attain the following output: ```Your app is ready and listening on port 3000```
- Now, you should be able to run the app from the url 'development.local:3000'
