# Under development. Should be done by Christmas!

![Header Image](GitHub/Assets/Header.png)

# Popovers

A library to present popovers.
- Present **any** view above your app's main content.
- Attach to source views or use picture-in-picture positioning.
- Supports multiple popovers at the same time with smooth transitions.
- Popovers are interactive and can be dragged to different positions.
- Highly customizable API that's super simple — just add `.popover`.
- Written in SwiftUI with full SwiftUI and UIKit support.

## Showroom


<table>

<tr>
<td>
Alert   
</td>
<td>
Color  
</td>
<td>
Menu   
</td>
<td>
Tip      
</td>
<td>
Standard 
</td>
</tr>

<tr>
</tr>
  
<tr>
<td>
<img src="GitHub/Assets/GIFs/Alert.gif" alt="Alert">
</td>
<td>
<img src="GitHub/Assets/GIFs/Color.gif" alt="Color">
</td>
<td>
<img src="GitHub/Assets/GIFs/Menu.gif" alt="Menu">
</td>
<td>
<img src="GitHub/Assets/GIFs/Tip.gif" alt="Tip">
</td>
<td>
<img src="GitHub/Assets/GIFs/Standard.gif" alt="Standard">
</td>
</tr>

<tr>
</tr>
  
<tr>
<td colspan=2>
Tutorial
</td>
<td colspan=2>
Picture-in-Picture
</td>
<td>
Notification
</td>
</tr>
  
<tr>
</tr>
  
<tr>
<td colspan=2>
<img src="GitHub/Assets/GIFs/Tutorial.gif" alt="Tutorial">
</td>
<td colspan=2>
<img src="GitHub/Assets/GIFs/PIP.gif" alt="Picture in Picture">
</td>
<td>
<img src="GitHub/Assets/GIFs/Notification.gif" alt="Notification">
</td>
</tr>

</table>

## Example
The example app was written in Swift Playgrounds 4, so you can run it right on your iPad. If you're using a Mac, download the Xcode version. [Download for Swift Playgrounds 4](https://github.com/aheze/Popovers/raw/main/Examples/PopoversPlaygroundApp.swiftpm.zip) • [Download for Xcode](https://github.com/aheze/Popovers/raw/main/Examples/PopoversXcodeApp.zip)

![Example app](GitHub/Assets/ExampleApp.png)

## Installation
Popovers can be installed through the Swift Package Manager (preferred) or Cocoapods.

<table>
<tr>
<td>
<strong>
Swift Package Manager
</strong>
<br>
Add the Swift Package URL:
</td>
<td>
<strong>
Cocoapods
</strong>
<br>
Add this to your Podfile:
</td>
</tr>
  
<tr>
<td>
<br>

```
https://github.com/aheze/Popovers
```
</td>
<td>
<br>

```
pod 'Popovers'
```
</td>
</tr>
</table>



## Usage
First:
```
import Popovers
```
Then you can use either SwiftUI or UIKit.


## Customization
Customize popovers through the `attributes` struct.

## License
Popovers is made by [aheze](https://github.com/aheze). Use it however you want.
```
MIT License

Copyright (c) 2022 A. Zheng

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

