# Create icons
Place files in ~/.local/share/applications/%APP_NAME%.desktop
## PhpStorm
[Desktop Entry]<br>
Version=1.0<br>
Type=Application<br>
Name=PhpStorm<br>
Icon=/home/dev/bin/PhpStorm-191.7141.52/bin/phpstorm.png<br>
Exec="/home/dev/bin/PhpStorm-191.7141.52/bin/phpstorm.sh" %f<br>
Comment=Develop with pleasure!<br>
Categories=Development;IDE;<br>
Terminal=false<br>
StartupWMClass=jetbrains-phpstorm
## Filezilla
[Desktop Entry]<br>
Version=1.0<br>
Type=Application<br>
Name=Filezilla<br>
Icon=/home/dev/bin/FileZilla3/share/icons/hicolor/32x32/apps/filezilla.png<br>
Exec="/home/dev/bin/FileZilla3/bin/filezilla" %f<br>
Comment=Ftp client<br>
Categories=Development;<br>
Terminal=false
#Docker commands
docker-compose up -d app-auth-service app-emulator app-sms<br>
docker-compose exec app-sms composer reset-database-test<br>
docker-compose exec app-sms bin/console ca:cl --env=test<br>
docker-compose exec app-sms composer test

# Env setup
## Rotate windows on scroll 
gsettings set org.gnome.shell.extensions.dash-to-dock scroll-action 'cycle-windows'
