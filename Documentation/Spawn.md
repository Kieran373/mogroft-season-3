# Spawn

## Armor Stands

Armor Stands haben folgende spezielle Eigenschaften:
- `ShowArms:1b`
- `NoBasePlate:1b`
  - Verstecke die graue Bodenplatte des Armor Stands.
- `DisabledSlots:4144959`
  - Sperre die Slots Main-Hand, Off-Hand, Helm, Chest, Leggings, Boots fürs Removen, Replacen, Placen von Items.
- `Invulnerable:1b`
  - Mache den Armor Stand unverwundbar, sodass er nicht zerstört werden kann.
- `NoGravity:1b`
- `Tags:[<identifikation>]`
  - Gebe dem Armor Stand einen Tag, sodass er z. B. darüber gekillt werden kann: `/kill @e[type=minecraft:armor_stand,tag=hendrik]`
- `equipment: {<equip>}`
  - Enthält folgende Beispielwerte:
    ```mc
    equipment:{
      head:{id:player_head,components:{profile:{name:AusterBirke98}}},
      chest:{id:leather_chestplate,components:{dyed_color:5415167}},
      legs:{id:leather_leggings,components:{dyed_color:7692627}},
      feet:{id:leather_boots,components:{dyed_color:5415167}}
    }
    ```

### AusterBirke98
- [x] platziert
- Tag: `hendrik`

Command:
```mc
summon armor_stand -62.4 291.5 79.8 {Pose:{Head:[25f,0f,0f],LeftArm:[0f,0f,327f],RightArm:[276f,66f,0f],LeftLeg:[15f,0f,0f],RightLeg:[351f,0f,0f]},ShowArms:1b,NoBasePlate:1b,DisabledSlots:4144959,Invulnerable:1b,NoGravity:1b,Rotation:[166f,0],Tags:[hendrik],equipment:{head:{id:player_head,components:{profile:{name:AusterBirke98}}},chest:{id:leather_chestplate,components:{dyed_color:5415167}},legs:{id:leather_leggings,components:{dyed_color:7692627}},feet:{id:leather_boots,components:{dyed_color:5415167}}}}
```

### ZugTier06
- [x] platziert
- Tag: `lars`

Command:
```mc
summon armor_stand -62.2 291 80.9 {Pose:{LeftArm:[258f,359f,0f],RightArm:[273f,8f,0f],LeftLeg:[348f,0f,0f],RightLeg:[18f,0f,0f]},ShowArms:1b,NoBasePlate:1b,DisabledSlots:4144959,Invulnerable:1b,NoGravity:1b,Rotation:[168f,0],Tags:[lars],equipment:{head:{id:player_head,components:{profile:{name:ZugTier06}}},chest:{id:leather_chestplate,components:{dyed_color:3355443}},legs:{id:leather_leggings,components:{dyed_color:0}},feet:{id:leather_boots,components:{dyed_color:3355443}}}}
```

### Noel6384
- [x] platziert
- Tag: `noel`

Command:
```mc
summon armor_stand -59 290 89.5 {Pose:{LeftArm:[263f,299f,0f],RightArm:[248f,38f,0f],RightLeg:[0f,8f,0f]},ShowArms:1b,NoBasePlate:1b,DisabledSlots:4144959,Invulnerable:1b,NoGravity:1b,Rotation:[248f,0],Tags:[noel],equipment:{head:{id:player_head,components:{profile:{name:Noel6384}}},chest:{id:leather_chestplate,components:{dyed_color:1996071}},legs:{id:leather_leggings,components:{dyed_color:6532458}},feet:{id:leather_boots,components:{dyed_color:1996071}}}}
```

### ninotf
- [x] platziert
- Tag: `nino`

Command:
```mc
summon armor_stand -55.5 289.8 88.2 {Pose:{LeftArm:[316f,0f,345f],RightArm:[350f,0f,14f],LeftLeg:[273f,349f,0f],RightLeg:[273f,8f,0f]},ShowArms:1b,NoBasePlate:1b,DisabledSlots:4144959,Invulnerable:1b,NoGravity:1b,Rotation:[68f,0],Tags:[nino],equipment:{head:{id:player_head,components:{profile:{name:ninotf}}},chest:{id:leather_chestplate,components:{dyed_color:16770926}},legs:{id:leather_leggings,components:{dyed_color:1996071}},feet:{id:leather_boots,components:{dyed_color:16770926}}}}
```

### whoslilian
- [x] platziert
- Tag: `mara`

Command:
```mc
summon armor_stand -55.5 289.8 86.4 {Pose:{LeftArm:[350f,0f,345f],RightArm:[320f,0f,70f],LeftLeg:[273f,349f,0f],RightLeg:[273f,8f,0f]},ShowArms:1b,NoBasePlate:1b,DisabledSlots:4144959,Invulnerable:1b,NoGravity:1b,Rotation:[43f,0],Tags:[mara],equipment:{head:{id:player_head,components:{profile:{name:whoslilian}}},chest:{id:leather_chestplate,components:{dyed_color:12022783}},legs:{id:leather_leggings,components:{dyed_color:16777215}},feet:{id:leather_boots,components:{dyed_color:12022783}}}}
```

### Expeerte
- [x] platziert
- Tag: `peer`

