# HvH 2v2 Plugin Pack 

This plugin pack was tested and works fine. If you want any help DM me on discord or create an issue on this rep.

You need to change the configs and if you want you can change the translations.

Credits : @asm_000009 and me

# CommandLine / Startup Config
```bash
-norestart -game csgo -console -condebug -usercon +game_type 0 +game_mode 2 -maxplayers_override 10 +exec server.cfg +mapgroup mg_active +map de_vertigo -ip YOURIP +net_public_adr YOURIP -ip_tv YOURIP -port YOURPORT -tv_port YOURPORT -tickrate 64 -stringtables -nobots -insecure
```

   # 2v2 Map Pool should include:
    
    de_cbble
    de_inferno
    de_shortnuke
    de_overpass
    de_train
    de_vertigo
    de_shortdust
    de_bank
    de_cache
    de_safehouse
    de_stmarc
    de_lake
    
   
You can change this on /addons/sourcemod/config/pugsetup and maps.txt

#Plugins Restrictions Convars

For now, 5v5 is not included, but will soon configure it.
No guns are restriced.

- Unmatched Restrictions / Exploit Fixes Convar (credits to imi-tat0r)
    um_restrict_untrusted_angles = 1 / If this cvar is enabled, untrusted angles will be normalized/clamped
	um_restrict_body_lean = 1 / If this cvar is enabled, body lean will be disabled
	um_restrict_extended_angles = 1 / If this cvar is enabled, extended angles will be disabled
	um_restrict_fake_duck = 0 / If this cvar is enabled, fake duck will be disabled
  




