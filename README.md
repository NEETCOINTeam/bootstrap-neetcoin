# bootstrap-neetcoin
This is the NEETCOIN Wallet Bootstrap-file for local synchronization.  
This file is compressed and has a file name indicating the date of update.

## How to
When using, it need to __uncompress__ and __copy__ to the correct place with the correct file name.  
This copy works needs to be done in the state where the wallet is not in active(no working). 

* The correct filename is 'bootstrap.dat'.
* The correct place(PATH) to be copied is the root directory where the executable file(.exe) of the wallet is located.  
 
After copy completed, start up wallet exe.  
Until the file date of update, synchronization from localfile'bootstrap.dat' will begin.  

## Note
* Even if you quit Wallet exe on the way, synchronization will start from the continuation point though, it is not recommended. If possible, it is necessary to finish as the end point. So please do this work when your device has time.  
* Synchronization is until the update date when Bootstrap was created. In order to bring it up to date, so need a net sync after that.  
* After synchronization is all completed, you can be deleted 'bootstrap.dat'.

