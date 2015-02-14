# ARAlertController

[![Twitter](http://img.shields.io/badge/contact-@alexruperez-blue.svg?style=flat)](http://twitter.com/alexruperez)
[![GitHub Issues](http://img.shields.io/github/issues/alexruperez/ARAlertController.svg?style=flat)](http://github.com/alexruperez/ARAlertController/issues)
[![CI Status](http://img.shields.io/travis/alexruperez/ARAlertController.svg?style=flat)](https://travis-ci.org/alexruperez/ARAlertController)
[![Version](https://img.shields.io/cocoapods/v/ARAlertController.svg?style=flat)](http://cocoadocs.org/docsets/ARAlertController)
[![License](https://img.shields.io/cocoapods/l/ARAlertController.svg?style=flat)](http://cocoadocs.org/docsets/ARAlertController)
[![Platform](https://img.shields.io/cocoapods/p/ARAlertController.svg?style=flat)](http://cocoadocs.org/docsets/ARAlertController)
[![Analytics](https://ga-beacon.appspot.com/UA-55329295-1/ARAlertController/readme?pixel)](https://github.com/igrigorik/ga-beacon)

## Overview

UIAlertController compatible iOS >= 5.0

![ARAlertController Screenshot](https://www.service2media.com/wp-content/uploads/2014/08/UIAlertControl.png)

## Usage

### Installation

ARAlertController is available through [CocoaPods](http://cocoapods.org). To install
it, simply add the following line to your Podfile:

    pod 'ARAlertController'

#### Or you can add the following files to your project:
* `ARAlertController.m`
* `ARAlertController.h`

### Example

```objectivec
self.alert = [ARAlertController alertControllerWithTitle:@"My Alert" message:@"This is an alert." preferredStyle:ARAlertControllerStyleAlert];

ARAlertAction* defaultAction = [ARAlertAction actionWithTitle:@"OK" style:ARAlertActionStyleDefault handler:^(ARAlertAction * action) {}];

[self.alert addAction:defaultAction];

[self.alert presentInViewController:self animated:YES completion:nil];
```

# Etc.

* Contributions are very welcome.
* Attribution is appreciated (let's spread the word!), but not mandatory.

## Use it? Love/hate it?

Tweet the author [@alexruperez](http://twitter.com/alexruperez), and check out alexruperez's blog: http://alexruperez.com

## License

ARAlertController is available under the MIT license. See the LICENSE file for more info.