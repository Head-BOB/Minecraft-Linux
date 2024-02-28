# Minecraft-Linux
</br>

## 💡 Helpful Linux commands for setting up Minecraft Server on Linux
</br>
</br>

- ###  Update/Upgrade System OS & Security:
```
sudo apt update && sudo apt -y upgrade
```
</br>
</br>

- ### Check Java Version / Install Java:

```
java -version
```
```
sudo apt install openjdk-16-jre 
```
> [!NOTE] 
> Replace openjdk-16-jre with your java version
</br>
</br>
</br>

- ### Create Minecraft Folder/Directory & Change Directory Into Folder:

```
mkdir minecraft-1.20
``` 

```
cd minecraft-1.20
```
> [!NOTE]
> Name as you like
</br>
</br>
</br>

- ### Pull File(s) From WorldWideWeb:
</br>



```
wget https://api.papermc.io/v2/projects/paper/versions/1.20.4/builds/436/downloads/paper-1.20.4-436.jar
```
> [!WARNING]
> Make sure you have the link to the correct version
</br>
</br>
</br>

- ### Create a New Screen / List Screens (ID #) / Remote Screen (ID #) / Close Screen:
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
</br>
</br>
</br>

- ### Run Minecraft Jar File, Replace Ram Size as Needed:



```
java -Xms4G -Xmx8G -jar paper-1.20.4-436.jar nogui
```

> [!NOTE]
> Replace paper jar with yours
</br>
</br>
</br>

- ### Edit File(s), using Nano filename.extension:
```
nano eula.txt
```
```
nano server.properties
```
</br>
</br>
</br>

> [!IMPORTANT]
> Save Nano Files
> CTRL + X
>  S (to Overwrite / Save)
> Enter (To Confirm)
</br>
</br>
</br>

- ### Start Server Again.


```
java -Xms4G -Xmx8G -jar paper-1.20.4-436.jar nogui
```

> [!NOTE]
> Replace paper jar with yours
</br>
</br>

## Connect Via External IP !!
