# World of Warcraft

## Reset all settings (hardcore)

1. In the game, go to settings and click on the "Reset to default button"
2. Disconnect from World of Warcraft.
3. Go do the directory and rename the `WTF` folder to `WTF.old`.
4. Create a new empty `WTF` folder.
5. Create a `Config.wtf`
6. Write the following lines into the `Config.wtf` file:

    ```
    SET synchronizeConfig "0"
    SET synchronizeSettings "0"
    ```
7. Start the game but disable all addons
8. Type the following two commands: 

```
/console synchronizeConfig 1
/console synchronizeSettings 1
```

9. Quit the game.
10. Remove the `WTF` folder again, and the `WTF.old`
11. Finally, start the game and you should be good to go !
