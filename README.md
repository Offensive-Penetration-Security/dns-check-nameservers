# dns-check-nameservers #

Simple bash script to get nameservers of a list of domains

This script is for checking if customer domains on our nameservers still exist and have our nameservers assigned to keep our nameservers clean.

## Usage: ##

./dns-check-nameservers.sh &lt;file with list of domains&gt;

The file with all domain records has to contain one domain each line. F.ex.:  
example1.com  
example2.com  
example3.com

## License ##
GPLv3, see LICENCE file.
