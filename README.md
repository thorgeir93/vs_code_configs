# vs_code_configs

# Enable settings
Make sure the User settings/keybindings does not already exists, if so take backup of them and replace them using below commands.

```
ln --symbolic $(pwd)/User/keybindings.json ~/.config/Code/User/keybindings.json
ln --symbolic $(pwd)/User/settings.json ~/.config/Code/User/settings.json
```
