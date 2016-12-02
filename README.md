# Noku-Tofu
DockbarX theme

Find where your dockbarX themes are (for me it's ~/.dockbarx/themes) and place inside it the NokuTofu.tar.gz and Foyu.tar.gz in the popup_styles folder (you may have to create this folder). The rest of the files are for tweaking and repackaging into the tar.gz. You can re-color them with the resources here.

Again, the only things you need in your dockbarx's themes folder:

* NokuTofu.tar.gz
* popup_styles/Foyu.tar.gz

Then open dockbar preferences (right click > properties for xfce panel) and set

* Theme > Noku Tofu
* Window list style > Foyu
* Window list background > Color name: #FFFFFF & Opacity: 31
* Active window > Color name: #009688 (or match your adapta theme, mine is set to use teal)
* Normal text > Color name: #CBD1D4
* Minimized window text > Color name: #7B8387
* Needs attention effect > Blinking
* Check "Use gtk menu (old style)"
* Done!

You can unpackage NokuTofu and Foyu to see which files go in which package. Re-color and re-package, open DockBarX preferences, swap themes, hit refresh button, swap back to Noku Tofu, hit refresh and it should work.
