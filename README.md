# Fire Ring Attribute

Custom Attribute using Nosoop's [custom attributes framework](https://github.com/nosoop/SM-TFCustAttr). 

This custom attribute lets you have a fire ring around you, similar to huo-long heater's. However, since you're not using a minigun and you don't "slow down to shoot" like what a minigun does, this custom attribute has a meter system. Once it reaches 100%, you can activate it. It'll deal dmg around you and you'll gain the vampire power-up. Though, you can remove the last part if you want. I manage a ff2 server and it was necessary to make pyro survive.

```
"fire ring attribute"   "max_rage=1000.0 damage=70.0 radius=150.0 duration=10.0"
```

These are its arguments. You can change 'em however it pleases you. 
```
- max_rage <- The total amount of damage that the player has to deal to active the fire ring
- damage <- The amount of damage it deals every 0.5 seconds ( same interval that the huo-long heater uses )
- radius <- The radius of the fire ring ( 150.0 is the stock radius for the huo-long heater, you can change it )
- duration <- The amount of time that the fire ring lasts.
```
Tested it on Nosoop's [Custom Weapon X](https://github.com/nosoop/SM-TFCustomWeaponsX) and it works without any problems.

This plugin uses Nosoop's [Ninja](https://github.com/nosoop/NinjaBuild-SMPlugin) template. Easy to organize everything and build releases. I'd recommend to check it out.

Please, this is the first version of this plugin. If you find any issues, make sure to open an issue to let me know!

Also I've got no clue how to properly format this.
