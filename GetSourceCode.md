# Import all in Eclipse workspace #

  * `git clone --recursive https://code.google.com/p/droid2droid/`
  * `cd droid2droid`

  * Menu File/Import/Existing project into Workspace
  * Select `droid2droid` and Finish

  * Menu New/Other/Android/Android Project from Existing Code
  * Select `workspace/root/ActionBarSherlock/library`
  * Rename the project `library` to `actionbarsherlock-library`


# Import only root projects #

  * `cd workspace`
  * `git clone --recursive https://code.google.com/p/droid2droid.root/ root`

  * Menu File/Import/Existing project into Workspace
  * Select workspace/root and Finish

  * Menu New/Other/Android/Android Project from Existing Code
  * Select workspace/root/ActionBarSherlock/library
  * Rename the project `library` to `actionbarsherlock-library`


# Import only apps projects #
  * `cd workspace`
  * `git clone --recursive https://code.google.com/p/droid2droid.apps/ apps`

  * Menu File/Import/Existing project into Workspace
  * Select workspace/apps and Finish