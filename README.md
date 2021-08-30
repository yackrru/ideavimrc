# ideavimrc
Personal .ideavimrc settings

## Prerequirements
- Plugins
  - [IdeaVim](https://plugins.jetbrains.com/plugin/164-ideavim/)
  - [IdeaVim-EasyMotion](https://plugins.jetbrains.com/plugin/13360-ideavim-easymotion/)
  - [AceJump](https://plugins.jetbrains.com/plugin/7086-acejump/)

## Standard

## Custom

## [NERDTree](https://github.com/JetBrains/ideavim/wiki/NERDTree-support)
### Key binding
Vim key binding with focus on source code window.
|Key|Description|Map setting|State|
|:---|:---|:---|:---|
|<C-t>|Open source tree and will focus that|`:NERDTree`|Closed source tree|
|<C-t>|Focus source tree|`:NERDTree`|Opened source tree|
|<C-c>|Close source tree|`:NERDTreeClose`|Opened source tree|
### NERDTree command
Typical NERDTree key binding with focus on source tree.
|Key|Description|
|:---|:---|
|o (or return)|Open file or directory|
|i|Open file with splitting window horizontally|
|s|Open file with splitting window vertically|
|O|Open directories recursively|
|x|Close directories under focusing file or directory|
