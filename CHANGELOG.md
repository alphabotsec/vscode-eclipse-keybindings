# Change Log

## 0.16.1 (May 23, 2022)
* bug fix - remove previously introduced keybindings for ctrl+f (cmd+f) [#60](https://github.com/alphabotsec/vscode-eclipse-keybindings/issues/60).

## 0.16.0 (May 20, 2022)
* enhancement - ctrl+f (cmd+f) now opens the search and replace box. [#27](https://github.com/alphabotsec/vscode-eclipse-keybindings/issues/27).
* enhancement - ctrl+f3 (cmd+f3) open structure/outline [#52](https://github.com/alphabotsec/vscode-eclipse-keybindings/pull/52).
* enhancement - ctrl+{ (cmd+{) split editor (does not work on all keyboard layouts) [#53](https://github.com/alphabotsec/vscode-eclipse-keybindings/pull/53).
* enhancement - alt+shift+t (alt+cmd+t) show refactor menu [#54](https://github.com/alphabotsec/vscode-eclipse-keybindings/pull/54).
* enhancement - alt+shift+s (alt+cmd+s) show source action menu [#55](https://github.com/alphabotsec/vscode-eclipse-keybindings/pull/55).
* enhancement - f11 (cmd+f11) debug start [#56](https://github.com/alphabotsec/vscode-eclipse-keybindings/pull/56).
* enhancement - alt+shift+up expand selection (does not work on macOS) [#57](https://github.com/alphabotsec/vscode-eclipse-keybindings/pull/57).
* bug fix - ctrl+f11 (cmd+shift+f11) fix run [#56](https://github.com/alphabotsec/vscode-eclipse-keybindings/pull/56).

## 0.14.0 (July 4, 2021)
* enhancement - added ctrl+q last edit location. [#40](https://github.com/alphabotsec/vscode-eclipse-keybindings/pull/40).
* enhancement - added ctrl+alt+h call hierarchy. [#41](https://github.com/alphabotsec/vscode-eclipse-keybindings/pull/41).
* enhancement - added f4 type hierarchy. [#43](https://github.com/alphabotsec/vscode-eclipse-keybindings/pull/43).
* enhancement - added alt+shift+v move... . [#44](https://github.com/alphabotsec/vscode-eclipse-keybindings/pull/44).
* enhancement - added alt+shift+m extract method. [#45](https://github.com/alphabotsec/vscode-eclipse-keybindings/pull/45).
* enhancement - added alt+shift+l extract local variable. [#46](https://github.com/alphabotsec/vscode-eclipse-keybindings/pull/46).

## 0.13.0 (April 1, 2021)
* enhancement - added shift+enter insert line below. [#27](https://github.com/alphabotsec/vscode-eclipse-keybindings/issues/37).
* enhancement - added ctrl+f7 focus next part. [#36](https://github.com/alphabotsec/vscode-eclipse-keybindings/issues/36).
* enhancement - added ctrl+shift+f7 focus previous part. [#36](https://github.com/alphabotsec/vscode-eclipse-keybindings/issues/36).
* bug fix - fix find in files. [#38](https://github.com/alphabotsec/vscode-eclipse-keybindings/issues/38).

## 0.12.0 (May 1, 2020)
* enhancement - added ctrl+7 comment lines. [#25](https://github.com/alphabotsec/vscode-eclipse-keybindings/issues/25).
* enhancement - better command for ctrl+e open active editor list. [#31](https://github.com/alphabotsec/vscode-eclipse-keybindings/pull/31).
* enhancement - also support copy lines up/down on Ubuntu. [#28](https://github.com/alphabotsec/vscode-eclipse-keybindings/issues/28).

## 0.10.0 (November 20, 2018)
* enhancement - added shift+alt+y toggle wordwrap.
* enhancement - added ctrl+left/right jump one word to the left/right.
* enhancement - added ctrl+shift+left/right expand selection to left/right word.

## 0.9.8 (July 14, 2018)
* enhancement - added ctrl+shift+o organize imports.

## 0.9.7 (May 1, 2018)
* enhancement - added ctrl+. go to next problem. See [#12](https://github.com/alphabotsec/vscode-eclipse-keybindings/issues/12).
* enhancement - added ctrl+alt+t toggle integrated terminal.

## 0.9.6 (July 5, 2017)
* bug fix - on macOS start/debugging should be cmd+shift+f11.
* enhancement - added f12 focus active editor.
* enhancement - added ctrl+shift+f4 close all editors.
* enhancement - added ctrl+shift+delete delete to end of line. See [#10](https://github.com/alphabotsec/vscode-eclipse-keybindings/issues/10).

## 0.9.5 (June 7, 2017)
* bug fix - on macOS navigate back should be cmd+alt+left. See [#8](https://github.com/alphabotsec/vscode-eclipse-keybindings/issues/8).
* bug fix - on macOS navigate forward should be cmd+alt+right. See [#8](https://github.com/alphabotsec/vscode-eclipse-keybindings/issues/8).

## 0.9.4 (May 25, 2017)
* enhancement - added alt+left navigate back. See [#7](https://github.com/alphabotsec/vscode-eclipse-keybindings/pull/7).
* enhancement - added alt+right navigate forward. See [#7](https://github.com/alphabotsec/vscode-eclipse-keybindings/pull/7).

## 0.9.3 (March 29, 2017)
* enhancement - added ctrl+k next selection. See [#5](https://github.com/alphabotsec/vscode-eclipse-keybindings/issues/5).
* enhancement - added ctrl+shift+k previous selection. See [#5](https://github.com/alphabotsec/vscode-eclipse-keybindings/issues/5).

## 0.9.2 (February 27, 2017)
* enhancement - added ctrl+shift+w close all editors. See [#3](https://github.com/alphabotsec/vscode-eclipse-keybindings/issues/3).
* enhancement - added ctrl+shift+c comment line. See [#3](https://github.com/alphabotsec/vscode-eclipse-keybindings/issues/3).
* enhancement - added ctrl+alt+j join lines. See [#3](https://github.com/alphabotsec/vscode-eclipse-keybindings/issues/3).
* enhancement - added ctrl+m toggle sidebar. See [#3](https://github.com/alphabotsec/vscode-eclipse-keybindings/issues/3).
* enhancement - added ctrl+e open previously used editor. See [#3](https://github.com/alphabotsec/vscode-eclipse-keybindings/issues/3).

## 0.9.1 (February 16, 2017)
* bug fix - Rename/Refactor on macOS same as in Eclipse on macOS (cmd+alt+r)
* enhancement - Document code format when text is not selected. See [#2](https://github.com/alphabotsec/vscode-eclipse-keybindings/issues/2).

## 0.9.0 (January 3, 2017)
* bug fix - ctrl+shift+s and ctrl+alt+s are swapped. See [#1](https://github.com/alphabotsec/vscode-eclipse-keybindings/issues/1).
* enhancement - added ctrl+{ split editor 
* enhancement - added ctrl+shift+x transform to upper case
* enhancement - added ctrl+shift+y transform to lower case

## 0.8.0 (November 3, 2016)
Initial version
