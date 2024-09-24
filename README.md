<!-- markdownlint-disable MD033 MD041 -->
<div align="center">

# Custom SF Symbols

</div>

This repository contains a *(slowly growing)* collection of custom SF Symbols designed for use in iOS, iPadOS, and macOS applications.

## Getting Started

### Prerequisites

To use these custom symbols, you'll need:

- Xcode 12 or later
- iOS 14, iPadOS 14, or macOS Big Sur (or later versions) for support of SF Symbols

## Usage

1. Drag the `.svg` into your Asset Catalog

1. Reference it like any other SF Symbol. For example, using SwiftUI:

    ```swift
    Image("custom-symbol-name")
      .symbolRenderingMode(.multicolor)
    ```

## Contributing

Feel free to open a pull request if you'd like to contribute your own symbol. Please ensure that your symbols follow the SF Symbols design guidelines for consistency.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
