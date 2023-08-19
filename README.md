# URL Launcher App with AppleScript - Spotlight Shortcut

If, like me, you regularly visit the same URL addresses and want to save a few enjoyable seconds by opening them more efficiently, here's how I solved this problem on macOS.

The idea is very simple: create a URL launcher application using AppleScript. This application can be easily accessed using the macOS native Spotlight feature (Command + Spacebar).


## How to

1. **Open AppleScript editor**.
   
2. Make sur to use the **AppleScript language**, not Javascript.

3. **Write the snippet**:
    ```AppleScript
    open location "yourURL"
    ```

4. **Verify you code is running** as expected by pressing the ▶ button on top right pannel.

5. **File > Save** : 
   - Choose a name for your app.
    - Select the file type: Application.

## Bonus: Customized Icon

You can customize the icon of your app:

- Prepare an image in PNG format, preferably formatted for an icon, and name it "applet.icns".
- Right-click on your app > Open package > Contents > Resources.
- Replace the existing "applet.icns" with your own icon.
