# Telia Bruteforcer

![Screenshot](.previews/telia-bruteforcer.gif)
![Screenshot](.previews/telia_bruteforcer_howto.gif)

This is a bruteforce tool for hunting rbi files.

This tool should work for all other internet providers that hosting rbi files for technicolor routers

## How To Getting Started:

     git clone git://github.com/wuseman/telia-bruteforcer.git
     cd telia-bruteforcer

     Open telia-bruteforcer.sh, change the field below:
 
            board="VDNT-O" 
            firmware="17.2.0405-1901068-20201215160859"
            server_ssl=false
            server_ip=131.116.22.230
            file_format="rbi"

     When you have edited the file, run the script as below:

         sh ./telia-bruteforcer.sh -d -p /tmp 

              -d|--download      | Download firmwares
              -p|--path          | Path to store firmware files


## Notice

     Read the notice header inside telia-bruteforcer.sh before before you are using this script

## Changelog

[Versions changelog](CHANGELOG.md).

## Authors:

* **wuseman <wuseman@nr1.nu\>**

## License

This project is licensed under the GNU General Public License v3.0 - see the [LICENSE.md](LICENSE.md) file for details

# End
