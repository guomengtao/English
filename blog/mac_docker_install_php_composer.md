lerning book


I try run the Laravel on the Mac by Docker!

I meeted a lot questiong , but now is sucsecce to installed by Composer and PHP8.1 vession!

1. pull the php new version from Docker  hub.docker.com
2. use "PHP" command to intalling the composer not sudo, open the composer copy these 3 command
    php -r "copy('https://install.phpcomposer.com/installer', 'composer-setup.php');"
    php composer-setup.php
    php -r "unlink('composer-setup.php');"
 3. run the mv comand , Do not add the sudo ,just use "mv" comand is curect.
     {sudo} mv composer.phar /usr/local/bin/composer
