# Problem:
https://www.google.com/search?q=ubuntu+android+studio+intel+some+users+have+experienced+emulator+stability+issues+with+this+driver+version

# Solution: Run an AVD from command line!
https://stackoverflow.com/questions/45121828/android-studio-suddenly-got-gpu-driver-issue-when-running-emulator

## Works:
```
avd_instance=Pixel_8_Pro
cd ~/Android/Sdk/emulator ; ./emulator -avd $avd_instance -gpu host
```
