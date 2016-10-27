# SSH

Some useful SSH codes and notes

### How to download a file from server using SSH?
*You can do this with the scp command. scp uses the SSH protocol to copy files across system by extending the syntax of cp.*

#### Copy something from this system to some other system:
```python
scp /path/to/local/file username@hostname:/path/to/remote/file  
```        

#### Copy something from some system to some other system:
```python
scp username1@hostname1:/path/to/file username2@hostname2:/path/to/other/file   
``` 

#### Copy something from another system to this system:
```python
scp username@hostname:/path/to/remote/file /path/to/local/file
``` 

source:http://stackoverflow.com/a/9427762
