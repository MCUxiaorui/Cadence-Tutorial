# Cadence-Tutorial
## Start
### Start Cadence
🥇
* Navigate to your folder
* Open FreePDK45 PDK
```
VLSI5545
```
* Open Virtuoso at the current location
```
virtuoso &
```
### Create Project
* create library
1. File -> new -> library -> OK
2. Attach to existing technology library -> OK
3. NCSU_TechLib_FreePDK45 -> OK

* create cell view
1. Select newly create library
2. File -> new -> cell view
3. In Pop-up -> name it -> OK
## Finish
### compress Project to tgz 
* Using tgz to compress the project file
```
tar -czvf  ProjectName_PID.tgz name-of-your-library
```
### Use in guacamole to open toolbar
* CTRL + SHIFT + ALT
