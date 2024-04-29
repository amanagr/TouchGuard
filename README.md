# TouchGuard

### Instructions for installation

1. Download this repo.
2. Extract files on Desktop.
3. Run this command in terminal. (make TouchGuard executable)
```
cd Desktop
sudo chmod +x TouchGuard
```
4. Copy `TouchGuard` file (executable now) to `/usr/local/bin/` folder (eg `sudo cp TouchGuard /usr/local/bin/`).
5. Copy `org.amanagr.TouchGuard.driver.Daemon.plist` to `/Library/LaunchDaemons` (eg `sudo cp org.amanagr.TouchGuard.driver.Daemon.plist /Library/LaunchDaemons/`).
6. Reboot.

Based on [thesyntaxinator/TouchGuard](https://github.com/thesyntaxinator/TouchGuard)
