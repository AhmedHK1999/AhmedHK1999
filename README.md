- 👋 Hi, I’m @AhmedHK1999
- 👀 I’m interested in gta 5 roleplay
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
AhmedHK1999/AhmedHK1999 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
---># you probably don't want to change these!
# only change them if you're using a server with multiple network interfaces
endpoint_add_tcp "0.0.0.0:30120"
endpoint_add_udp "0.0.0.0:30120"

set mysql_connection_string "server=127.0.0.1;database=essentialmode;userid=root"
set es_enableCustomData 1

start mapmanager
start chat
start spawnmanager
start sessionmanager
start fivem
start hardcap
start rconlog
start scoreboard

start mysql-async
start async
start essentialmode
start esplugin_mysql
start es_admin2

start es_extended

start esx_menu_default
start esx_menu_list
start esx_menu_dialog

start instance
start cron
start esx_addonaccount
start esx_addoninventory
start esx_datastore
start esx_property
start esx_shops
start skinchanger
start esx_skin
start esx_clotheshop
start esx_jobs
start esx_vehicleshop
start esx_garage
start esx_billing
start esx_identity
start esx_policejob
start esx_holdup
start esx_joblisting
start es_AdvancedFuel
start es_carwash

start carhud
start vSync
start disclaimer
start bx-loading-screen
start heli
start interiors
start loadipl
start missionrow
start pausemenu-title
start pv-tow
start RealisticVehicleFailure
start RPDeath
start sheriffpd
start snowballs
start vk_handsup
start wastedscreen
start wk_actionmenu
start wk_wrs
start coordsaver
start streetLabel
start watermark
start mellotrainer

start ESU_thing
start els-fivem
start rims
start vics
start 2017-els-chp-pack
start bcsoels
start rev_vehicles_imports

start RealisticHandle
start indicators
start brakelights
start ToastysCruiseControl
start NativeUI
start dev-scripts
start dv_weapons
start dv_copcars
start pNotify
start NewsCam

start lscustoms

sv_scriptHookAllowed 1

# change this
rcon_password secretpassword123

sv_hostname "DevRain Dev Server"

# nested configs!
#exec server_internal.cfg

# loading a server icon (96x96 PNG file)
#load_server_icon myLogo.png

# convars for use from script
set temp_convar "hey world!"

# disable announcing? clear out the master by uncommenting this
#sv_master1 ""

# want to only allow players authenticated with a third-party provider like Steam?
sv_authMaxVariance 1
sv_authMinTrust 5

# add system admins
add_ace group.admin command allow # allow all commands
add_ace group.admin command.quit deny # but don't allow quit
add_principal identifier.steam:110000108527a21 group.admin # devoutrain - server-commandline-admin
add_ace resource.essentialmode command.add_ace allow
add_ace resource.essentialmode command.add_principal allow

# hide player endpoints in external log output
sv_endpointprivacy true

# server slots limit (default to 32)
sv_maxclients 32

# license key for server (https://keymaster.fivem.net)
sv_licensekey cfxk_Bi13oevprLxeqtApk2Br_1SSLx1
