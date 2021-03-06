# Curated List of Resources for iOS Devs

A list of all the things that make iOS developers happy

## Development 

### iOS-independent

* gitignore [templates for xcode projects](https://github.com/github/gitignore/blob/master/Global/Xcode.gitignore) and [for all other projects](https://github.com/github/gitignore)

### About iOS

* [What's new in iOS](https://developer.apple.com/library/prerelease/content/releasenotes/General/WhatsNewIniOS): Detailed release notes and upgrade informations for developers about iOS versions.
* [iOS Version distribution chart](https://developer.apple.com/support/app-store/): See what percentage are using the latest and legacy iOS versions.

### News, tutorials, podcasts

* [iOS Dev Weekly](https://iosdevweekly.com) Weekly newsletter / blog post with a dozen or so curated links on different aspects of iOS technology and development. Also job postings.
* http://raywenderlich.com

### Source Code & Documentation

* [Swift Style Guide from Ray Wenderlich](https://github.com/raywenderlich/swift-style-guide): extensive, sensible style guide for swift
* [jazzy](https://github.com/realm/jazzy): generates documentation from source code

### Development Tools

* [fastlane](https://github.com/fastlane/fastlane): the missing build tool for iOS (and macOS), with a ruby DSL.  Also creates push & app certs, prov. profiles, uploads to TestFlight
* http proxy for intercepting traffic
** [Charles Proxy](https://www.charlesproxy.com/) proxy with GUI for observing, capturing and on-the-fly- changing of network traffic (from / to an app on a real device / simulator)
** [mitmproxy](https://mitmproxy.org/) command line proxy tool for observing, capturing and on-the-fly- changing of network traffic (from / to an app on a real device / simulator)
* http client for API testing
** [Paw](https://paw.cloud) is a very powerfull paid http client which comes as a native mac app and supports many importers (Swagger!)
** [Postman](https://www.getpostman.com) a http client for testing API calls. started out as a chrome extension.

#### Image optimization

* Google [guetzli](https://github.com/google/guetzli). Optimizes JPG/PNG for size and quality with [butteraugli](https://github.com/google/butteraugli) `guetzli --quality 84 in.jpg out.jpg`

### Continouos Integration

* [Jenkins CI](https://jenkins.io): Open Source continuous integration server
* [bitrise.io](https://www.bitrise.io/): Continuous integration as a Service for iOS / macOS projects

### Code signing

* [codesigning.guide](https://codesigning.guide) a clean and simple approach on creating, maintaining and storing signing certificates and prov. profiles

## Testing

### Beta distribution

* Apple TestFlight. No UDIDs required. Processing of IPAs :(. Internal testing easy to set up, external testing requires beta app review (faster than normal App Review)
* Fabric Beta. Requires collecting UDIDs. No IPA-processing, no beta-review.

* [Instructions for non-devs how to find out a devices UDID](http://whatsmyudid.com)

### Crowd-Testing providers

* Applause
* Testbirds

## Libraries

* RxSwift & RxCocoa

### Network 

* AlamoFire
* ObjectMapper for mapping json to Swift objects

### Image 
* [TOCropViewController](https://github.com/TimOliver/TOCropViewController) view controller for cropping, resizing and rotating images in a very fancy and easy way

## UI/UX

* [Ultimate Guide To iPhone Resolutions](https://www.paintcodeapp.com/news/ultimate-guide-to-iphone-resolutions) - Overview of Screen Sizes and Resolutions of iOS Devices 

* [HexPreview](http://hexpreview.com) Full-Screen hex color value preview 
