# DisplayValueCommon Library

## Overview
The `DisplayValueCommon` is a generic interface that defines the basic structure for display devices in an embedded system. It is intended to be extended by specific display libraries that implement the actual behavior of each method.

## Features
- Defines the basic methods for a display (`init()`, `clear()`, `setLabel()`, `updateValue()`).
- Provides a common interface for developing display libraries.

## Methods
- `init()`: Initializes the display hardware.
- `clear()`: Clears the display screen.
- `setLabel(const String& label)`: Sets the display label, usually shown on the first line.
- `updateValue(const String& value)`: Updates the value shown on the display.

## Usage
This is an abstract interface and cannot be used directly. It should be implemented by specific display classes like `DisplayValueLCD`, `DisplayValueOLED`, etc.

## License
This library is open source, distributed under the MIT License.