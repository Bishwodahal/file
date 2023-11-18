# File.exe  in c++

Simple command line tool for playing with files!
As windows doesn't provide good tool So this will allow you to use file 

## file
  Place the file.exe to any place 
  I recommend to save files in `C:\Custom command`
  
  Add the path  to Path Variable (If you don't know Google It)
  Now open your cmd and enter

  ```powershell
  file --v
  ```
  This will return you the version of file

  ---

## Commands Summary

Commands | Description
---      | --- |
file create | Create file |
file open | Open file |
file size | Display size of file |
file insert | Insert content into file |
file rename | Rename the file |
file delete | Delete the file |

## Commands with Description

### `file create *.*`

This will create file in the current directory.  You can create as many files as you want.


### Arguments:

 `-b` : It means with boilerplate. It has support to some commonly used extensions (11 boiler plates)

```powershell
    file create a.cpp hello.vue
```
 

 
### `file open *.*`

This will open file in the current directory.  You can open as many files as you want in same command.

```powershell
    file open a.cpp hello.vue
```

### `file size *.*`

This will create file in the current directory.  You can create as many files as you want.


### Arguments:

 `-b` : In Bytes

 `-kb` : In Kilo Bytes

 `-mb` : In Mega Bytes

 `-gb` : In Giga Bytes


```powershell
    file size a.cpp  hello.exe
```

 ### `file insert *.*`

This will allow you to insert texts in the file. 
If file is not present Then It will prompt you to create or not

Press CTRL + Z and then Enter to close the file

```powershell
    file insert a.cpp hello.vue
```

 ### `file rename *.*`

As the name suggests you can rename files using this command.



```bash
    file rename oldfile.cpp newfile.cpp
```


### `file delete *.*`

This will delete file in the current directory. 
Any no. of parameters are allowed

```powershell
    file delete a.cpp 
```
 
 

