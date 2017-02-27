## phpminibrow

## Installation

requires a working folder with php.
DOWNLOAD PHP - http://php.net/downloads.php

## Usage

Phpminibro.exe only works if a php folder in the same working directory or point to an existing php folder in the minibro.ini.

The minibro.ini file allows you to write the path to any php folder that exists on your computer.

The minibro.ini file allows you to write the port number to any available port equal to or greater than 80.

phpminibro.exe will select an unused port if a selected port is unavailable allowing multiple application occurrences from individual folders.

phpminibro requires php version 5.4.0 or greater for the CLI SAPI which provides a built-in web server.

Check out php.net for additional information on the built-in server @ http://php.net/manual/en/features.commandline.webserver.php

Required Folder Structure
[Your folder "what ever you want to call it" (includes phpminibro.exe, minibro.ini, and index.php) ]  
├──phpminibro.exe  
├──index.php  
├──minibro.ini : (phppath=.\php\ -AND- phpport=80)  
├──[PHP 5.4 or greater ]  
├──[CUSTOM APPLICATION DEVELOPMENT FOLDER]  
Once you have a working php directory you can point to any other folders in your root from the index.php file.

If phpinfo fails to load, this typically is due to the extensions_dir not pointing correctly in php.ini. ie; extension_dir = ".\ext"

Tested fine on win7 and win10 and also works on a thumb drive

## Contributing

use it kindly & give feedback.

## History

phpminibro was developed in visual studio c# as a utility to provide an easy way to work on multiple web projects at the same time without the need of a full xampp or wampp install.

## Credits

© 2017 ephernet technologies


## License

GNU General Public License
