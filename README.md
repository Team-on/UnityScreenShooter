# ScreenShooter
Screenshot utility for Unity runtime &amp; editor


## Description
'ScreenShooter' is an asset that can capture screenshot sequences in editor. You can configurate size, Game/Editor view and UI for screenshots.
Integrated with [Polyglot Tool](https://assetstore.unity.com/packages/tools/gui/polyglot-tool-131560?_ga=2.85337567.750031523.1612646196-741310434.1607024629) to capture screenshots with all avaliabled languages. Can work without *Polyglot* too.  
Also provide API to capture screenshots runtime  

![1](https://user-images.githubusercontent.com/30273693/107130626-19341380-68d8-11eb-9160-3cb5772e1725.png)  
![2](https://user-images.githubusercontent.com/30273693/107130628-1afdd700-68d8-11eb-9555-0f3c3955cdc8.png)


## Installation
### (For Unity 2018.3 or later) Using OpenUPM  
This package is available on [OpenUPM](https://openupm.com).  
You can install it via [openupm-cli](https://github.com/openupm/openupm-cli).  
```
openupm add com.teamon.screenshooter
```

### (For Unity 2018.3 or later) Using Git
Find the manifest.json file in the Packages folder of your project and add a line to `dependencies` field.
* Major version: ![](https://img.shields.io/github/v/release/mob-sakai/SubAssetEditor)  
`"com.coffee.sub-asset-editor": "https://github.com/eam-on/UnityScreenShooter.git"`
Or, use [UpmGitExtension](https://github.com/mob-sakai/UpmGitExtension) to install and update the package.

#### For Unity 2018.2 or earlier
1. Download a source code zip this page
2. Extract it
3. Import it into the following directory in your Unity project
   - `Packages` (It works as an embedded package. For Unity 2018.1 or later)
   - `Assets` (Legacy way. For Unity 2017.1 or later)
   
#### From Unity Asset Store
1. https://assetstore.unity.com/packages/slug/188939
2. Add it to project as usual


## Usage
1. From the menu, click `Window > Screen shooter(Alt + S)`.
2. Configurate sequences
3. Enjoy!
