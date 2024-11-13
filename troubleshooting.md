# troubleshooting
there are some fixes for most of the common errors that may happen during the process. check if the following methods can solve your problems, or reach me [here](https://github.com/ddvniele/checkm8-iOS15-14-downgrade/issues)

## futurerestore is unable to obtain keys for your device
if this happens, there's a fix for you:
- install [Homebrew](https://brew.sh/) on your mac
- install python3 using your terminal: <code>brew install python</code>
- run <code>pip3 install requests pyquery Flask --break-system-packages</code
- download [this file](https://github.com/ddvniele/checkm8-iOS15-14-downgrade/releases/download/downloads/wikiproxy.py)
- then, every time you run futurerestore, before starting the process open another terminal window and run <code>python3 (path-to-wikiproxy)</code>
  - instead of (path-to-wikiproxy), drag and drop the wikiproxy file you downloaded on your terminal window
- keep this window opened until futurerestore completes the restore


## ⚠️ known issues without a solution (for now)
- iCloud passwords don't work (at least for me)
