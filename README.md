# Flutter Analog Clock

Clean and fully customizable analog clock widget.

## Installation

In your pubspec.yaml file within your Flutter Project:

   ```
   dependencies:
  analog_clock: ^0.1.0
   ```

## Features

1. Modern and clean analog clock interface.

2. Fully customizable.

3. Live clock.

4. Custom datetime.

## Usage

   ```
   import 'package:analog_clock/analog_clock.dart';


AnalogClock(
	decoration: BoxDecoration(
	    border: Border.all(width: 2.0, color: Colors.black),
	    color: Colors.transparent,
	    shape: BoxShape.circle),
	width: 150.0,
	isLive: true,
	hourHandColor: Colors.black,
	minuteHandColor: Colors.black,
	showSecondHand: false,
	numberColor: Colors.black87,
	showNumbers: true,
	showAllNumbers: false,
	textScaleFactor: 1.4,
	showTicks: false,
	showDigitalClock: false,
	datetime: DateTime(2019, 1, 1, 9, 12, 15),
	);
   ```
