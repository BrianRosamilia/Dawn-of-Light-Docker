# Dawn-of-Light-Docker

MySQL docker container for [Dawn of Light DAOC Server](http://www.dolserver.net/)

## Everything necessary for MySQL database backing a Dawn of Light Server

* docker.bat (windows) & dockerfile.sh (linux) Runs your MySQL Instance on port 3306 (run docker-machine ip to see the ip)
* single_file.sql the latest version of the Dawn of Light database

## Misc Commands

* `.\DOLLoader "D:\Program Files (x86)\Electronic Arts\Dark Age of Camelot\game.dll" 127.0.0.1 10300 1 account pass`

* `update Account set privlevel = 3` (make yourself an admin)

## Misc Links

* [Dawn of Light server on Github](https://github.com/Dawn-of-Light/DOLSharp)
* [Devart Db Forge (To run single_file.sql against your container)](https://www.devart.com/dbforge/mysql/studio/)