# Inkdrop for Mobile - Release Notes

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
