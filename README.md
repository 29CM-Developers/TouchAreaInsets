# fork 배경

- 29CM iOS 앱에서 사용하고 있는 라이브러리로, SPM 지원이 되지 않아 fork 후 별도로 SPM 지원을 추가했습니다.

---

# TouchAreaInsets

[![Build Status](https://travis-ci.org/devxoul/TouchAreaInsets.svg?branch=master)](https://travis-ci.org/devxoul/TouchAreaInsets)
[![CocoaPods](http://img.shields.io/cocoapods/v/TouchAreaInsets.svg)](https://cocoapods.org/pods/TouchAreaInsets)

Touch area insets for UIView.

## At a Glance

The code below expands button's touch area for 20px.

```swift
let button = UIButton()
button.touchAreaInsets = UIEdgesInsets(top: 20, left: 20, bottom: 20, right: 20)
```

## Installation

```ruby
pod 'TouchAreaInsets'
```

## License

TouchAreaInsets is under MIT license. See the [LICENSE](LICENSE) file for more info.
