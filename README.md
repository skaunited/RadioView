# SwiftUI Radio View Button Demo

This is a demo app showcasing how to use radio view buttons in SwiftUI. The buttons support `onTapGesture` and `withAnimation` for a smooth user experience.

![https://github.com/skaunited/RadioView/blob/main/Demo/radio.gif](demo.gif)

## Requirements

- Swift 5.8
- iOS 16.4
- Xcode 14.3

## How to Use

1. Clone or download the project to your local machine.
2. Open the project in Xcode 14.3 or later.
3. Run the app on an iOS 16.4 or later device or simulator.

## Features

- Multiple radio view buttons with custom colors and sizes.
- Smooth animation when selecting a new option.
- Ability to select and deselect options.

## Implementation Details

The radio view buttons are implemented using SwiftUI's `View` protocol and the `@State` property wrapper. Each button is a `ZStack` containing a circle shape, with a smaller circle shape inside to represent the selected state. When a button is tapped, the selected state is updated using the `@State` property wrapper and the animation is triggered using `withAnimation`.

## Credits

This demo was created by [Your Name Here] and uses [OpenMoji](https://openmoji.org/) icons for the radio button shapes.

## License

This demo is available under the MIT license. See the [LICENSE](LICENSE) file for more info.
