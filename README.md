**Car Lock UI** allows players to deploy code locks to modular cars at a car lift using a UI.

*Note: This plugin plus [Vehicle Deployed Locks](https://umod.org/plugins/vehicle-deployed-locks) replace [Modular Car Code Locks](https://umod.org/plugins/modular-car-code-locks).*

Players will see the UI while "looting" a car at a lift if the following conditions are met.
- The player has permission.
- The player is not building blocked.
- The player has a code lock, sufficient resources to craft one, or permission for free locks in the Vehicle Deployed Locks plugin.
- The car has a cockpit module (i.e., driver seat).
- The car does not already have a key lock or code lock deployed to it (though it may have a built-in car lock).

Note: This plugin requires the [Vehicle Deployed Locks](https://umod.org/plugins/vehicle-deployed-locks) plugin to be installed, but you can safely install that plugin without any setup because its default mode is passive, meaning it will just support other plugins like this one. If you want, you can optionally configure that plugin to alter some aspects of how code locks work on cars and other vehicles.

## UI Screenshots

![Add Code Lock Button](https://i.imgur.com/Xk91dHF.png)
![Remove Code Lock Button](https://i.imgur.com/IT1xsrZ.png)

## Permissions

- `carlockui.use.codelock` -- Allows the player to deploy and remove code locks via UI buttons while editing a car at a lift.

*Open to supporting deployed key locks on request*.

## Configuration
```json
{
  "UISettings": {
    "AddButtonColor": "0.44 0.54 0.26 1",
    "AnchorMax": "1 0",
    "AnchorMin": "1 0",
    "ButtonTextColor": "0.97 0.92 0.88 1",
    "OffsetMax": "-68 377",
    "OffsetMin": "-255 349",
    "RemoveButtonColor": "0.7 0.3 0 1"
  }
}
```

- `UISettings` -- (Advanced) Control the display of the UI buttons.

## Localization

```json
{
  "UI.AddCodeLock": "Add Code Lock",
  "UI.RemoveCodeLock": "REMOVE Code Lock"
}
```
