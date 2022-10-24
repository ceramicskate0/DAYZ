# DAYZ

Map: https://dayz.ginfo.gg
Types Changer: https://dzsa.tools/

**Change** ``events.xml`` ``<active>1<active/>``

 **to**
 
 ``<active>0<active/>``

#Wipe Server (Not Player) (economy.xml):
 ```   
 <?xml version="1.0" encoding="UTF-8" standalone="yes"?>
    <economy>
        <dynamic init="0" load="0" respawn="0" save="0"/>
        <animals init="0" load="0" respawn="0" save="0"/>
        <zombies init="0" load="0" respawn="0" save="0"/>
        <vehicles init="0" load="0" respawn="0" save="0"/>
        <randoms init="0" load="0" respawn="0" save="0"/>
        <custom init="0" load="0" respawn="0" save="0"/>
        <building init="0" load="0" respawn="0" save="0"/>
        <player init="1" load="1" respawn="1" save="1"/>
    </economy>
```

#SetBack Server (economy.xml):
 ```
<?xml version="1.0" encoding="UTF-8" standalone="yes"?>
<economy>
    <dynamic init="1" load="1" respawn="1" save="1"/>
    <animals init="1" load="0" respawn="1" save="0"/>
    <zombies init="1" load="0" respawn="1" save="0"/>
    <vehicles init="1" load="1" respawn="1" save="1"/>
    <randoms init="0" load="0" respawn="1" save="0"/>
    <custom init="0" load="0" respawn="0" save="0"/>
    <building init="1" load="1" respawn="0" save="1"/>
    <player init="1" load="1" respawn="1" save="1"/>
</economy>

 ```
