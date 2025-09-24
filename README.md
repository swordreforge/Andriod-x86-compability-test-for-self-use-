### Andriod-x86-compability-test-for-self-use
Use as kali 2025.1 relies on havily on its new debian kenel,many android simulators just cannot run the container or machine,so I collect some refer for self use
#### The easist way 
To use the sfs that andriod x86 official provided:
1.download file houdini9_y.sfs or houdini9_x.sfs or any other version,
2.put them into ``/data/media/0/arm``
3.execute command (x86 is already with root,make sure your /system is writable)
Termux or MT-simulator Terminal or so on:
````Termux or MT-simulator Terminal or so on
su root #use as root
enable_nativebridge #The file is already in /system/bin 
````
For more info please follow on this website:http://juniorprincewang.github.io/2023/12/11/androidx86-libhoudini/
#### The custome way to enable the compabilities:
