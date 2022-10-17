# Apache HTTP Server 2.4 CIS Benchmark Script
Apache HTTP Server 2.4 CIS Benchmarks Automation Script

This would run mostly all the audit points specified in the Official CIS Benchmark PDF.

Simply run the bash script

NOTE: This will only give the output of the audit points. Manual check of the outputs needs to be done in order to check if it is compliant or not by following the Benchmarks PDF

## More Troubleshooting
The script should be put in the same directory with the apache folder, by default should be `/etc/apache2`  
If you are facing any error while running the SHELL script, run the following command:
```
sed -i -e 's/\r$//' "Apache HTTP Server 2.4.sh"
```
When you are successfully running the script, it will be prompting for your `Configuration File` and you can input the absolute path of your apache configuration file, for example if you are running apache2.conf, the following location will be the default location:
```
/etc/apache2/apache2.conf
```
