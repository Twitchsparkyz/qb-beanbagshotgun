# Bean Bag Shotgun
Addon bean bag shotgun to use with qbcore

# Installation:
Add to qb-core/shared/weapons.lua

```
[`weapon_beanbagshotgun`]					= {['name'] = 'weapon_beanbagshotgun',				['label'] = 'Non-Lethal Shotgun',						['ammotype'] = 'AMMO_SHOTGUN',						['damagereason'] = 'Hit by a bean bag'},
  
```

Add to qb-core/shared/items.lua

```
	['weapon_beanbagshotgun'] 			 = {['name'] = 'weapon_beanbagshotgun', 		 	  	['label'] = 'Non-Lethal Shotgun', 			    ['weight'] = 1000, 		['type'] = 'weapon', 	['ammotype'] = 'AMMO_SHOTGUN',			['image'] = 'weapon_beanbagshotgun.png', 		['unique'] = true, 		['useable'] = false, 	['description'] = 'A Non-lethal version of the Remington 870'},
```

Add to qb-weapons/config.lua at Config.DurabilityMultiplier

```
    ['weapon_beanbagshotgun'] 		= 0.0,
```

Add to qb-weapons/config.lau at WeaponAttachments

```
    ['WEAPON_BEANBAGSHOTGUN'] = {
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

Add this image to qb-inventory/html/images with name: weapon_beanbagshotgun.png
![weapon_beanbagshotgun](https://cdn.discordapp.com/attachments/1083123794765426789/1263504832329941012/weapon_beanbagshotgun.png?ex=669a7a12&is=66992892&hm=bd16dc8f7e2efb8c42bfa5cffa4389040ad82b57967feafadd0bb5cc919517d8&)

# Weapon Model and skin credits:
https://www.gta5-mods.com/weapons/less-lethal-shotgun-bean-bag-shotgun
