# KStrike
Stand-alone parser for User Access Logging from Server 2012 and newer systems

# [BriMor Labs](https://www.brimorlabs.com)

## KStrike

This script parse data from the User Access Logging files contained on Windows Server 2012 and newer systems, found under the path "\Windows\System32\Logfiles\SUM". For documentation on these files, please visit the official documentation page at https://docs.microsoft.com/en-us/windows-server/administration/user-access-logging/manage-user-access-logging


Usage example:
KStrike.py SYSTEMNAME\Current.mdb > Current_mdb.txt

This script has been tested on the following systems:
- Windows
- macOS
- \*nix

REQUIREMENTS:

- libesedb (pyesedb) (https://github.com/libyal/libesedb)
- Python2 
- May require some additional Perl modules
