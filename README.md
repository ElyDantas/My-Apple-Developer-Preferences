### :desktop_computer:&nbsp; Xcode by <kbd>ELY</kbd>

## Theme

#### Save **CyberPunk.xccolortheme** file in xcode themes folder: #### 

```
~/Library/Developer/Xcode/UserData/FontAndColorThemes
```

#### Select or add CyberPunk theme in **Xcode > Preferences > Fonts & Colors** #### 

![CyberPunkThemeImage](/CyberPunkThemeImage.png)

## Key Bindings

Using **Finder** <kbd>COMMAND</kbd> + <kbd>SHIFT</kbd> + <kbd>G</kbd> search below path:

```
/Applications/Xcode.app/Contents/Frameworks/IDEKit.framework/Versions/A/Resources/
```

Replace file or add individual key bindings into ```IDETextKeyBindingSet.plist```

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

## Create @3x Image.workflow

Service made in automator to generate @3x, @2x, @1x from image with extension: **.jpg** or **.png**. Script replace " copy"(English) and "cópia de "(Portuguese) words.

Double click on **Create @3x Image.workflow** file to install in your system.

#### How to use it

1. Click right button on image file with size: 90x90 (px).
2. Choose Services → Create @3x
3. Result: 

> - image@3x.png 	(90x90 px)
> - image@2x.png 	(60x60 px)
> - image@1x.png 	(30x30 px)

## Matrix Screensaver

Awesome matrix screensaver. Just download and install: ```MatrixScreenSaver.saver.zip```

![alt-text](https://github.com/ElyDantas/Apple-Developer-Sugarry/blob/master/MatrixScreenSaver.gif?raw=true)
