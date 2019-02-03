# SERVER-PACKS INCLUDES LINGOR-NAPF-SAUERLAND-TAKISTAN

[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_buynowCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=7H2X3TG2RLZHS)



MANY TNKS: TO CHERDENKO,NOVA,OLDMATECHOC for all support during this work. 
TNKS TOO : to SuperSonic,Beta,Wagner and Soldado for give me an space to work on it.

*You can choose whatever of this ones.*
*All of they are Ovepoch*
*Check The mod list and credits file*

**HOW TO INSTALL**

-FOR RUN IN LOCAL MACHINES OR VIRTUAL ONES:

###############################################
```
-1.Create a database called "overpoch2018" with his username: "overpoch2018" and his pass: "overpoch2018". (we gonna use that names cuz is the value for default that i put. You can change it later.)
```

```
-2.A.  Create a fresh server files in C:\overpoch\  
(We gonna use that path cuz its already defined in server files,other way you gonna need edit a lot).
Note that you will need add @DayzOverwatch and @DayZ_Epoch
```
```
-2.B.Do not put @DayZ_Epoch_Server and MPMissions folder provided by epoch. we gonna use our owns.
So basically in this step you jsut need drop all content from your arma2 and arma2oa in one single folder.Download overwacht and dayz_epoch client files.
```

```
-3.A.Now choose the map you gonna use. For example Napf.
```

```
-3.B.Drop @DayZ_Epoch_Server_napf , MPMissions and Keys  folder into C:\overpoch\  (do the same with the .dll).
-Note: if u are choosing lingor drop the folder called "keys-OnlyForLingor" and rename it as: "Keys".-
```

```
-3.C.Drop DZE_Server_Config into C:\
```

```
-4.To start your server go to C:\DZE_Server_Config\ and click over "START_WITH_RESTART.bat" or "start_withoutrestart.bat".-
```

-WE ARE DONE. THE SERVER CAN RUN NOW WITH AN AUTORESTART. CHECK THE CONFIG FILE IF U WANNA KNOW MORE ABOUT THE SERVER

################################################


-FOR RUN IN HOSTS LIKE GTX:
```
1.Download @DayZ_Overwachat into your host and activate it.
```

```
2.Choose the map that you will use: for example Takistan.
```

```
-3.A.Open serverpacks\takistan\@DayZ_Epoch_Server_taki\addons\ and drop dayz_server.pbo into your @DayZ_Epoch_Server\addons\
```

```
-3.B.Open serverpacks\takistan\MPMissions\ and drop DayZ_Epoch_1.Takistan.pbo
```

```
-4.Open from your host your config.cfg 
```
-Find this line: (the name of the line could change according to the map you are currently using) 
```ruby
template = "DayZ_Epoch_11.Chernarus";
```
-Change By:
```ruby
template = "DayZ_Epoch_1.Takistan";
```

-WE ARE DONE. CHECK THE CONFIG FILE IF U WANNA KNOW MORE ABOUT THE SERVER.



**INFISTAR USERS.

-1.Open your AHConfig.sqf
This is my _ALLOWED_Dialogs list.

```ruby
_ALLOWED_Dialogs = _ALLOWED_Dialogs + [2600,2601,4800,9000,81000,88890,20001,20002,20003,20004,20005,20006,55510,55511,55514,55515,55516,55517,55518,55519,555120,118338,118339,571113]; // adding some others from community addons
```

-2.Into _cMenu = [.........];   paste:

```ruby
,"#USER:PlayerActionsMenu","#USER:Housemenu","#USER:HudToggle","#USER:deploy","#USER:GrassToggle","#USER:SETVIEW","#USER:sounds","#USER:color","#USER:write","#USER:dance","#USER:deployweapons","#USER:Server","#USER:players","#USER:MY","#USER:adminevents","#USER:admmenu","#USER:surveillance","#USER:STATICS","#USER:USEFUL","#USER:ACTIONS","#USER:workshopMenu","#USER:xmastree","#USER:questions"
```

-3. Into _dayzActions =[.........];

```ruby
,"s_player_13252_copyToKey",
	"s_player_copyToKey","s_player_claimVehicle",
	"s_player_clothes","s_player_fastgear","s_player_fastgear2","s_player_refugeedoor","s_player_cctv","s_player_camerasys",
    "s_player_officer","s_player_bagg","s_player_TobaccoSell","s_bank_dialog1","s_player_isgambling2","s_player_zhide2",
    "s_player_cleanguts","s_player_makepiss","s_player_makepoo","s_player_box","s_player_behero","s_player_bebandit","s_player_managework","s_player_xmastree","s_player_xmas",
	"s_player_refugee","s_player_refugee_guard","s_player_detentiondoor","s_player_get_key","s_player_sisterdoor","s_player_baker","s_player_sisterdoor2",
	"s_player_questions","s_player_fillMelamine","s_player_tobacco","s_player_animals_actions","s_player_Sowtobacco",
	"s_player_tobaccoGrow","s_player_waterSupply","s_player_tobacco_def","s_player_tobacco_mer","s_player_opencrate","s_player_openViruscrate","s_player_radioON",
	"s_player_flipcrate","s_player_cannibal"
```
