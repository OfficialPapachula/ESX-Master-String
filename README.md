# Installation

Step 1 : Add esx folder to resources directory. Then add the following to your "server.cfg" : 

#ESX Resources

start mysql-async
start essentialmode
start async
start extendedmode
start instance
start esx_menu_default
start esx_menu_list
start esx_menu_dialog
start esx_billing
start esx_society
start cron
start skinchanger
start esx_skin
start esx_addonaccount
start esx_addoninventory
start esx_datastore
start esx_identity
start esx_license
start esx_animations
start esx_rpchat
start esx_status
start esx_property
start esx_accessories
start esx_service
start esx_bankerjob
start esx_cruisecontrol
start esx_clotheshop
start esx_boat
start esx_jobs
start esx_weaponshop
start esx_lscustom
start esx_joblisting
start esx-kr-advanced-shops
start esx_mechanicjob
start esx_taxijob
start esx_drugs
start esx_holdup
start esx_sit
start esx_barbershop
start esx_basicneeds
start esx_dmvschool
start esx_ambulancejob
start esx_policejob
start esx_vehicleshop
start pNotify
start esx_drp_garage
start LegacyFuel
start trew_hud_ui
start new_banking
start admincars
start adminpeds
start esx_admins
start ShowOwnID
start esx_pilotjob-master
start esx_gym

The order does matter so be sure to copy word for word. 

Step 2 : Import "extendedmode.sql" into your database. 

Troubleshooting : 

If a resource is not working, make sure that you have imported the sql for said resource into your database. 
