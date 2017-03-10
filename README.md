#Awesome Xamarin

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

# About
A curated list of awesome Xamarin ports, bindings, tutorials and much more!
The list is divided into categories such as Frameworks, Components, Testing and others, open source projects, free and paid services. There is no pre-established order of items in each category, the order is for contribution. If you want to contribute, please read the [guide](https://github.com/MarcBruins/awesome-xamarin/blob/master/CONTRIBUTING.md).


# How to Use
Awesome-Xamarin is an amazing list for people who need a certain feature on their app, so the best ways to use are:
- Ask for help on our [Twitter](https://twitter.com/marcbruins)
- Simply press <kbd>command</kbd> + <kbd>F</kbd> to search for a keyword
- Go through our *Content Menu*

## Content
- [About](#about)
- [How to Use](#how-to-use)
- [Getting Started](#getting-started)
- [Library and Frameworks](#libraries-and-frameworks)
    - [Analytics](#analytics)
    - [Animation](#animation)
    - [Architecture](#architecture)
    - [Authentication](#authentication)
    - [Cache](#cache)
    - [Charts](#charts)
    - [Code Quality](#code-quality)
    - [Color](#color)
    - [Database](#database)
    - [Data Structures / Algorithms](#data-structures--algorithms)
    - [Date & Time](#date--time)
    - [EventBus](#eventbus)
    - [Files](#files)
    - [Games](#games)
    - [Gesture](#gesture)
    - [Graphics](#graphics)
    - [Hardware](#hardware)
        - [Bluetooth](#bluetooth)
        - [Camera](#camera)
        - [iBeacon](#ibeacon)
        - [Location](#location)
        - [Other Hardware](#other-hardware)
    - [Layout](#layout)
    - [Logging](#logging)
    - [Localization](#localization)
    - [Maps](#maps)
    - [Math](#math)
    - [Media](#media)
        - [Audio](#audio)
        - [GIF](#gif)
        - [Image](#image)
        - [Media Processing](#media-processing)
        - [PDF](#pdf)
        - [Streaming](#streaming)
        - [Video](#video)
    - [Messaging](#messaging)
    - [Networking](#networking)
    - [Notifications](#notifications)
        - [Push Notifications](#push-notifications)
            - [Push Notification Providers](#push-notification-providers)
    - [Parsing](#parsing)
        - [CSV](#csv)
        - [JSON](#json)
        - [HTML](#xml--html)
    - [Passbook](#passbook)
    - [Payments](#payments)
    - [Permissions](#permissions)
    - [Reactive Programming](#reactive-programming)
    - [Security](#security)
        - [Encryption](#encryption)
        - [Keychain](#keychain)
    - [Server](#server)
    - [Testing](#testing)
        - [TDD / BDD](#tdd--bdd)
        - [A/B Testing](#ab-testing)
        - [UI Testing](#ui-testing)
    - [UI](#ui)
        - [Activity Indicator](#activity-indicator)
        - [Alert View](#alerts)
        - [App Introduction](#app-introduction)
        - [Badge](#badge)
        - [Button](#button)
        - [Calendar](#calendar)
        - [Card View](#card-view)
        - [Form & Settings](#form--settings)
        - [Keyboard](#keyboard)
        - [Label](#label)
        - [Menu](#menu)
        - [Modal Transition](#modal-transition)
        - [Navigation Bar](#navigation-bar)
        - [PickerView](#pickerview)
        - [Popup](#popup)
        - [Pull to Refresh](#pull-to-refresh)
        - [Rating Stars](#rating-stars)
        - [ScrollView](#scrollview)
        - [Slider](#slider)
        - [Splash View](#splash-view)
        - [Stepper](#stepper)
        - [Switch](#switch)
        - [Tab Bar](#tab-bar)
        - [Table View / Collection View](#table-view--collection-view)
        - [Tag](#tag)
        - [TextField & TextView](#textfield--textview)
        - [Web View](#web--view)
    - [URL Scheme](#url-scheme)
    - [Utility](#utility)
    - [VR](#vr)
    - [Walkthrough / Intro / Tutorial](#walkthrough--intro--tutorial)
    - [Websocket](#websocket)
- [Project setup](#project-setup)
- [Dependency / Package Manager](#dependency--package-manager)
- [Tools](#tools)
- [Rapid Development](#rapid-development)
  - [Injection](#injection)
- [Deployment / Distribution](#deployment--distribution)
- [App Store](#app-store)
- [SDK](#sdk)
    - [Official](#official)
    - [Unofficial](#unofficial)
- [Xcode](#xcode)
    - [Plugins](#plugins)
    - [Themes](#themes)
    - [Other Xcode](#other-xcode)
- [Reference](#reference)
- [Style Guides](#style-guides)
- [Good Websites](#good-websites)
    - [News, Blogs and more](#news-blogs-and-more)
    - [UIKit references](#uikit-references)
    - [Forums and discuss lists](#forums-and-discuss-lists)
    - [Tutorials and Keynotes](#tutorials-and-keynotes)
    - [Prototyping](#prototyping)
    - [Newsletters](#newsletters)
    - [Medium](#medium)
- [Social Media](#social-media)
  - [Twitter](#twitter)
  - [Facebook Groups](#facebook-groups)
- [Podcasts](#podcasts)
- [Books](#books)
- [Other Awesome Lists](#other-awesome-lists)
- [Contributing](#contributing-and-license)

***
# Getting Started
* [Start Developing with Xamarin](https://developer.xamarin.com/guides/cross-platform/getting_started/) - Official Xamarin. :large_orange_diamond:

# Libraries And Frameworks

## Analytics
* [Google Analytics](https://www.google.nl/intl/nl/analytics/) - Google analytics platform. ![android][android]![ios][ios]![windows][windows] 
* [Firebase](https://firebase.google.com/) - Analytics and much more. ![android][android]![ios][ios]![windows][windows] 
* [Hockeyapp](https://www.hockeyapp.net/) - Analytics and crash reporting ![android][android]![ios][ios]![windows][windows]
- [Raygun](https://raygun.com/) - Crash reporting and real user monitoring. ![android][android]![ios][ios]![windows][windows]

## Animation
* [Xamarin.Animations](https://github.com/aloisdeniel/Xamarin.Animations) - Libraries tends to make view animation easier for common scenarios like fade or scale entrance animations. ![android][android]![ios][ios]![windows][windows]
* [Facebook Pop](https://components.xamarin.com/view/Facebook.Pop) - Pop is an open-source animation engine behind the Facebook Paper's smooth animations and transitions. Using dynamic instead of traditional static animations, Pop drives the scrolling, bouncing, and unfolding effects that bring Paper to life. ![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/ios.png)
* [DCAnimationKit](https://github.com/markjackmilian/Xam.DCAnimationKit) - A collection of animations for Xamarin iOS ![ios][ios]
* [Lottie](https://github.com/martijn00/LottieXamarin) - Library that renders After Effects animations in real time, and allows apps to use animations as easily as they use static assets. Lottie uses animation data exported as JSON files from an open-source After Effects extension called [Bodymovin](https://github.com/bodymovin/bodymovin). ![android][android]![ios][ios]


## Architecture
* [MvvmCross](https://mvvmcross.com) - Extensive MVVM framework with plugins. ![android][android]![ios][ios]![windows][windows]
* [MVVM Light](http://www.mvvmlight.net) - Lightweight MVVM framework. ![android][android]![ios][ios]![windows][windows]
* [Prism](https://github.com/PrismLibrary/Prism) - Framework for building loosely coupled, maintainable, and testable XAML applications in WPF, Windows 10 UWP, and Xamarin Forms
* [Caliburn Micro](http://caliburnmicro.com/) - A small, yet powerful framework, designed for building applications across all XAML platforms. Full support for Xamarin.Forms and allows for reuse of ViewModels with Xamarin.Android and Xamarin.iOS projects (more support will be added in future releases). 
* [FreshMvvm](https://github.com/rid00z/FreshMvvm) - FreshMvvm is a super light Mvvm Framework designed specifically for Xamarin.Forms.
* [ReactiveUI](https://github.com/reactiveui/ReactiveUI) - Use the Reactive Extensions for .NET to create elegant, testable User Interfaces that run on any mobile or desktop platform. Supports Xamarin.iOS, Xamarin.Android, Xamarin.Mac, Xamarin Forms, WPF, Windows Forms, Windows Phone 8, Windows Store and Universal Windows Platform (UWP). ![android][android]![ios][ios]![windows][windows]

## Authentication
* [Xamarin.Auth](https://components.xamarin.com/view/xamarin.auth/) - Xamarin.Auth helps you authenticate users via standard authentication mechanisms (e.g. OAuth 1.0 and 2.0), and store user credentials. ![android][android]![ios][ios]

* [Auth0](https://components.xamarin.com/view/auth0client) - Add authentication with different sources, either social like Google, Facebook, Twitter, or enterprise like WAAD, Google Apps, AD, ADFS or any SAML Provider.
 ![android][android]![ios][ios]
 
* [SimpleAuth](https://github.com/Clancey/SimpleAuth) SimpleAuth embeds authentication into the API so you dont need to deal with it. Most importantly it works great with traditional Xamarin and Xamarin.Forms, and supports providers like Facebook and Google out of the box.
 
* [Fingerprint](https://github.com/smstuebe/xamarin-fingerprint/) - Authenticate a user using the fingerprint sensor (aka. Touch ID).
 ![android][android]![ios][ios]![windows][windows]

## Cache
* [Akavache](https://github.com/akavache/Akavache) - Akavache is an asynchronous, persistent (i.e. writes to disk) key-value store created for writing desktop and mobile applications in C#, based on SQLite3. Akavache is great for both storing important data (i.e. user settings) as well as cached local data that expires.![android][android]![ios][ios]![windows][windows]
* [FFImageLoading](https://github.com/luberda-molinet/FFImageLoading) - Library to load images quickly & easily on Xamarin.iOS, Xamarin.Android, Xamarin.Forms and Windows (UWP, WinRT).![android][android]![ios][ios]![windows][windows]

## Charts
* [Syncfusion](https://www.syncfusion.com/products/xamarin/chart) - Chart includes functionality for plotting more than 20 chart types. Each chart type is easily configured with built-in support for creating stunning visual effects. ![android][android]![ios][ios]![windows][windows]
* [Flexchart](http://www.goxuni.com/flexchart/) - Visualize your data in a wide span of Cartesian chart types including bar, column, area, line, spline, scatter, bubble, high-low-open-close (HLOC) and candle. ![android][android]![ios][ios]![windows][windows]
* [Charts](https://github.com/Flash3001/iOSCharts.Xamarin) - A Xamarin port by Lucas Teixeira for [Charts](https://github.com/danielgindi/Charts) (ios-charts) by Daniel Cohen Gindi, inspired by Philipp Jahoda  ![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/ios.png)
* [Oxyplot](https://components.xamarin.com/view/oxyplot) - A cross-platform plotting library for .NET ![android][android]![ios][ios]![windows][windows]
* [Telerik](http://www.telerik.com/xamarin-ui/chart) - Feature-rich, intuitive and easy to use data visualization control featuring a large collection of chart series with smooth interaction and zooming. ![android][android]![ios][ios]![windows][windows]
* [SciChart](https://www.scichart.com/scichart-xamarin-ios-xamarin-android-bindings-alpha/) - High performance iOS & Android charts. Capable of displaying millions of data-points in real-time (see [Android Performance](https://www.scichart.com/android-chart-performance-comparison/), [iOS Performance](https://www.scichart.com/ios-chart-performance-comparison/)). Supports 2D Line, Scatter, Column, Mountain chart, OHLC, Candlestick, Heatmap. v2 will support Stacked Columns, Stacked Mountains, Error Bars, Bubbles and Xamarin bindings![android][android]![ios][ios]
* [MPAndroidChart](https://github.com/Flash3001/MPAndroidChart.Xamarin) - A Xamarin binding for [MPAndroidChart](https://github.com/PhilJay/MPAndroidChart) by Philipp Jahoda. ![android][android]

## Code Quality
* [Xamarin profiler](https://www.xamarin.com/profiler) - Use it to find memory leaks, resolve performance bottlenecks, and add polish to your apps before getting them out the door. ![android][android]![ios][ios]
* [Firebase](https://firebase.google.com/) - Analytics and much more. ![android][android]![ios][ios]![windows][windows] 
* [Hockeyapp](https://hockeyapp.com/) - Analytics and crash reporting ![android][android]![ios][ios]![windows][windows]

## Color
* [Splat](https://github.com/paulcbetts/splat) - Splat aims to fix that, by providing a usable leaky abstraction above platform code. It is leaky, because it always provides an extension method ToNative() and FromNative(), which converts the abstraction to the platform-specific version.

## Database
* [Akavache](https://github.com/akavache/Akavache) - Akavache is an asynchronous, persistent (i.e. writes to disk) key-value store created for writing desktop and mobile applications in C#, based on SQLite3. Akavache is great for both storing important data (i.e. user settings) as well as cached local data that expires.![android][android]![ios][ios]![windows][windows]
* [Realm](https://realm.io/docs/xamarin/latest/) - The alternative to SQLite: Simple, modern and fast.![android][android]![ios][ios]![windows][windows]
* [Couchbase Lite](https://components.xamarin.com/view/couchbase-lite-net) - Couchbase document store lite![android][android]![ios][ios]![windows][windows]
* [sqlite-net](https://github.com/praeclarum/sqlite-net) - SQLite-net is an open source, minimal library to allow .NET and Mono applications to store data in SQLite 3 databases.![android][android]![ios][ios]![windows][windows]
* [Genesis.Repository](https://github.com/kentcb/Genesis.Repository) - Genesis.Repository is a library that makes it simpler to implement the repository pattern within your application, using SQLite as a backing store.![android][android]![ios][ios]![windows][windows]
* [Genesis.DataStore](https://github.com/kentcb/Genesis.DataStore) - Genesis.DataStore is a library that makes it simpler to implement a SQLite-based, versioned data store for your application.![android][android]![ios][ios]![windows][windows]

## Data Structures / Algorithms
*

## Date & Time

* [Noda.Time](http://nodatime.org/) - A better date and time API for .NET![android][android]![ios][ios]![windows][windows]


## EventBus
* [MessageBus](https://components.xamarin.com/view/messagebus) - Cross platform EventBus framework for iOS, Android, Windows Phone and Mac![android][android]![ios][ios]![windows][windows]


## Files
* [PCLStorage](https://github.com/dsplaisted/PCLStorage) - PCL Storage provides a consistent, portable set of local file IO APIs for .NET, Windows Phone, Windows Store, Xamarin.iOS, Xamarin.Android, and Silverlight. This makes it easier to create cross-platform .NET libraries and apps.![android][android]![ios][ios]![windows][windows]
* [Filepicker-plugin](https://github.com/Studyxnet/FilePicker-Plugin-for-Xamarin-and-Windows) - Simple cross-platform plug-in that allows Pick files, save files and open the archive application standards..![android][android]![ios][ios]![windows][windows]

## Games
* [CocoSharp](https://developer.xamarin.com/guides/cross-platform/game_development/cocossharp/) - CocosSharp is an easy to use library for 2D games using C# and F#. It is a .NET port of the popular Cocos2D engine. ![android][android]![ios][ios]![windows][windows]
* [UrhoSharp](https://developer.xamarin.com/guides/cross-platform/urho/introduction/) - UrhoSharp is a powerful 3D Game Engine for Xamarin and .NET developers. ![android][android]![ios][ios]![windows][windows]
* [MonoGame](https://developer.xamarin.com/guides/cross-platform/game_development/monogame/) - MonoGame is an efficient, flexible, cross platform API for developing 2D and 3D games.![android][android]![ios][ios]![windows][windows]

## Gesture
* [MR.Gestures](http://www.mrgestures.com/) - Handles all touch gestures in your Xamarin.Forms app. It uses a .NET like API in the PCL. No need for platform specific code.![android][android]![ios][ios]![windows][windows]

## Graphics
* [Splat](https://github.com/paulcbetts/splat) - Splat aims to fix that, by providing a usable leaky abstraction above platform code. It is leaky, because it always provides an extension method ToNative() and FromNative(), which converts the abstraction to the platform-specific version.![android][android]![ios][ios]![windows][windows]
* [SkiaSharp](https://github.com/mono/SkiaSharp) - SkiaSharp is a cross-platform 2D graphics API for .NET platforms based on Google's Skia Graphics Library (https://skia.org/). ![android][android]![ios][ios]![windows][windows]
* [NGraphics](https://github.com/praeclarum/NGraphics) - NGraphics is a cross platform library for rendering vector graphics on .NET.![android][android]![ios][ios]![windows][windows]

## Hardware
#### Bluetooth
* [Xamarin bluetooth le](https://github.com/xabre/xamarin-bluetooth-le) - Xamarin and MvvMCross plugin for accessing the bluetooth functionality. ![android][android]![ios][ios]![windows][windows]
* [BluetoothLE](https://github.com/aritchie/bluetoothle) - Easy to use, cross platform, reactive BluetoothLE Plugin for Xamarin.![android][android]![ios][ios]

#### Camera
* [MediaPlugin](https://github.com/jamesmontemagno/MediaPlugin) - Simple cross platform plugin to take photos and video or pick them from a gallery from shared code.![android][android]![ios][ios]![windows][windows]
* [Chafu](https://github.com/BruelAndKjaer/Chafu) - A photo browser and camera library for Xamarin.iOS. UIImagePickerController alternative, with cropping support, face detection and more. ![ios][ios]

#### Beacons
* [AltBeacon](https://github.com/chrisriesgo/Android-AltBeacon-Library) - Allows developers to create proximity aware applications utilizing iBeacons & geo fences.![android][android]
* [Estimote](http://developer.estimote.com/other-platforms/3rd-party-sdks/#xamarin-ios--android-c) - Xamarin folks have prepared these components—wrappers around our native SDKs for iOS and Android:![android][android]![ios][ios]

#### Location
* [GeoLocator](https://github.com/jamesmontemagno/GeolocatorPlugin) - Simple cross platform plugin to get GPS location including heading, speed, and more. ![android][android]![ios][ios]![windows][windows]

#### Other Hardware
*

## Layout
* [FluentLayout](https://github.com/FluentLayout/Cirrious.FluentLayout) - FluentLayout provides an easy, fluent API for creating constraint-based layouts in Xamarin.iOS. ![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/ios.png)
* [TZStackView](https://github.com/Cheesebaron/TZStackView) - A back port for iOS 7 & 8 and drop in replacement of UIStackView for Xamarin.iOS. ![ios][ios]
* [SlideOverKit](https://github.com/XAM-Consulting/SlideOverKit) - SlideOverKit allows developers to easily create awesome Slideovers in Xamarin.Forms. ![android][android]![ios][ios]![windows][windows]
* [EasyLayout](https://gist.github.com/praeclarum/6225853) - EasyLayout makes writing auto layout code in Xamarin.iOS easier. ![ios][ios]
* [EasyLayout.Droid](https://github.com/lprichar/EasyLayout.Droid) - EasyLayout.Droid makes it easier to read, write, and maintain relative layouts in Xamarin.Android. ![android][android]

## Localization
* [JsonLocalization](https://mvvmcross.com/docs/jsonlocalisation) - MvvmCross - The JsonLocalization plugin provides a number of support classes to help load Json language text files for internationalization (i18n). ![android][android]![ios][ios]![windows][windows]
* [I18N-Portable](https://github.com/xleon/I18N-Portable) - Simple and cross platform internationalization/translations for Xamarin and .NET. ![android][android]![ios][ios]![windows][windows]

## Logging
* [Xamarin-Logger](https://github.com/jirimatejka/xamarin-logger) - Simple plugin for logging events in your Xamarin.Forms applications. ![android][android]![ios][ios]![windows][windows]
* [Genesis.Logging](https://github.com/kentcb/Genesis.Logging) - Genesis.Logging is a simple library for application authors (not library authors) to facilitate performance-focussed logging.![android][android]![ios][ios]![windows][windows]

## Maps
* [ExternalMaps-Plugin](https://components.xamarin.com/gettingstarted/externalmapsplugin) - Open external maps application to navigate to a specific geolocation or address. ![android][android]![ios][ios]![windows][windows]
* [Google-Maps-iOS](https://components.xamarin.com/view/googleiosmaps) - Add custom markers, styled maps, 3D buildings, indoor floor plans, street view, satellite imagery, and more to your iOS app. ![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/ios.png)
* [UnifiedMaps](https://github.com/fiveninedigital/UnifiedMaps) - A platform independent map implementation for Xamarin.Forms designed from the ground up with MVVM in mind. ![android][android]![ios][ios]

## Math
* [Math.NET](https://numerics.mathdotnet.com/) - Math.NET Numerics aims to provide methods and algorithms for numerical computations in science, engineering and every day use. ![android][android]![ios][ios]![windows][windows]


## Media
#### Audio
* [XamarinMediaManager](https://github.com/martijn00/XamarinMediaManager) - Cross platform Xamarin plugin to play Media from PCL ![android][android]![ios][ios]![windows][windows]

#### GIF
* [gifimageviewandroid](https://components.xamarin.com/view/gifimageviewandroid) - Xamarin.Android ImageView that handles Animated GIF images! ![android][android]![ios][ios]![windows][windows]

#### Image
* [ImageCirclePlugin](https://github.com/jamesmontemagno/ImageCirclePlugin) - Simple but elegant way of display circle images in your Xamarin.Forms projects ![android][android]![ios][ios]![windows][windows]
* [SimpleCropView](https://github.com/markjackmilian/Xam.Droid.SimpleCropView) - Image cropping library for Xamarin Android ![android][android]


#### Media Processing
* [QRchestra](https://developer.xamarin.com/samples/monotouch/QRchestra/) - QR Code implementation. ![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/ios.png)
* [ZXING.net](https://components.xamarin.com/view/zxing.net.mobile) - ZXing.Net.Mobile is a C#/.NET Barcode Scanning Library ![android][android]![ios][ios]![windows][windows]

#### PDF
* [Xamarin.Forms.PDFViewer](https://github.com/alexrainman/Xamarin.Forms.PDFViewer) - PDF Viewer custom renderers for Xamarin.Forms using Radaee PDF SDK and android-pdfview ![android][android]

* [ZoomingPdfViewer](https://github.com/xamarin/ios-samples/tree/master/ZoomingPdfViewer) - PThis is a port of Apple's ZoomingPDFViewer ![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/ios.png)

* [mTouch-PDFReader](https://github.com/AlexanderMac/mTouch-PDFReader) - mTouch-PDFReader is a Xamarin iOS library to display PDF documents on iPad and iPhone. ![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/ios.png)

* [PDFNet](https://www.pdftron.com/pdfnet/) - PDFNet SDK is an industry-leading, high-quality document solution powering mobile, server, desktop, web, and cloud-based apps.

* [XFiniumPDF](https://components.xamarin.com/view/xfinium.pdf) -Cross platform PDF development. Add PDF capabilites to your iOS, Android or Windows Phone applications.![android][android]

* [APITron](https://components.xamarin.com/view/apitron-pdf-kit) - Universal PDF creation and manipulation library, can be used to read, merge, edit and sign PDFs. Supports PDF content extraction, including text and images. ![android][android]![ios][ios]

* [PSPDFKit](https://pspdfkit.com/) - A high-level PDF framework, includes PDF viewer, annotations and forms support, indexed full-text search and document editor. Official bindings are [available](https://pspdfkit.com/guides/ios/current/other-languages/xamarin/). ![android][android]![ios][ios]

#### Streaming
* [AndroidStreamingAudio](https://github.com/jamesmontemagno/AndroidStreamingAudio) - Series of Samples of streaming audio in background service in Xamarin.Android ![android][android]

#### Video
* [XamarinMediaManager](https://github.com/martijn00/XamarinMediaManager) - Cross platform Xamarin plugin to play Media from PCL ![android][android]![ios][ios]![windows][windows]

## Messaging

Also see [push notifications](#push-notifications)

* [JSQMessagesViewController](https://components.xamarin.com/view/jsqmessagesviewcontroller) - JSQMessagesViewController provides a gorgeous and feature rich iOS view controller that makes adding messaging to your app easy. ![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/ios.png)
* [SlackTextViewController](https://components.xamarin.com/view/SlackTextViewController) - A drop-in UIViewController subclass with a growing text input view and other useful messaging features. ![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/ios.png)

## Networking
* [Polly](https://github.com/App-vNext/Polly) - Polly is a .NET resilience and transient-fault-handling library that allows developers to express policies such as Retry, Circuit Breaker, Timeout, Bulkhead Isolation, and Fallback in a fluent and thread-safe manner. ![android][android]![ios][ios]![windows][windows]
* [refit](https://github.com/paulcbetts/refit) - The automatic type-safe REST library for Xamarin and .NET. ![android][android]![ios][ios]![windows][windows]
* [ModernHttpClient](https://github.com/paulcbetts/ModernHttpClient) - This library brings the latest platform-specific networking libraries to Xamarin applications via a custom HttpClient handler. ![android][android]![ios][ios]![windows][windows]
* [Connectivity](https://github.com/jamesmontemagno/ConnectivityPlugin) - This library brings the latest platform-specific networking libraries to Xamarin applications via a custom HttpClient handler. ![android][android]![ios][ios]![windows][windows]
* [Fusillade](https://github.com/paulcbetts/Fusillade) - Fusillade helps you to write more efficient code in mobile and desktop applications written in C#. Its design goals and feature set are inspired by Volley as well as Picasso. ![android][android]![ios][ios]![windows][windows]


#### Email

* [Messaging Plugin](https://components.xamarin.com/view/xam.plugins.messaging) - The Messaging plugin makes it possible to make a phone call, send a sms or send an e-mail using the default messaging applications on the different mobile platforms. ![android][android]![ios][ios]![windows][windows]
* [MvvmCross email plugin](https://github.com/MvvmCross/MvvmCross/tree/develop/MvvmCross-Plugins/Email) -The Email plugin provides a cross-platform implementation for sending emails. ![android][android]![ios][ios]![windows][windows]

## Notifications

#### Push Notifications
* [PushNotification](https://github.com/rdelrosario/xamarin-plugins/tree/master/PushNotification) -Simple cross platform plugin to handle push notification events such as registering, unregistering and messages arrival on Android, iOS, UWP platforms. ![android][android]![ios][ios]![windows][windows]
* [PushSharp](https://github.com/Redth/PushSharp) - PushSharp is a server-side library for sending Push Notifications to iOS/OSX (APNS), Android/Chrome (GCM), Windows/Windows Phone, Amazon (ADM) and Blackberry devices! ![android][android]![ios][ios]![windows][windows]

##### Push Notification Providers

Most of these are paid services, some have free tiers.

* [Urban Airship](https://www.urbanairship.com/products/mobile-app-engagement ) ![android][android]![ios][ios]![windows][windows]
* [Azure](https://azure.com) - Microsoft Azure platformr. ![android][android]![ios][ios]![windows][windows]
* [HelpShift](https://lp.helpshift.com/push-notifications) - in-app push notification and messaging sdk ![android][android]![ios][ios]![windows][windows]

## Parsing

#### CSV
* [CSVHelper](https://github.com/JoshClose/CsvHelper) - A library for reading and writing CSV files. Extremely fast, flexible, and easy to use. Supports reading and writing of custom class objects. ![android][android]![ios][ios]![windows][windows]
* [KBCsv](https://github.com/kentcb/KBCsv) - KBCsv is an efficient, easy to use .NET parsing and writing library for the CSV (comma-separated values) format. ![android][android]![ios][ios]![windows][windows]

#### JSON
* [JSON.net](http://www.newtonsoft.com/json) -  Popular high-performance JSON framework for .NET

 Download
#### HTML
* [HTML Agility pack](http://htmlagilitypack.codeplex.com/) -This is an agile HTML parser that builds a read/write DOM and supports plain XPATH or XSLT ![android][android]![ios][ios]![windows][windows]

## Passbook
* [PassKitSharp](https://github.com/Redth/PassKitSharp) - PassKitSharp is a C#/.NET Library for Reading and Writing Apple PassKit files. ![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/ios.png)

## Payments
* [JudoPay](https://components.xamarin.com/view/judopay-xamarin-sdk) - Payments SDK for Xamarin.Forms. ![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images//android%2Bios.png)
* [Stripe](https://components.xamarin.com/view/stripe) - Mobile Payments built for Developers
 ![android][android]![ios][ios]
* [Xamarin.inAppBilling](https://components.xamarin.com/view/xamarin.inappbilling) - Component to assist in adding In-App Billing to a Xamarin.Android application via Google Play Services.![android][android]
* [PayPal.Forms](https://github.com/AlejandroRuiz/PayPal.Forms) - PayPal Plugin for Xamarin.Forms ![android][android]![ios][ios]

## Permissions
* [PermissionsPlugin](https://github.com/jamesmontemagno/PermissionsPlugin) - Simple cross platform plugin to request and check permissions. ![android][android]![ios][ios]![windows][windows]

## Reactive Programming
* [ReactiveUI](https://github.com/reactiveui/ReactiveUI) - A MVVM framework that integrates with the Reactive Extensions for .NET to create elegant, testable User Interfaces that run on any mobile or desktop platform. ![android][android]![ios][ios]![windows][windows]
* [Genesis.Observables](https://github.com/kentcb/Genesis.Observables) - Genesis.Observables is a simple library that provides commonly used, pre-canned observables.![android][android]![ios][ios]![windows][windows]
* [Genesis.GenericSerialDisposable](https://github.com/kentcb/Genesis.GenericSerialDisposable) - Genesis.GenericSerialDisposable adds a generic version of Reactive Extensions' SerialDisposable class.![android][android]![ios][ios]![windows][windows]
* [Genesis.RetryWithBackoff](https://github.com/kentcb/Genesis.RetryWithBackoff) - Genesis.RetryWithBackoff adds a `RetryWithBackoff` extension method to observables. As the name suggests, the `RetryWithBackoff` method makes it simple to retry a failing observable with a variable delay between retries.![android][android]![ios][ios]![windows][windows]
* [Genesis.RepeatWithBackoff](https://github.com/kentcb/Genesis.RepeatWithBackoff) - Genesis.RepeatWithBackoff adds a `RepeatWithBackoff` extension method to observables. As the name suggests, the `RepeatWithBackoff` method makes it simple to repeat a failing observable with a variable delay between repetitions.![android][android]![ios][ios]![windows][windows]
* [Genesis.WindowScan](https://github.com/kentcb/Genesis.WindowScan) - Genesis.WindowScan adds a `WindowScan` extension method to observables. This allows you to scan a time-boxed window if items. As items arrive on the source, your `add` function will be called. As items fall outside the window, your `remove` function will be called.![android][android]![ios][ios]![windows][windows]
* [BluetoothLE](https://github.com/aritchie/bluetoothle) - Easy to use, cross platform, reactive BluetoothLE Plugin for Xamarin.![android][android]![ios][ios]

## Security
* [Xamarin.Auth](https://components.xamarin.com/view/xamarin.auth/) - Xamarin.Auth helps you authenticate users via standard authentication mechanisms (e.g. OAuth 1.0 and 2.0), and store user credentials. ![android][android]![ios][ios]

#### Encryption
* [PCLCrypto](https://github.com/AArnott/PCLCrypto) - PCLCrypto provides cryptographic APIs over algorithms implemented by the platform, including exposing them to portable libraries. ![android][android]![ios][ios]![windows][windows]
* [SecureStorage](https://github.com/sameerkapps/SecureStorage) - The plugin can be used to securely store sensitive data strings such as password, session token, credit card number etc. ![android][android]![ios][ios]![windows][windows]

## Testing

#### TDD / BDD
* [xUnit](http://xunit.github.io/) - xUnit.net is a free, open source, community-focused unit testing tool for the .NET Framework. xUnit has test runners available for Android and iOS. [Greg Shackles](http://gregshackles.com) has written a nice [tutorial](http://gregshackles.com/testing-xamarin-apps-getting-started-with-xunit/) to help you get started. ![android][android]![ios][ios]
* [NUnitLite](https://github.com/nunit/nunitlite) - A lightweight testing framework for .NET, based on the ideas in NUnit and providing a subset of its features. NUnitLite is distributed with Xamarin to allow unit-testing of applications build with Xamarin. ![android][android]![ios][ios]![windows][windows]
* [PCLMock](https://github.com/kentcb/PCLMock) - A simple mocking framework in a PCL.![android][android]![ios][ios]![windows][windows]

#### A/B Testing
* 

#### UI Testing
* [Xamarin UITest](https://developer.xamarin.com/guides/testcloud/uitest/) - Introducing Xamarin.UITest, an Automated UI Acceptance Testing framework based on Calabash that allows programmers to write and execute tests in C# and NUnit that validate the functionality of iOS and Android Apps. ![android][android]![ios][ios]![windows][windows]

#### Font
* 

## UI
* [userdialogs](https://github.com/aritchie/userdialogs/) - A cross platform library that allows you to call for standard user dialogs from a shared/portable library, Actionsheets, alerts, confirmations, loading, login, progress, prompt, toast... async just for fun. ![android][android]![ios][ios]![windows][windows] 

#### Activity Indicator
* 

#### Alerts
* 

#### App Introduction
* [AppIntro](https://github.com/JonDouglas/AppIntro) - Xamarin port of [AppIntro](https://github.com/PaoloRotolo/AppIntro) by apl-devs.![android][android]

#### Badge
* 

#### Button
* 

#### Calendar
* 

#### Card View
* [FoldingCell](https://github.com/martijn00/FoldingCell) - FoldingCell is an expanding content cell inspired by folding paper material and created by [Ramotion Inc](https://business.ramotion.com/gthb-casestudies). ![android][android]


#### Form & Settings
* 

#### Keyboard
* [FormsPinView](https://github.com/lassana/XamarinFormsPinView) -  PIN keyboard for Xamarin.Forms. ![android][android]![ios][ios] 

#### Label
* 

#### Menu
* 

#### Modal Transition
* 

#### Navigation Bar / Toolbar
* 

#### PickerView
* 

#### Popup
* [Rg.Plugins.Popup](https://github.com/rotorgames/Rg.Plugins.Popup) - The plugin allows you to open any page as a popup in Xamarin.Forms. ![android][android]![ios][ios]![windows][windows]

#### Pull to Refresh
* 

#### Rating Stars
*

#### ScrollView
* 

#### Slider
* 

#### Splash View
* 

#### Stepper
* 

#### Switch
* 

#### Tab Bar
* [Tab Badge](https://github.com/xabre/xamarin-forms-tab-badge) - Xamarin Forms bindable tab badges. Badges are small numbers/chars that can indicate new items on the tab page.
 ![android][android]![ios][ios]
* [SGTabbedPager](https://github.com/Cheesebaron/SGTabbedPager) - A port of SGViewPager for Xamarin.iOS. Provides ViewPagerIndicator like tabs to iOS. ![ios][ios]

#### Table View / Collection View
* 


#### Tag
* 

#### TextField & TextView
* 

#### Web View
* 

## URL Scheme
* 

## Utility
 * 
 
## VR
* 

## Walkthrough / Intro / Tutorial
* 

## WebSocket
* 

#### GCD
 * 

# Project setup
* 

# Dependency / Package Manager
* 

# Tools
* 

# Rapid Development
* 

# Injection
* 

# Deployment / Distribution
* 

# App Store

# Style Guides
* 

# Good Websites

#### News, Blogs and more
* [marcbruins.nl](http://www.marcbruins.nl/)
* [weeklyxamarin.com](https://weeklyxamarin.com/)
* [planetxamarin.com](https://planetxamarin.com/)
* [ghuntley.com](https://ghuntley.com/)

#### UIKit references
* [iOS Fonts](http://iosfonts.com/)
* [UIAppearance list](https://gist.github.com/mattt/5135521)

#### Forums and discuss lists
* 

#### Tutorials and Keynotes
* 

#### iOS UI Template
* 

#### Prototyping
* 

#### Newsletters

* [WeeklyXamarin](https://www.weeklyxamarin.com/) - Hand-picked round up of the best Xamarin development links every week. Curated by Geoffrey Huntley and published every Friday. Free.

#### Medium
* 

# Social Media

* [Planet Xamarin](https://planetxamarin.com) - An aggregator of content from Xamarin Community members. Why subscribe individually when you can subscribe to one convenient RSS feed? If RSS isn't your thing, follow our [Twitter](https://twitter.com/PlanetXamarin) or [Facebook](https://www.facebook.com/planetxamarin/) accounts which are automatically updated with the latest content from the community.


#### Twitter


#### Facebook Groups


# Podcasts

* [Xamarin Podcast](https://soundcloud.com/xamarin-podcast) ([iTunes](https://itunes.apple.com/us/podcast/xamarin-podcast/id691368176?mt=2), [Google Play Music](https://play.google.com/music/listen?u=0#/ps/Ifcss44ww5lc375esulsuettsey)) - Knowing the latest in .NET, C#, and Xamarin is easier than ever with the Xamarin Podcast! Covers both Xamarin-specific topics (like [What's New in Xamarin.Forms](https://blog.xamarin.com/podcast-whats-new-in-xamarin-forms-2-3-3/) and general mobile development topics, like [authentication and identity management](https://blog.xamarin.com/podcast-identity-management-in-mobile-apps/).
* [MergeConflict](http://www.mergeconflict.fm/) - A weekly discussion on all things development, technology, & more.
* [Gone Mobile](http://gonemobile.io/) - Gone Mobile is a podcast discussing the latest in mobile development, with a healthy bias towards Xamarin technologies. The podcast covers in-depth topics with guests ranging from Android, iOS, Windows Phone & Store development to mobile marketing and design, as well as other mobile or not so mobile related technologies.

# Books
* [Xamarin In Action](http://xam.jbb.io) - Creating Native Cross-Platform Mobile Apps
* [Mastering Xamarin.Forms](http://book.sndr.io) - Patterns and practices for building mobile apps with Xamarin.Forms


# Contributing and License
 * [See the guide](https://github.com/MarcBruins/awesome-xamarin/blob/master/CONTRIBUTING.md)
 * Distributed under the MIT license. See LICENSE for more information.

[ios]: https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/ios.png
[android]: https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/android.png
[windows]: https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/windows.png
