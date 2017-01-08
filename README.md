#Awesome Xamarin

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)

# About
A curated list of awesome Xamarin ports, bindings, tutorials and much more!
The list is divided into categories such as Frameworks, Components, Testing and others, open source projects, free and paid services. There is no pre-established order of items in each category, the order is for contribution. If you want to contribute, please read the [guide](https://github.com/vsouza/awesome-ios/blob/master/.github/CONTRIBUTING.md).


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
        - [Other Testing](#other-testing)
    - [Text](#text)
        - [Font](#font)
    - [UI](#ui)
        - [Activity Indicator](#activity-indicator)
        - [Alert View](#alerts)
        - [Badge](#badge)
        - [Button](#button)
        - [Calendar](#calendar)
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
* [Google Analytics](https://www.google.nl/intl/nl/analytics/) - Google analytics platform. ![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/android%2Bios%2Bwindows.png) 
* [Firebase](https://firebase.google.com/) - Analytics and much more. ![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/android%2Bios%2Bwindows.png) 
* [Hockeyapp](https://hockeyapp.com/) - Analytics and crash reporting ![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/android%2Bios%2Bwindows.png)

## Animation
* [Xamarin.Animations](https://github.com/aloisdeniel/Xamarin.Animations) - Libraries tends to make view animation easier for common scenarios like fade or scale entrance animations. ![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/android%2Bios%2Bwindows.png)
* [Facebook Pop](https://components.xamarin.com/view/Facebook.Pop) - Pop is an open-source animation engine behind the Facebook Paper's smooth animations and transitions. Using dynamic instead of traditional static animations, Pop drives the scrolling, bouncing, and unfolding effects that bring Paper to life. ![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/ios.png)

## Authentication
* [Xamarin.Auth](https://components.xamarin.com/view/xamarin.auth/) - Xamarin.Auth helps you authenticate users via standard authentication mechanisms (e.g. OAuth 1.0 and 2.0), and store user credentials. ![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/android%2Bios.png)

* [Auth0](https://components.xamarin.com/view/auth0client) - Add authentication with different sources, either social like Google, Facebook, Twitter, or enterprise like WAAD, Google Apps, AD, ADFS or any SAML Provider.
 ![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/android%2Bios.png)


## Cache
* [Akavache](https://github.com/akavache/Akavache) - Akavache is an asynchronous, persistent (i.e. writes to disk) key-value store created for writing desktop and mobile applications in C#, based on SQLite3. Akavache is great for both storing important data (i.e. user settings) as well as cached local data that expires.![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/android%2Bios%2Bwindows.png)
* [FFImageLoading](https://github.com/luberda-molinet/FFImageLoading) - Library to load images quickly & easily on Xamarin.iOS, Xamarin.Android, Xamarin.Forms and Windows (UWP, WinRT).![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/android%2Bios%2Bwindows.png)


## Charts
* [Syncfusion](https://www.syncfusion.com/products/xamarin/chart) - Chart includes functionality for plotting more than 20 chart types. Each chart type is easily configured with built-in support for creating stunning visual effects. ![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/android%2Bios%2Bwindows.png)
* [Flexchart](http://www.goxuni.com/flexchart/) - Visualize your data in a wide span of Cartesian chart types including bar, column, area, line, spline, scatter, bubble, high-low-open-close (HLOC) and candle. ![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/android%2Bios%2Bwindows.png)
* [Charts](https://github.com/Flash3001/iOSCharts.Xamarin) - A Xamarin port by Lucas Teixeira for Charts (ios-charts) by Daniel Cohen Gindi, inspired by Philipp Jahoda https://github.com/danielgindi/Charts ![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/ios.png)
* [Oxyplot](https://components.xamarin.com/view/oxyplot) - A cross-platform plotting library for .NET ![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/android%2Bios%2Bwindows.png)
* [Telerik](http://www.telerik.com/xamarin-ui/chart) - Feature-rich, intuitive and easy to use data visualization control featuring a large collection of chart series with smooth interaction and zooming. ![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/android%2Bios%2Bwindows.png)
* [SciChart](https://www.scichart.com/scichart-xamarin-ios-xamarin-android-bindings-alpha/) - High performance charts. ![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/android%2Bios.png)

## Code Quality
* [Xamarin profiler](https://www.xamarin.com/profiler) - Use it to find memory leaks, resolve performance bottlenecks, and add polish to your apps before getting them out the door. ![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/android%2Bios.png)
* [Firebase](https://firebase.google.com/) - Analytics and much more. ![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/android%2Bios%2Bwindows.png) 
* [Hockeyapp](https://hockeyapp.com/) - Analytics and crash reporting ![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/android%2Bios%2Bwindows.png)

## Color
* [Splat](https://github.com/paulcbetts/splat) - Splat aims to fix that, by providing a usable leaky abstraction above platform code. It is leaky, because it always provides an extension method ToNative() and FromNative(), which converts the abstraction to the platform-specific version.

## Database
* [Akavache](https://github.com/akavache/Akavache) - Akavache is an asynchronous, persistent (i.e. writes to disk) key-value store created for writing desktop and mobile applications in C#, based on SQLite3. Akavache is great for both storing important data (i.e. user settings) as well as cached local data that expires.![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/android%2Bios%2Bwindows.png)
* [Realm](https://realm.io/docs/xamarin/latest/) - The alternative to SQLite: Simple, modern and fast.![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/android%2Bios%2Bwindows.png)
* [Couchbase Lite](https://components.xamarin.com/view/couchbase-lite-net) - Couchbase document store lite![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/android%2Bios%2Bwindows.png)
* [sqlite-net](https://github.com/praeclarum/sqlite-net) - SQLite-net is an open source, minimal library to allow .NET and Mono applications to store data in SQLite 3 databases.![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/android%2Bios%2Bwindows.png)


## Data Structures / Algorithms
*

## Date & Time

* [Noda.Time](http://nodatime.org/) - A better date and time API for .NET![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/android%2Bios%2Bwindows.png)


## EventBus
* [MessageBus](https://components.xamarin.com/view/messagebus) - Cross platform EventBus framework for iOS, Android, Windows Phone and Mac![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/android%2Bios%2Bwindows.png)


## Files
* [PCLStorage](https://github.com/dsplaisted/PCLStorage) - PCL Storage provides a consistent, portable set of local file IO APIs for .NET, Windows Phone, Windows Store, Xamarin.iOS, Xamarin.Android, and Silverlight. This makes it easier to create cross-platform .NET libraries and apps.![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/android%2Bios%2Bwindows.png)
* [Filepicker-plugin](https://github.com/Studyxnet/FilePicker-Plugin-for-Xamarin-and-Windows) - Simple cross-platform plug-in that allows Pick files, save files and open the archive application standards..![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/android%2Bios%2Bwindows.png)

## Games
* [CocoSharp](https://developer.xamarin.com/guides/cross-platform/game_development/cocossharp/) - CocosSharp is an easy to use library for 2D games using C# and F#. It is a .NET port of the popular Cocos2D engine. ![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/android%2Bios%2Bwindows.png)
* [UrhoSharp](https://developer.xamarin.com/guides/cross-platform/urho/introduction/) - UrhoSharp is a powerful 3D Game Engine for Xamarin and .NET developers. ![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/android%2Bios%2Bwindows.png)
* [MonoGame](https://developer.xamarin.com/guides/cross-platform/game_development/monogame/) - MonoGame is an efficient, flexible, cross platform API for developing 2D and 3D games.![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/android%2Bios%2Bwindows.png)

## Gesture
*

## Graphics
* [Splat](https://github.com/paulcbetts/splat) - Splat aims to fix that, by providing a usable leaky abstraction above platform code. It is leaky, because it always provides an extension method ToNative() and FromNative(), which converts the abstraction to the platform-specific version.![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/android%2Bios%2Bwindows.png)
* [SkiaSharp](https://github.com/mono/SkiaSharp) - SkiaSharp is a cross-platform 2D graphics API for .NET platforms based on Google's Skia Graphics Library (https://skia.org/). ![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/android%2Bios%2Bwindows.png)

## Hardware
#### Bluetooth
* [Xamarin bluetooth le](https://github.com/xabre/xamarin-bluetooth-le) - Xamarin and MvvMCross plugin for accessing the bluetooth functionality. ![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/android%2Bios%2Bwindows.png)

#### Camera
* [MediaPlugin](https://github.com/jamesmontemagno/MediaPlugin) - Simple cross platform plugin to take photos and video or pick them from a gallery from shared code.![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/android%2Bios%2Bwindows.png)

#### Beacons
* [AltBeacon](https://github.com/chrisriesgo/Android-AltBeacon-Library) - Allows developers to create proximity aware applications utilizing iBeacons & geo fences.![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/android.png)
* [Estimote](http://developer.estimote.com/other-platforms/3rd-party-sdks/#xamarin-ios--android-c) - Xamarin folks have prepared these components—wrappers around our native SDKs for iOS and Android:![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/android%2Bios.png)

#### Location
* [GeoLocator](https://github.com/jamesmontemagno/GeolocatorPlugin) - Simple cross platform plugin to get GPS location including heading, speed, and more. ![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/android%2Bios%2Bwindows.png)

#### Other Hardware
*

## Layout
* [FluentLayout](https://github.com/FluentLayout/Cirrious.FluentLayout) - FluentLayout provides an easy, fluent API for creating constraint-based layouts in Xamarin.iOS. ![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/ios.png)

## Localization
* [JsonLocalization](https://mvvmcross.com/docs/jsonlocalisation) - MvvmCross - The JsonLocalization plugin provides a number of support classes to help load Json language text files for internationalization (i18n). ![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/android%2Bios%2Bwindows.png)

## Logging
* [Xamarin-Logger](https://github.com/jirimatejka/xamarin-logger) - Simple plugin for logging events in your Xamarin.Forms applications. ![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/android%2Bios%2Bwindows.png)

## Maps
* [ExternalMaps-Plugin](https://components.xamarin.com/gettingstarted/externalmapsplugin) - Open external maps application to navigate to a specific geolocation or address. ![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/android%2Bios%2Bwindows.png)
* [Google-Maps-iOS](https://components.xamarin.com/view/googleiosmaps) - Add custom markers, styled maps, 3D buildings, indoor floor plans, street view, satellite imagery, and more to your iOS app. ![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/ios.png)

## Math
* [Math.NET](https://numerics.mathdotnet.com/) - Math.NET Numerics aims to provide methods and algorithms for numerical computations in science, engineering and every day use. ![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/android%2Bios%2Bwindows.png)


## Media
#### Audio
* [XamarinMediaManager](https://github.com/martijn00/XamarinMediaManager) - Cross platform Xamarin plugin to play Media from PCL ![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/android%2Bios%2Bwindows.png)

#### GIF
* [gifimageviewandroid](https://components.xamarin.com/view/gifimageviewandroid) - Xamarin.Android ImageView that handles Animated GIF images! ![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/android%2Bios%2Bwindows.png)

#### Image
* [ImageCirclePlugin](https://github.com/jamesmontemagno/ImageCirclePlugin) - Simple but elegant way of display circle images in your Xamarin.Forms projects ![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/android%2Bios%2Bwindows.png)


#### Media Processing
* [QRchestra](https://developer.xamarin.com/samples/monotouch/QRchestra/) - QR Code implementation. ![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/ios.png)
* [ZXING.net](https://components.xamarin.com/view/zxing.net.mobile) - ZXing.Net.Mobile is a C#/.NET Barcode Scanning Library ![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/android%2Bios%2Bwindows.png)

#### PDF
* [Xamarin.Forms.PDFViewer](https://github.com/alexrainman/Xamarin.Forms.PDFViewer) - PDF Viewer custom renderers for Xamarin.Forms using Radaee PDF SDK and android-pdfview ![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/android.png)

* [ZoomingPdfViewer](https://github.com/xamarin/ios-samples/tree/master/ZoomingPdfViewer) - PThis is a port of Apple's ZoomingPDFViewer ![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/ios.png)

* [mTouch-PDFReader](https://github.com/AlexanderMac/mTouch-PDFReader) - mTouch-PDFReader is a Xamarin iOS library to display PDF documents on iPad and iPhone. ![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/ios.png)

* [PDFNet](https://www.pdftron.com/pdfnet/) - PDFNet SDK is an industry-leading, high-quality document solution powering mobile, server, desktop, web, and cloud-based apps.

* [XFiniumPDF](https://components.xamarin.com/view/xfinium.pdf) -Cross platform PDF development. Add PDF capabilites to your iOS, Android or Windows Phone applications.![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/android.png)

* [APITron](https://components.xamarin.com/view/apitron-pdf-kit) - Universal PDF creation and manipulation library, can be used to read, merge, edit and sign PDFs. Supports PDF content extraction, including text and images. ![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/android%2Bios.png)

#### Streaming
* [AndroidStreamingAudio](https://github.com/jamesmontemagno/AndroidStreamingAudio) - Series of Samples of streaming audio in background service in Xamarin.Android ![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/android.png)

#### Video
* [XamarinMediaManager](https://github.com/martijn00/XamarinMediaManager) - Cross platform Xamarin plugin to play Media from PCL ![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/android%2Bios%2Bwindows.png)

## Messaging

Also see [push notifications](#push-notifications)

* [JSQMessagesViewController](https://components.xamarin.com/view/jsqmessagesviewcontroller) - JSQMessagesViewController provides a gorgeous and feature rich iOS view controller that makes adding messaging to your app easy. ![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/ios.png)
* [SlackTextViewController](https://components.xamarin.com/view/SlackTextViewController) - A drop-in UIViewController subclass with a growing text input view and other useful messaging features. ![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/ios.png)

## Networking
* [Polly](https://github.com/App-vNext/Polly) - Polly is a .NET resilience and transient-fault-handling library that allows developers to express policies such as Retry, Circuit Breaker, Timeout, Bulkhead Isolation, and Fallback in a fluent and thread-safe manner. ![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/android%2Bios%2Bwindows.png)
* [refit](https://github.com/paulcbetts/refit) - The automatic type-safe REST library for Xamarin and .NET. ![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/android%2Bios%2Bwindows.png)
* [ModernHttpClient](https://github.com/paulcbetts/ModernHttpClient) - This library brings the latest platform-specific networking libraries to Xamarin applications via a custom HttpClient handler. ![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/android%2Bios%2Bwindows.png)
* [Connectivity](https://github.com/jamesmontemagno/ConnectivityPlugin) - This library brings the latest platform-specific networking libraries to Xamarin applications via a custom HttpClient handler. ![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/android%2Bios%2Bwindows.png)
* [Fusillade](https://github.com/paulcbetts/Fusillade) - Fusillade helps you to write more efficient code in mobile and desktop applications written in C#. Its design goals and feature set are inspired by Volley as well as Picasso. ![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/android%2Bios%2Bwindows.png)


#### Email

* [Messaging Plugin](https://components.xamarin.com/view/xam.plugins.messaging) - The Messaging plugin makes it possible to make a phone call, send a sms or send an e-mail using the default messaging applications on the different mobile platforms. ![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/android%2Bios%2Bwindows.png)
* [MvvmCross email plugin](https://github.com/MvvmCross/MvvmCross/tree/develop/MvvmCross-Plugins/Email) -The Email plugin provides a cross-platform implementation for sending emails. ![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/android%2Bios%2Bwindows.png)

## Notifications

#### Push Notifications
* [PushNotification](https://github.com/rdelrosario/xamarin-plugins/tree/master/PushNotification) -Simple cross platform plugin to handle push notification events such as registering, unregistering and messages arrival on Android, iOS, UWP platforms. ![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/android%2Bios%2Bwindows.png)
* [PushSharp](https://github.com/Redth/PushSharp) - PushSharp is a server-side library for sending Push Notifications to iOS/OSX (APNS), Android/Chrome (GCM), Windows/Windows Phone, Amazon (ADM) and Blackberry devices! ![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/android%2Bios%2Bwindows.png)
* [PushSharp](https://github.com/Redth/PushSharp) - PushSharp is a server-side library for sending Push Notifications to iOS/OSX (APNS), Android/Chrome (GCM), Windows/Windows Phone, Amazon (ADM) and Blackberry devices! ![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/android%2Bios%2Bwindows.png)

##### Push Notification Providers

Most of these are paid services, some have free tiers.

* [Urban Airship](https://www.urbanairship.com/products/mobile-app-engagement ) ![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/android%2Bios%2Bwindows.png)
* [Azure](https://azure.com) - Microsoft Azure platformr. ![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/android%2Bios%2Bwindows.png)
* [HelpShift](https://lp.helpshift.com/push-notifications) - in-app push notification and messaging sdk ![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/android%2Bios%2Bwindows.png)

## Parsing

#### CSV
* [CSVHelper](https://github.com/JoshClose/CsvHelper) - A library for reading and writing CSV files. Extremely fast, flexible, and easy to use. Supports reading and writing of custom class objects. ![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/android%2Bios%2Bwindows.png)
* [KBCsv](https://github.com/kentcb/KBCsv) - KBCsv is an efficient, easy to use .NET parsing and writing library for the CSV (comma-separated values) format. ![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/android%2Bios%2Bwindows.png)

#### JSON
* [JSON.net](http://www.newtonsoft.com/json) -  Popular high-performance JSON framework for .NET

 Download
#### HTML
* [HTML Agility pack](http://htmlagilitypack.codeplex.com/) -This is an agile HTML parser that builds a read/write DOM and supports plain XPATH or XSLT ![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/android%2Bios%2Bwindows.png)

## Passbook
* [PassKitSharp](https://github.com/Redth/PassKitSharp) - PassKitSharp is a C#/.NET Library for Reading and Writing Apple PassKit files. ![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/ios.png)

## Payments
* [JudoPay](https://components.xamarin.com/view/judopay-xamarin-sdk) - Payments SDK for Xamarin.Forms. ![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images//android%2Bios.png)
* [Stripe](https://components.xamarin.com/view/stripe) - Mobile Payments built for Developers
 ![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/android%2Bios.png)
* [Xamarin.inAppBilling](https://components.xamarin.com/view/xamarin.inappbilling) - Component to assist in adding In-App Billing to a Xamarin.Android application via Google Play Services.![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/android.png)
* [PayPal.Forms](https://github.com/AlejandroRuiz/PayPal.Forms) - PayPal Plugin for Xamarin.Forms ![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/android%2Bios.png)

## Permissions
* [PermissionsPlugin](https://github.com/jamesmontemagno/PermissionsPlugin) - Simple cross platform plugin to request and check permissions. ![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/android%2Bios%2Bwindows.png)

## Reactive Programming
* [ReactiveUI](https://github.com/reactiveui/ReactiveUI) - A MVVM framework that integrates with the Reactive Extensions for .NET to create elegant, testable User Interfaces that run on any mobile or desktop platform. ![alt tag](https://raw.githubusercontent.com/MarcBruins/awesome-xamarin/master/images/android%2Bios%2Bwindows.png)

## Security
* 

#### Encryption
* 

## Text
*

## Testing

#### TDD / BDD
* 

#### A/B Testing
* 

#### UI Testing
* 

#### Other Testing
* 

#### Font
* 

## UI
* 

#### Activity Indicator
* 

#### Alerts
* 

#### Badge
* 

#### Button
* 

#### Calendar
* 

#### Form & Settings
* 

#### Keyboard
*

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
* 

#### Pull to Refresh
* 

#### Rating Stars
* [

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
* 

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
* 

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
* 

#### Medium
* 

# Social Media

#### Twitter
* 


#### Facebook Groups
* 

# Podcasts
* 

# Books
* 


# Contributing and License
 * [See the guide](https://github.com/vsouza/awesome-ios/blob/master/.github/CONTRIBUTING.md)
 * Distributed under the MIT license. See LICENSE for more information.
