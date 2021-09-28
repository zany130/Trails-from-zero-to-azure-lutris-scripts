# Trails-from-zero-to-azure-lutris-scripts
lutris scripts to run trails from zero and trails to azure on linux
To run this script, simply download it and run `lutris -i trails-from-zero.yml` and `lutris -i trails-to-azure.yml` in your console.
Do not run the game from the installer as it apply the overides to load the geofront mod after exiting. If you need to rerun the installer select the game and click on the wine bottle on the lower left and select run exe in wine prefix and browse to the installer.

Also setting anti aliasing to anything higher than 4x casues visual glitch's (seems to be fixed with DXVK 1.9)

zero runs fine  with the defualt lutris wine version, but azure need's 6.1-3 get it by clicking on the cog next to runners in lutris and scrolling down to wine and then clicking the first cog to manage versions and select 6.1-3, also there might be some random crashes with DXVK enabled (example end of chapter 4 crashes with DXVK enabled) So I disabled it but if you get any graphical issues escpecially with frame pacing enable DXVK.

I disabled DXVK as in zero it would cause screen flickering in battles. (seems to be fixed in 1.9) I have yet to have this issue in azure but I disabled it anyway the game dosn't seem to run worse because of it, but if you notice any issues try renabling DXVK in the wine runner settings 
