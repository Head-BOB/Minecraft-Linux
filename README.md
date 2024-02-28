# Minecraft-Linux 
## 💡 Helpful Linux commands for setting up Minecraft Server on Linux



### Update/Upgrade System OS & Security:
```
sudo apt update && sudo apt -y upgrade
```


### Check Java Version / Install Java:
> [!NOTE] 
> Replace openjdk-16-jre with your java version

```
java -version
```
```
sudo apt install openjdk-16-jre 
```




### Create Minecraft Folder/Directory & Change Directory Into Folder:

> [!NOTE]
> Name as you like


```
mkdir minecraft-1.20
``` 


```
cd minecraft-1.20
```



### Pull File(s) From WorldWideWeb:

> [!WARNING]
> Make sure you have the link to the correct version


```
wget https://api.papermc.io/v2/projects/paper/versions/1.20.4/builds/436/downloads/paper-1.20.4-436.jar
```




### Create a New Screen / List Screens (ID #) / Remote Screen (ID #) / Close Screen:
```
screen
```
```
screen -ls
```
```
screen -r
```
```
CTRL + A | CTRL + D
```




### Run Minecraft Jar File, Replace Ram Size as Needed:

> [!NOTE]
> Replace paper jar with yours

```
java -Xms4G -Xmx8G -jar paper-1.20.4-436.jar nogui
```




### Edit File(s), using Nano filename.extension:
```
nano eula.txt
```
```
nano server.properties
```



> [!IMPORTANT]
> Save Nano Files
> CTRL + X
> S (to Overwrite / Save)
> Enter (To Confirm)




### Start Server Again.

> [!NOTE]
> Replace paper jar with yours

```
java -Xms4G -Xmx8G -jar paper-1.20.4-436.jar nogui
```


## Connect Via External IP !!
