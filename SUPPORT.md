# Setup and connection checks

1. Install the **Ableton Live** plugin, then the **Ableton Dial Profile** or **Ableton Deck Profile** for your device family and OS.
2. Open an Ableton action → **Integration** → **Install / Repair Integration**. If needed, choose the User Library configured in Live. You do not need to move your library to the default location.
3. Fully restart Live. In **Settings → Link, Tempo & MIDI**, select **Ulanzi** in one **Control Surface** row. Input and Output should both be **None**. Replace an old Dial row instead of enabling both.
4. Keep Ulanzi Studio running. Look for **Connected**; Installed alone does not confirm communication. Mixing and dynamic values require the connection.

If it stays Basic/Offline, open a bug report with the exact versions, Integration tab and Control Surface screenshots, and the affected functions. Tell us whether the User Library is default, custom, external, OneDrive or another cloud folder, and whether restarting or rebooting changes the result. Include Studio and Live UI languages and keyboard layout if shortcuts behave differently.

For Windows, relevant Live errors are in `%APPDATA%\Ableton\Live <version>\Preferences\Log.txt`. On macOS, use `~/Library/Preferences/Ableton/Live <version>/Log.txt`. Search for `Ulanzi`, `Ableton Live:`, `Traceback`, `could not bind`, or `61337`. Include the nearby error lines and any plugin connection error. Redact usernames, project names and unrelated personal paths before posting publicly. A complete Live Set is not needed.

One D200X profile per OS covers the D200 family, as confirmed by Ulanzi. The separate Dial profile is for Ulanzi Dial. When importing manually, select the appropriate device first.

This plugin controls supported Live parameters. It does not provide generic mouse-hover control over arbitrary third-party plugin knobs. Fine scrolling through another profile’s mouse-wheel action is a separate Ulanzi feature.
