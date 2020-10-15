# Inkdrop for Mobile - Release Notes

## v4.1.0
2020-10-15

g'day. Automn is coming! 🍁

### Improvements
* Faster launch speed
* Set status and tag based on current query context (Thanks [Shogo-san](https://forum.inkdrop.app/t/topic/2060))
  * When you are selecting a tag or status, new note will have the tag/status automatically.

### Markdown renderer updates
* mermaid now supports User journey diagram and Entity relationship diagrams

### Bugfix
* Pinned notes not listed at the top in tag and status groups (Thanks [Shimizu-san](https://forum.inkdrop.app/t/pin-to-top-not-working-with-tags-and-statuses/2078))

## v4.0.1
2020-09-03

### Bugfix
* Background note syncing not working on iOS

## v4.0.0
2020-09-01

### New features

* [Pin notes to top](https://forum.inkdrop.app/t/pin-notes-and-reminder/672) (Thanks Andi, Alec, Bastian and Adelbert)
* Support Workspace View
* Collapse/expand notebook on sidebar
* [Show sub-notebooks](https://forum.inkdrop.app/t/display-sub-notebooks-when-focussed-on-notebook/) in [notebook submenu](https://docs.inkdrop.app/manual/navigating-notes#notebook-submenu) (Thanks James and Jeremy)
* [Remember sort & order](https://forum.inkdrop.app/t/save-remember-sort-order-settings-per-notebook/315) of note list per view (all/notebook/tag/status/pins)
* Toggle task list item by tapping `[ ]` or `[x]`
* Zoom preview
* Refurbished icons

### Improvements
* Improve search result by having bigger weight for title field (Thanks [Zhuolun and James](https://forum.inkdrop.app/t/how-to-search-notes-by-the-title/1849))

### Bugfix
* List unindentation does not work properly

## v3.6.0
2020-02-28

### New features

* New syntax theme: material-dark-mod (Thanks [Otawara-san](https://forum.inkdrop.app/t/can-we-please-get-inkdrop-material-dark-mod-syntax-for-android/1737/5))
  ![Material Dark Mod](https://github.com/inkdropapp/version-history-mobile/blob/master/images/v3.6.0-material-dark-mod-syntax-theme.jpg?raw=true)
  * You can change syntax theme from *Sidebar -> Preferences -> Themes -> Syntax Theme*
* (iOS) Support `inkdrop:` URL scheme to just open the app

### Bugfix

* Detect correct image MIME type
* [sequence-diagram] lighter background color for dark UI themes (Thanks [Peilun](https://forum.inkdrop.app/t/low-visibility-of-sequence-diagram-when-using-with-dark-ui-theme/1754/6))

## v3.5.0
2020-01-23

### New features

* Global search
* Advanced markdown renderer options (a.k.a. plugins for mobile)
  - breaks
  - embed
  - flowchart
  - markdown-emoji
  - math
  - mermaid
  - sequence-diagrams
  - toc

### Bugfix

* Tablet layout issue

## v3.4.0
2019-12-23

### New features

* Notebook submenu  
  ![notebook submenu](https://github.com/inkdropapp/version-history-mobile/blob/master/images/v3.4.0-notebook-submenu_2.png?raw=true)  
  ![notebook submenu](https://github.com/inkdropapp/version-history-mobile/blob/master/images/v3.4.0-notebook-submenu.png?raw=true)
  Tap ">" button on the right of a notebook item on the sidebar.
  The submenu lists statuses and tags that are associated with notes in the selected notebook.
  You can learn more about [Notebook submenu here](https://docs.inkdrop.app/manual/navigating-notes).
* Revision history  
  ![Revision history 1](https://github.com/inkdropapp/version-history-mobile/blob/master/images/v3.4.0-revision-history_1.png?raw=true)  
  ![Revision history 2](https://github.com/inkdropapp/version-history-mobile/blob/master/images/v3.4.0-revision-history_2.png?raw=true)  
  ![Revision history 3](https://github.com/inkdropapp/version-history-mobile/blob/master/images/v3.4.0-revision-history_3.png?raw=true)  
  ![Revision history 4](https://github.com/inkdropapp/version-history-mobile/blob/master/images/v3.4.0-revision-history_4.png?raw=true)  
  You can restore an old note revision stored in your device locally.
  Lean more about [revision history here](https://docs.inkdrop.app/manual/revision-history).
* Math support  
  ![Math support in preview](https://github.com/inkdropapp/version-history-mobile/blob/master/images/v3.4.0-math-support.png?raw=true)  
  Built-in [math plugin](https://my.inkdrop.app/plugins/math).
* Auto-backup for editing note  
  You can restore the last edit when the app crashed.

### Improvement

* Show the editor when created new note
* Show error message when failed to load notes

## v3.3.2
2019-10-24

### Bugfix

* Inserting images not working

## v3.3.1
2019-10-23

### Bugfix

* Toggling checkboxes not working (Thanks Shota-san)

## v3.3.0
2019-10-18

### New features

* Selecting multiple notes
* Highlighting tables and codeblocks in the editor
* Long-press the note list item to show the note information screen
* Duplicating notes (Thanks [James](https://forum.inkdrop.app/t/allow-one-to-duplicate-a-document-on-ios/1393))

### Improvements

* Better UI performance
* Faster full-text search
* Better UI performance on side bar
* Support deleting the local db and syncing from scrach
* Support dark theme for editor toolbar

### Bugfix

* Some memory leaks in data sync
* Flashy modal screens
* Cursor won't place correctly when scrolled down in your note (Thanks Sceptic)
* Settings screen not working properly (Thanks Otawara-san)
* Editor not updating when the note is updated via sync
* Revert changes regarding checkpointers of data sync which might have been causing that some notes won't be synced in some cases
* Avoid updating mde while composing CJK
* Avoid unnecessary re-renderings for error boundary
* (Android) Removing lines won't work properly (Thanks [Y_Ho](https://forum.inkdrop.app/t/cant-remove-text-in-android-app/1606))

## v3.2.0
2019-09-03

NOTE: This version is released on Android only.

* **Improvement**: Finally support Gboard

Thank you so much you guys who helped me fix the issues on Gboard!!

## v3.1.0
2019-07-07

* **Bugfix**: Syncing with Android not working in some cases
* **Bugfix**: Sort order is not properly preserved when loading more items on note list bar
* **Bugfix**: Trigger indexing FTS when sync finished

## v3.0.0
2019-06-05

* **New feature**: End-to-end encryption support
* **Improvement**: New app icon
* **Improvement**: Sync notes in background
* **Improvement**: Great performance improvement on full-text search
* **Improvement**: Cleaner search bar
* **Bugfix**: Emptying trash not working

## v2.4.3
2019-01-11

* **Chore**: Fix internal compatibility check
* **Chore**: Update domain

## v2.4.2
2018-12-14

* **Bugfix**: The app is stuck on white screen after logging in in some case (Thanks Otawara-san)

## v2.4.1
2018-11-29

* **Bugfix**: Table align doesn't work
* **Bugfix**: Trashed notes with status are shown in the note list of status columns (Thanks Ikeda-san)
* **Bugfix**: Sync status view is distractive on tablets

## v2.4.0
2018-11-14

* **New feature**: Inline HTML support
* **Bugfix**: Cursor jumps to invalid position when got focus at the bottom of the note
* **Bugfix**: The editor is unloaded when the app resumed from background (Thanks Takeuchi-san)

## v2.3.1
2018-11-07

* **Bugfix**: The editor unexpectedly scrolls up when auto-save (Thanks Yoshioka-san and Otawara-san)
* **Bugfix**: Image widgets become invisible when editing note got synced

## v2.3.0
2018-11-04

* **New Feature**: Support changing editor font family (Thanks [Kurt](https://forum.inkdrop.info/t/ios-app-font/790))
* **Improvement**: [Android] Support enabling Gboard (Experimental) (Thanks [David](https://forum.inkdrop.info/t/android-version-disables-glide-typing-on-google-keyboard/644))
* **Improvement**: Auto-save after 5 seconds
* **Improvement**: Fix CJK input problem
* **Improvement**: Scroll to cursor position on focus (Thanks Otawara-san)

## v2.2.1
2018-10-09

* **Improvement**: [iOS] Support 6.5" Display
* **Bugfix**: [iOS] Fix a bug where note conflicts often occur on iPad

## v2.2.0
2018-08-23

* **Bugfix**: Resolve sync issue that edited note sometimes unexpectedly got lost
* **Improvement**: Make a copy of a note when detected an update conflict
* **Improvement**: Update note list immediately after saving editing note (Thanks Sceptic)

## v2.1.0
2018-08-13

* **New feature**: Task progress view
* **New feature**: Show invisible characters (Thanks Sceptic)
* **Bugfix**: Fixed a problem syncing currently editing note

## v2.0.0
2018-07-04

* **New feature**: Built from scratch! Read [this blogpost](https://blog.inkdrop.info/inkdrop-mobile-v2-has-been-released-4b0b69bba7f0) to learn more.
