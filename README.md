### :desktop_computer:   Xcode by <kbd>ELY</kbd>

## Theme

#### Save **CyberPunk.xccolortheme** file in xcode themes folder: #### 

```
~/Library/Developer/Xcode/UserData/
```

#### Select or add CyberPunk theme in **Xcode > Preferences > Fonts & Colors** #### 

![CyberPunkThemeImage](/CyberPunkThemeImage.png)

## Key Bindings

#### Replace file or add individual key bindings into IDETextKeyBindingSet.plist

```
Finder with <kbd>COMMAND</kbd> + <kbd>SHIFT</kbd> + <kbd>G</kbd>
```

```
/Applications/Xcode.app/Contents/Frameworks/IDEKit.framework/Versions/A/Resources/
```

- Duplicate Current Lines Down <kbd>COMMAND</kbd> + <kbd>D</kbd>
  
```xml  
<key>Duplicate Current Lines Down</key>
<string>selectParagraph:, delete:, yank:, moveToBeginningOfParagraph:, yank:, moveUp:, moveToEndOfParagraph:</string>
```

- Delete Current Line <kbd>COMMAND</kbd> + <kbd>DELETE</kbd>

```xml  
<key>Delete Current Line</key>
<string>deleteToBeginningOfLine:, moveToEndOfLine:, deleteToBeginningOfLine:, deleteBackward:, moveDown:,moveToBeginningOfLine:</string>
```
