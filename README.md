# archived

ready to use copyparty conf & compose

## copyparty ?

[link here](https://github.com/9001/copyparty)

portable file server with:
- web based file sharing
- media streaming
- searching
- easy mobile friendly
- easy to host

## how to deploy?

i generally use [coolify](https://github.com/coollabsio/coolify) for all my projects to host.
it's free and easy to use.
it has docker integrated (it's not necessary tho!)

once you got coolify installed do this:

1. fork this repo privately
   make the changes you want/need to your conf & compose file.
       for compose: change the source of docker mount
       for configs: change the password & my username; + other changes you'd want (such as special folders etc.)
1. on coolify; create a new resource & select github app (private repo)
1. select your forked repo & load the yaml file
1. click the following on coolify (under general): 
    <img width="967" height="289" alt="image" src="https://github.com/user-attachments/assets/f8a841e1-715a-4f99-855a-ce9d0b1382d8" />
    absolutely make sure THIS is on!!!!!!!!!!!!!!!!!!!
1. set your domain / subdomain for the application (make sure the dns already resolves .. check your nameserver)
1. deploy!
