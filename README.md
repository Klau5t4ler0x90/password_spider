# password_spider
The module recursively searches SMB shares for files with potential passwords.

This python script is an additional module for NetExec from Pennyw0rth.
You can speed up your Penetrationtests. Read the files and print the passwords and usernames.

### The module filters all files with the endings: 
* ".cmd" 
* ".bat" 
* ".ps1" 
* ".inf"
* ".info"
* ".psd"

Use this module by downloading the python script and copying it to the appropriate directory.
When the program (nxc/Netexec) is executed, the module is integrated into the list of SMB modules. Check it out with "nxc smb -L"

Path to copy in Kali Linux is: /usr/lib/python3/dist-packages/nxc/modules/

```shell
sudo cp password_spider.py /usr/lib/python3/dist-packages/nxc/modules/password_spider.py
```

Thanks to [Pennyw0rth](https://github.com/Pennyw0rth/NetExec) and the whole team for this great tool.

How it works? [Wiki](https://github.com/Klau5t4ler0x90/password_spider/wiki/password_spider)
