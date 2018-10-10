<h1 align="center"> Success and Error Status </h1>
<p align="center">
<img src="https://img.shields.io/badge/Swift-4.0-orange.svg" alt="Swift 4.0"/>
<img src="https://img.shields.io/badge/platform-iOS-brightgreen.svg" alt="Platform: iOS"/>
<img src="https://img.shields.io/badge/Xcode-9%2B-brightgreen.svg" alt="XCode 9+"/>
<img src="https://img.shields.io/badge/iOS-11%2B-brightgreen.svg" alt="iOS 11"/>
<img src="https://img.shields.io/badge/licence-MIT-lightgray.svg" alt="Licence MIT"/>
</a>
</p>

A modal status view which look and feel like Xcode build succeeded status view. Very simple to use and customise.


### Features
- [x] Look and feel like Xcode Build Succeeded status with appearance animation.
- [x] Easy presentation.
- [x] Automatic disappearance.
- [x] Swift 4+.

<div align = "center">
<img src="Success.jpg"/>
<img src="Error.jpg"/>
</div>

## Usage

- To Present

```swift
// default success status
ModalStatusPresenter.presentStatus()
// or for more options
ModalStatusPresenter.presentStatus(frame: CGRect, title: String, type: StatusType, signColor: CGColor, textColor: UIColor)
```
## Installing

#### Manually

Download and add `ModalStatus.swift` file in your project. 
Or create a new file in your project and paste the code of `ModalStatus.swift`.

## Requirements

* Swift 4+
* iOS 11 or higher

## Authors

* **Jahid Hasan Polash** -  [jahid-hasan-polash](https://github.com/jahid-hasan-polash)

## Communication

* If you **found a bug**, open an issue.
* If you **have a feature request**, open an issue.
* If you **want to contribute**, submit a pull request.

## License

This project is licensed under the MIT License.
