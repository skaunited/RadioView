# SwiftUI Radio View Button Demo

This is a demo app showcasing how to use radio view buttons in SwiftUI. The buttons support `onTapGesture` and `withAnimation` for a smooth user experience.

<p align="center">
<img src= "https://github.com/skaunited/RadioView/blob/main/Demo/radio.gif" width="200" height="400" >
</p>

## Requirements

- Swift 5.8
- iOS 16.4
- Xcode 14.3

## Features

- Multiple radio view buttons with custom colors and sizes.
- Smooth animation when selecting a new option.
- Ability to select and deselect options.

## Implementation Details

The radio view buttons are implemented using SwiftUI's `View` protocol and the `@State` property wrapper. Each button is a `ZStack` containing a circle shape, with a smaller circle shape inside to represent the selected state. When a button is tapped, the selected state is updated using the `@State` property wrapper and the animation is triggered using `withAnimation`.

## Credits

This demo was created by Skander BAHRI .
