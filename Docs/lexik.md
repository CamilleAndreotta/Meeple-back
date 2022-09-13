
  
student@nedaudchristophe-server:~$ cd var/www/html/
-bash: cd: var/www/html/: No such file or directory
student@nedaudchristophe-server:~$ cd /var/www/html/
student@nedaudchristophe-server:/var/www/html$ ls
adminer  meeple  oflix  site-demo-deploiement.fr
student@nedaudchristophe-server:/var/www/html$ cd meeple
student@nedaudchristophe-server:/var/www/html/meeple$ bin/console lexik:jwt:generate-keypair
-bash: bin/console: No such file or directory
student@nedaudchristophe-server:/var/www/html/meeple$ ls
current  releases  shared
student@nedaudchristophe-server:/var/www/html/meeple$ cd current
student@nedaudchristophe-server:/var/www/html/meeple/current$ ls
bin  composer.json  composer.lock  config  deploy.php  Docs  migrations  phpunit.xml.dist  public  README.md  REVISION  src  symfony.lock  templates  tests  translations  var  vendor
student@nedaudchristophe-server:/var/www/html/meeple/current$ bin/console lexik:jwt:generate-keypair

                                                                                                                        
 [OK] Done!                                                                                                             
                                                                                                                        

student@nedaudchristophe-server:/var/www/html/meeple/current$ git config --global user.name "NedaudChristophe"