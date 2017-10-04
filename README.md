# gnome-shell-extension-window-session-manager

An indicator that let's you save and restore your open apps and the window positions and arrangements over multiple real and virtual displays.

![Screenshot](/screenshot.png "Screenshot")

Based on [lwsm](https://github.com/johannesjo/linux-window-session-manager).

## setup
Download or clone repository and move all files to `/home/your-user-name/.local/share/gnome-shell/extensions/lwsm@johannes.super-productivity.com`:

```
cd tmp
git clone git@github.com:johannesjo/gnome-shell-extension-window-session-manager.git
mv gnome-shell-extension-window-session-manager /home/$(whoami)/.local/share/gnome-shell/extensions/lwsm@johannes.super-productivity.com`
```

# usage
After a successfull setup you should see an "screen" icon at your top bar. Click on it to open the menu. To save your first window session click on the text input and enter a name for it. Click on the save icon to save it. 

After this can either restore a previously saved session by clicking on the play icon, delete them by clicking on the x icon or update them by clicking on the save icon. 

The opened applications and windows are saved independently for each screen combination, which means that you can have a different set of applications and arrangements for each of them and also need to save them indepdently. 
