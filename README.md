# docker-compose-gitlab-owncloud
An docker compose file for booting gitlab and owncloud with a postsql databas WITH lets encrypt

# To do:
## copy or clone the file 
`git clone https://github.com/martijnvwezel/docker-compose-gitlab-owncloud.git`

## password change 
Change the password of the sql and where the volumens of /srv will be placed.

## lets encrypte changes
Change the email of the lets encrypt keys. Also change the hostnames.

## hostname 
Change the hostname so the ngninx will know which docker the netwerk needs to be connected with.

## run command 
`docker-compose -f docker-compose.yml up -d`