Command:
```mc
summon armor_stand -75.5 293 98.5 {Pose:{Head:[0f,26f,0f],LeftArm:[341f,0f,347f],RightArm:[251f,46f,0f],RightLeg:[336f,41f,0f]},ShowArms:1b,NoBasePlate:1b,DisabledSlots:4144959,Invulnerable:1b,NoGravity:1b,Rotation:[226f,0],Tags:[peer],equipment:{head:{id:player_head,components:{profile:{name:Expeerte}}},chest:{id:leather_chestplate,components:{dyed_color:0}},legs:{id:leather_leggings,components:{dyed_color:6488086}},feet:{id:leather_boots,components:{dyed_color:0}}}}
```

### MinJungKieran
- [x] platziert
- Tag: `kieran`

Command:
```mc
summon armor_stand -71.55 290 98.5 {Pose:{Head:[50f,0f,0f],Body:[10f,0f,0f],LeftArm:[50f,331f,0f],RightArm:[50f,31f,0f],LeftLeg:[40f,0f,0f],RightLeg:[326f,0f,0f]},ShowArms:1b,NoBasePlate:1b,DisabledSlots:4144959,Invulnerable:1b,NoGravity:1b,Rotation:[271f,0],Tags:[kieran],equipment:{head:{id:player_head,components:{profile:{name:MinJungKieran}}},chest:{id:leather_chestplate,components:{dyed_color:16777215}},legs:{id:leather_leggings,components:{dyed_color:16711812}},feet:{id:leather_boots,components:{dyed_color:16777215}}}}
```

### Jczy
- [x] platziert
- Tag: `fred`

Command:
```mc
summon armor_stand -61.9 292 92.5 {Pose:{Head:[331f,36f,0f],Body:[0f,0f,352f],LeftArm:[356f,0f,207f],RightArm:[351f,0f,87f],LeftLeg:[15f,0f,317f],RightLeg:[351f,8f,7f]},ShowArms:1b,NoBasePlate:1b,DisabledSlots:4144959,Invulnerable:1b,NoGravity:1b,Rotation:[176f,0],Tags:[fred],equipment:{head:{id:player_head,components:{profile:{name:Jczy}}},chest:{id:leather_chestplate,components:{dyed_color:15773139}},legs:{id:leather_leggings,components:{dyed_color:16777215}},feet:{id:leather_boots,components:{dyed_color:15773139}}}}
```

### Laubfrosch49
- [x] platziert
- Tag: `piet`

Command:
```mc
summon armor_stand -60.85 293.25 90.5 {Pose:{Head:[10f,0f,0f],Body:[15f,0f,0f],LeftArm:[231f,0f,342f],RightArm:[231f,1f,12f],LeftLeg:[291f,342f,0f],RightLeg:[291f,16f,0f]},ShowArms:1b,NoBasePlate:1b,DisabledSlots:4144959,Invulnerable:1b,NoGravity:1b,Rotation:[85f,0],Tags:[piet],equipment:{head:{id:player_head,components:{profile:{name:Laubfrosch49}}},chest:{id:leather_chestplate,components:{dyed_color:11921545}},legs:{id:leather_leggings,components:{dyed_color:7692627}},feet:{id:leather_boots,components:{dyed_color:11921545}}}}
```

### JoProLP
- [x] platziert
- Tag: `johannes`

Command:
```mc
summon armor_stand -80.5 292.3 94.0 {Pose:{Head:[35f,0f,0f],Body:[10f,0f,0f],LeftArm:[231f,0f,352f],RightArm:[231f,0f,7f],LeftLeg:[346f,0f,0f],RightLeg:[15f,0f,0f]},ShowArms:1b,NoBasePlate:1b,DisabledSlots:4144959,Invulnerable:1b,NoGravity:1b,Rotation:[181f,0],Tags:[johannes],equipment:{head:{id:player_head,components:{profile:{name:JoProLP}}},chest:{id:leather_chestplate,components:{dyed_color:16765056}},legs:{id:leather_leggings,components:{dyed_color:5542911}},feet:{id:leather_boots,components:{dyed_color:16765056}}}}
```

### Leonv2d
- [x] platziert
- Tag: `leon`

Command:
```mc
summon armor_stand -82 289.3 90 {Pose:{Head:[316f,0f,0f],LeftArm:[331f,352f,0f],RightArm:[341f,21f,0f],LeftLeg:[266f,342f,0f],RightLeg:[266f,16f,0f]},ShowArms:1b,NoBasePlate:1b,DisabledSlots:4144959,Invulnerable:1b,NoGravity:1b,Rotation:[331f,0],Tags:[leon],equipment:{head:{id:player_head,components:{profile:{name:Leonv2d}}},chest:{id:leather_chestplate,components:{dyed_color:15583559}},legs:{id:leather_leggings,components:{dyed_color:16711680}},feet:{id:leather_boots,components:{dyed_color:15583559}}}}
```

### GrummeLP
- [x] platziert
- Tag: `mika`

Command:
```mc
summon armor_stand -78.7 290.3 95.15 {Pose:{Head:[316f,36f,0f],Body:[5f,0f,0f],LeftArm:[286f,342f,0f],RightArm:[296f,347f,0f],LeftLeg:[351f,331f,0f],RightLeg:[341f,11f,0f]},ShowArms:1b,NoBasePlate:1b,DisabledSlots:4144959,Invulnerable:1b,NoGravity:1b,Rotation:[90f,0],Tags:[mika],equipment:{head:{id:player_head,components:{profile:{name:GrummeLP}}},chest:{id:leather_chestplate,components:{dyed_color:8412217}},legs:{id:leather_leggings,components:{dyed_color:16757504}},feet:{id:leather_boots,components:{dyed_color:8412217}}}}
```