`Gitify restore`

Added in 0.7. Restores your MySQL database from a backup created with `Gitify backup`. Specify "last" to use the most recent backup. 

````
Usage:
 restore [file]

Arguments:
 file                  The file name of the backup to restore; if left empty you will be provided a list of available backups. Specify "last" to use the last backup, based on the file modification time.

Options:
 --help (-h)           Display this help message.
 --verbose (-v|vv|vvv) Increase the verbosity of messages: 1 for normal output, 2 for more verbose output and 3 for debug.
 --version (-V)        Display the Gitify version.

````