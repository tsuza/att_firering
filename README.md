<div align="center">
  <h1><code>Fire Ring Attribute</code></h1>
  <p>
    <strong>A custom attribute that fires a **huo-long heater**-like fire ring around you upon activating the rage.</strong>
  </p>
  <p style="margin-bottom: 0.5ex;">
    <img
        src="https://img.shields.io/github/downloads/Zabaniya001/att_firering/total"
    />
    <img
        src="https://img.shields.io/github/last-commit/Zabaniya001/att_firering"
    />
    <img
        src="https://img.shields.io/github/issues/Zabaniya001/att_firering"
    />
    <img
        src="https://img.shields.io/github/issues-closed/Zabaniya001/att_firering"
    />
    <img
        src="https://img.shields.io/github/repo-size/Zabaniya001/att_firering"
    />
    <img
        src="https://img.shields.io/github/workflow/status/Zabaniya001/att_firering/Compile%20and%20release"
    />
  </p>
</div>

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
## Information

### Attributes explanation

This custom attribute lets you have a fire ring around you, similar to huo-long heater's. However, since you're not using a minigun and you don't "slow down to shoot" like what a minigun does, this custom attribute has a meter system. Once it reaches 100%, you can activate it. It'll deal dmg around you and you'll gain the vampire power-up. Though, you can remove the last part if you want. I manage a ff2 server and it was necessary to make pyro survive.

```
"fire ring attribute"   "max_rage=1000.0 damage=70.0 radius=150.0 duration=10.0"
```

These are its arguments. You can change 'em however it pleases you. 

| Name                            | Description                                                                                                                                           |
| ------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------|
| `max_rage`                      | The total amount of damage that the player has to deal to active the fire ring                                                                        |
| `damage`                        | The amount of damage it deals every 0.5 seconds ( same interval that the huo-long heater uses )                                                       |
| `radius`                        | The radius of the fire ring ( 150.0 is the stock radius for the huo-long heater, you can change it )                                                  |
| `duration`                      | The amount of time that the fire ring lasts.                                                                                                          |


## Requirements

- [TF Custom Attribute Framework](https://github.com/nosoop/SM-TFCustAttr)
- [TF2 Utils](https://github.com/nosoop/SM-TFUtils)
- [TF2 Attribute ( >1.7.2 )](https://github.com/FlaminSarge/tf2attributes)


### Supported

- [CWX / Custom Weapons X](https://github.com/nosoop/SM-TFCustomWeaponsX)