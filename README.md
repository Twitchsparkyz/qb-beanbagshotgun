# Bean Bag Shotgun
Addon bean bag shotgun to use with qbcore

# Installation:
Add to qb-core/shared/weapons.lua

```
[`weapon_beanbagshotgun`]					= {['name'] = 'weapon_beanbagshotgun',				['label'] = 'Non-Lethal Shotgun',						['ammotype'] = nil,						['damagereason'] = 'Hit by a bean bag'},
  
```

Add to qb-core/shared/items.lua

```
	['weapon_beanbagshotgun'] 			 = {['name'] = 'weapon_beanbagshotgun', 		 	  	['label'] = 'Non-Lethal Shotgun', 			    ['weight'] = 1000, 		['type'] = 'weapon', 	['ammotype'] = 'AMMO_PISTOL',			['image'] = 'weapon_beanbagshotgun.png', 		['unique'] = true, 		['useable'] = false, 	['description'] = 'A Non-lethal version of the Remington 870'},
```

Add to qb-smallresources/client/weapondraw.lua

```
	'WEAPON_BEANBAGSHOTGUN',
  
```

Add to qb-weapons/config.lua at Config.DurabilityMultiplier

```
    ['weapon_beangbagshotgun'] 		= 0.0,
```

Add to qb-weapons/config.lau at Config.WeaponRepairCosts

```
    ['WEAPON_PAINTBALL'] = {
        ['defaultclip'] = {
            component = 'COMPONENT_BEANBAGSHOTGUN_CLIP_01',
            item = 'pumpshotgun_defaultclip',
            type = 'clip',
        },
    },
```

Add to qb-ambulancejob/config.lua

```
    [`WEAPON_BEANGBAGSHOTGUN`] = Config.WeaponClasses['NONE'],
```

Add to qb-smallresources/client/recoil.lua

```
[GetHashKey("weapon_beanbagshotgun")] = 0.0,
```

Add this image to qb-inventory/html/images with name: weapon_beanbagshotgun.png
![weapon_beanbagshotgun](https://cdn.discordapp.com/attachments/1001927439850684456/1015844092237844522/My_project-1_1.png)

# Weapon Model and skin credits:
https://www.gta5-mods.com/weapons/less-lethal-shotgun-bean-bag-shotgun
