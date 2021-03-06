# Change Log

## [v0.17.16+20](https://github.com/danielo515/tiddlypouch/tree/v0.17.16+20) (2017-01-01)
[Full Changelog](https://github.com/danielo515/tiddlypouch/compare/v.0.15.2...v0.17.16+20)

**Implemented enhancements:**

- Remove legacy design document  [\#50](https://github.com/danielo515/tiddlypouch/issues/50)
- Update pouchdb to version 6 [\#47](https://github.com/danielo515/tiddlypouch/issues/47)
- Fix sync problems [\#51](https://github.com/danielo515/tiddlypouch/pull/51) ([danielo515](https://github.com/danielo515))

**Fixed bugs:**

- Two way replication issues on desktop browsers [\#49](https://github.com/danielo515/tiddlypouch/issues/49)
- Fix sync problems [\#51](https://github.com/danielo515/tiddlypouch/pull/51) ([danielo515](https://github.com/danielo515))

## [v.0.15.2](https://github.com/danielo515/tiddlypouch/tree/v.0.15.2) (2016-09-18)
[Full Changelog](https://github.com/danielo515/tiddlypouch/compare/v0.15.0...v.0.15.2)

**Implemented enhancements:**

- Methods to show and hide splash screen on $TPouch object [\#46](https://github.com/danielo515/tiddlypouch/issues/46)
- Provide a splash screen [\#7](https://github.com/danielo515/tiddlypouch/issues/7)

**Fixed bugs:**

- Weird issues when first loading [\#45](https://github.com/danielo515/tiddlypouch/issues/45)

**Closed issues:**

- Create a plugin library served over https [\#44](https://github.com/danielo515/tiddlypouch/issues/44)

## [v0.15.0](https://github.com/danielo515/tiddlypouch/tree/v0.15.0) (2016-09-17)
[Full Changelog](https://github.com/danielo515/tiddlypouch/compare/v0.15.1...v0.15.0)

## [v0.15.1](https://github.com/danielo515/tiddlypouch/tree/v0.15.1) (2016-09-17)
[Full Changelog](https://github.com/danielo515/tiddlypouch/compare/v0.14.5...v0.15.1)

**Implemented enhancements:**

- Provide a method to auto-update existing databases [\#43](https://github.com/danielo515/tiddlypouch/issues/43)
- Make sure that no tiddler is tried to be loaded or deleted from the pluginsStore [\#39](https://github.com/danielo515/tiddlypouch/issues/39)
- Exclude plugins from skinny tiddlers index [\#38](https://github.com/danielo515/tiddlypouch/issues/38)
- Use Promise.all for boost performance [\#37](https://github.com/danielo515/tiddlypouch/issues/37)
- Save plugins to the same DB as the regular tiddlers. Keep them as two DBs conceptually [\#36](https://github.com/danielo515/tiddlypouch/issues/36)
- Add promise polifyl [\#34](https://github.com/danielo515/tiddlypouch/issues/34)
- Allow config db as dependency injection on config module [\#31](https://github.com/danielo515/tiddlypouch/issues/31)
- Basic reading of config database before boot for selecting appropiate plugins [\#30](https://github.com/danielo515/tiddlypouch/issues/30)
- Inject plugins into the $tw object based on the selected database [\#29](https://github.com/danielo515/tiddlypouch/issues/29)
- Call routes binded to DbRouter object [\#28](https://github.com/danielo515/tiddlypouch/issues/28)
- Prevent $tw boot, then inject tiddlers and boot after the process completes. [\#26](https://github.com/danielo515/tiddlypouch/issues/26)
- Implement plugin convert DB decorator [\#25](https://github.com/danielo515/tiddlypouch/issues/25)
- Implement a route to route plugins to a plugins db [\#24](https://github.com/danielo515/tiddlypouch/issues/24)
- Make TiddlyPouch a global object [\#22](https://github.com/danielo515/tiddlypouch/issues/22)
- Fix the old changelog file [\#19](https://github.com/danielo515/tiddlypouch/issues/19)
- Remove subtitle from getting started panel [\#18](https://github.com/danielo515/tiddlypouch/issues/18)
- Create Router class [\#4](https://github.com/danielo515/tiddlypouch/issues/4)
- Load plugins at startup before TW boots [\#2](https://github.com/danielo515/tiddlypouch/issues/2)

**Fixed bugs:**

- Make sure that no tiddler is tried to be loaded or deleted from the pluginsStore [\#39](https://github.com/danielo515/tiddlypouch/issues/39)
- Exclude plugins from skinny tiddlers index [\#38](https://github.com/danielo515/tiddlypouch/issues/38)
- Version 0.14.4 does not allow to load revisions  [\#20](https://github.com/danielo515/tiddlypouch/issues/20)

**Closed issues:**

- Create a Base converter decorator [\#27](https://github.com/danielo515/tiddlypouch/issues/27)
- Move tiddlers between DBs [\#9](https://github.com/danielo515/tiddlypouch/issues/9)

## [v0.14.5](https://github.com/danielo515/tiddlypouch/tree/v0.14.5) (2016-09-11)
[Full Changelog](https://github.com/danielo515/tiddlypouch/compare/v0.14.4...v0.14.5)

**Implemented enhancements:**

- Provide an easy way to query an index for tiddlers [\#17](https://github.com/danielo515/tiddlypouch/issues/17)
- Skinny tiddlers should not be treated differently [\#16](https://github.com/danielo515/tiddlypouch/issues/16)
- Use a factory to instantiate DbStore objects [\#15](https://github.com/danielo515/tiddlypouch/issues/15)
- Inject conversion logic into DbStore [\#14](https://github.com/danielo515/tiddlypouch/issues/14)
- Make pouchdb a global object [\#6](https://github.com/danielo515/tiddlypouch/issues/6)
- Create DbStore class [\#3](https://github.com/danielo515/tiddlypouch/issues/3)

**Fixed bugs:**

- Version 0.14.3+1 doesn't allow to change the selected database  [\#12](https://github.com/danielo515/tiddlypouch/issues/12)

## [v0.14.4](https://github.com/danielo515/tiddlypouch/tree/v0.14.4) (2016-09-09)
[Full Changelog](https://github.com/danielo515/tiddlypouch/compare/v0.14.3+1...v0.14.4)

**Fixed bugs:**

- Blank screen when opening V0.14.3 [\#1](https://github.com/danielo515/tiddlypouch/issues/1)

**Merged pull requests:**

- Merge the latest working branch on master [\#13](https://github.com/danielo515/tiddlypouch/pull/13) ([danielo515](https://github.com/danielo515))
- Module loader [\#10](https://github.com/danielo515/tiddlypouch/pull/10) ([danielo515](https://github.com/danielo515))

# 0.14.4
## Bugfixes
- Fixed #1 blank screen on oppening
- Fixed version 0.14.3+1 doesn't allow to change the selected database #12
## [v0.14.3+1](https://github.com/danielo515/tiddlypouch/tree/v0.14.3+1) (2016-09-09)
[Full Changelog](https://github.com/danielo515/tiddlypouch/compare/v0.14.3...v0.14.3+1)

## [v0.14.3](https://github.com/danielo515/tiddlypouch/tree/v0.14.3) (2016-09-04)
[Full Changelog](https://github.com/danielo515/tiddlypouch/compare/v0.14.2+2...v0.14.3)
- Deletions are now synced
- Added a Logger module
  - Allows to control the verbosity level
    - Log: normal information
    - Debug: Only if debug mode is active
    - Trace: only if verbose mode is active
## [v0.14.2+2](https://github.com/danielo515/tiddlypouch/tree/v0.14.2+2) (2016-09-03)
[Full Changelog](https://github.com/danielo515/tiddlypouch/compare/v0.14.2...v0.14.2+2)

## [v0.14.2](https://github.com/danielo515/tiddlypouch/tree/v0.14.2) (2016-09-03)
[Full Changelog](https://github.com/danielo515/tiddlypouch/compare/v0.11.3...v0.14.2)
- Implemented class for single individual databases configuration
- DefaultTiddlers is loaded at startup along with StoryList
- Sync adaptor method get-skinny-tiddlers now supports both promise flow and callbacks
- Dowload saver that downloads all the tiddlers contained on the current db as JSON
# 0.14.1
- Revisions are validated before saving 
# 0.14
- First version of module loader
# 0.13
- Better ui for revision handling
  - See revisions as tabs of the current tiddler
  - Open several previous revisions to check them all
  - Revisions names are shorted for readability
 - pixel perfect revisions tabs
# 0.12.1
- Set the database name as subtitle
  - Click on it to open the control panel on the database selection tab
- Fixed navigate to tab to display plain text inside the link (avoid wikification)
# 0.12
- Basic revision handling
  - Get **all** revisions of a tiddler method
  - Get revision of a tiddler
  - Ui to show and reload revisions of a tiddler
# 0.11.4
- If a cookie exists, login the user automatically
- Fixed several issues related to update conflicts:
  - Cloning a tiddler (was trying to create a new document with an existing revision)
  - Renaming a tiddler
- Introduced upsert method (which allowed to solve above issues)
# 0.11.3
- More meaningful login message
# 0.11.2
- Plugin deactivation detection mechanism has been removed
  - It was obsolete. Instead we are now using the default tiddlywiki method for the home page
# 0.11.1
- Update ui when a different Database is selected
- Started to move selected database logic to a separate module
- Utils moved to a module
# 0.11
- Updates to UX when saving config
  - On config update user is asked to reload the window
  - Better ui to select one of the existing databases
  - Macro to navigate directly to config tab
  - Button tiddler to save Database config
  - Clearer Getting started tid
- Removed old control panel `server`
- Check if there is URL configured before check login status
- Fixed promise chaining on config init

\* *This Change Log was automatically generated by [github_changelog_generator](https://github.com/skywinder/Github-Changelog-Generator)*