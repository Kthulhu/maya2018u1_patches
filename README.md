# m2018_update1_patches
Patch for Maya 2018 update 1 script files

List of files:
scripts/AETemplates/AEcameraImagePlaneNew.mel
//Image plane creation code, automatically creates new quick selection set named "im_planes" when user adds image plane.



scripts/startup/hotkeySetup.mel
// Removed hardcoded group hotkey

scripts/startup/statusLine.mel
// Hypershade button moved back to the left
// Added quick resolution switcher to the "Render" button's right click

scripts/others/buildHypergraphNodePopupMenuItems.mel
// Added "duplicate with connections" and "select objects with material" to hypershader mat right-click menu

scripts/others/dagMenuProc.mel
// Removes annoying menus from general view right-click menu: all those showEditor and other commands that either change your selection or calling AE all the time

scripts/others/doGroup.mel
// Grouping now uses some meaningful name from the first object in selection

scripts/others/doPlayblastArgList.mel
// "Ok" button is default now in file overwrite dialog

scripts/others/dynAddAttrWin.mel
// dynAttr window is not resetting now every time user creates an attribute

scripts/others/getAutomaticCacheName.mel
// Cache name got some meaningful name now

scripts/others/graphEditorPanel.mel
// You're not calling that menu accidentally now, it's moved to Ctrl-right click

scripts/others/hyperShadePanel.mel
// Added 2 buttons to hypershade toolbar: "create shading node" and "duplicate with connections"

scripts/others/imageFormats.mel
// Obsolete/unneeded formats totally removed, just most frequently used ones are left

scripts/others/importImagePlane.mel
// Fix for imagePlane creation: new image plane will be added to "im_plane" quick selection set

scripts/others/OutlinerEdMenu.mel
// 4 buttons in right-click menu: Toggle bbox/template/shading/reference states for selection

scripts/others/performPlayblast.mel
// playblast file goes to system %TEMP% dir now

scripts/others/performPolyMove.mel
// Little fix for patched component selection keyscript

scripts/others/renderWindowPanel.mel
// Render window now won't be larger than screen

scripts/others/saveChanges.mel
// Unsaved scene confirmation dialog commented out. Save your scenes yourself.

scripts/others/showEditor.mel
// Adds "close" button to floating AE


