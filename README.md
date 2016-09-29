fantastic-ios-architecture
==
Better ways to structure apps

![](Screenshots/Banner.png)

Content
==

<!-- TOC depthFrom:1 depthTo:6 withLinks:1 updateOnSave:1 orderedList:0 -->

- [General](#general)
	- [Posts](#posts)
	- [Videos](#videos)
	- [Unidirectional Data Flow](#unidirectional-data-flow)
	- [VIPER](#viper)
	- [MVVM](#mvvm)
	- [Frameworks](#frameworks)
	- [Repos](#repos)
- [Data Source](#data-source)
	- [Posts](#posts)
	- [Repos](#repos)

<!-- /TOC -->

# General

## Posts

- [Clean Cocoa](http://www.fantageek.com/blog/2015/12/03/clean-cocoa/) :star:
- [Flow Controllers on iOS for a Better Navigation Control](http://albertodebortoli.github.io/blog/2014/09/03/flow-controllers-on-ios-for-a-better-navigation-control/)
- [iOS Development: You're Doing It Wrong](http://doing-it-wrong.mikeweller.com/2013/06/ios-app-architecture-and-tdd-1.html)
- [How to separate view controllers from their view logic](http://jpellat.com/how-to-separate-view-controllers-from-his-view-logic/)
- [8 Patterns to Help You Destroy Massive View Controller](http://khanlou.com/2014/09/8-patterns-to-help-you-destroy-massive-view-controller/)
- [API Design](http://mattgemmell.com/api-design/)
- [Intentions](http://chris.eidhof.nl/posts/intentions.html)
- [Model-View-ViewModel for iOS](http://www.teehanlax.com/blog/model-view-viewmodel-for-ios/)
- [Singletons, AppDelegates and top-level data.](http://www.cocoawithlove.com/2008/11/singletons-appdelegates-and-top-level.html)
- [Collection Extensions](http://kickingbear.com/blog/archives/9)
- [SERVICE-ORIENTED APPDELEGATE](http://sizeof.io/service-oriented-appdelegate/)
- [Model View Controller Presenter](https://medium.com/ios-apprentice/model-view-controller-presenter-8bb4149fa5ef)
- [Model View Whatever](http://khanlou.com/2014/03/model-view-whatever/)
- [How We Modularized Medium’s iOS codebase](https://medium.com/medium-eng/how-we-modularized-mediums-ios-codebase-8f8f26965c76)
- [Lighter View Controller Swift](http://blog.vikingosegundo.de/2014/06/16/lighter-view-controller-swift/)
- [Improve your iOS Architecture with FlowControllers](http://merowing.info/2016/01/improve-your-ios-architecture-with-flowcontrollers/)
- [Massive View Controller](http://khanlou.com/2015/12/massive-view-controller/)
- [Lighter AppDelegate](http://www.fantageek.com/blog/2015/10/31/lighter-appdelegate/)
- [Clean Swift iOS Architecture for Fixing Massive View Controller](http://clean-swift.com/clean-swift-ios-architecture/)
- [Modern application architectures (Reactive programming, MVVM and beyond)](https://slack-files.com/T051G5Y6D-F0HABHKDK-8e9141e191)
- [“Tree of Models” as an Alternative App Architecture Model](https://yalantis.com/blog/tree-of-models-as-an-alternative-app-architecture-model/) :star:
- [A composable pattern for pure state machines with effects](https://gist.github.com/andymatuschak/d5f0a8730ad601bcccae97e8398e25b2)
- [MVVM Is Quite Okay at What It Is Supposed to Do](https://christiantietze.de/posts/2016/08/mvvm-is-okay-for-what-it-does/)

## Videos

- [Platformizing UI code](https://www.youtube.com/watch?v=TCPWckSi0Xs&feature=youtu.be)
- [The State of Statelessness](https://realm.io/news/pragma-hannes-verlinde-statelessness-react-native/)
- [Good iOS Application Architecture](http://slideslive.com/38897361/good-ios-application-architecture-en)

## Unidirectional Data Flow

- [Unidirectional Data Flow in Swift: An Alternative to Massive View Controllers](https://realm.io/news/benji-encz-unidirectional-data-flow-swift/)
- [ReSwift](https://github.com/ReSwift/ReSwift) Unidirectional Data Flow in Swift - Inspired by Redux
- [Ziggurat iOS App Architecture](https://corner.squareup.com/2015/12/ziggurat-ios-app-architecture.html)
- [ziggurat](https://github.com/alanf/ziggurat) App architecture with one-way data data flow and view models
- [Rethinking iOS App Architecture Using a One Way Data Flow](https://www.youtube.com/watch?v=4cP1p5VOrSI)
- [Elmification of Swift](https://medium.com/design-x-code/elmification-of-swift-af14b7f92b30#.7twj79puf)
- [StateView](https://github.com/sahandnayebaziz/StateView) Views that automatically update themselves.
- [Render](https://github.com/alexdrone/Render) Swift and UIKit a la React.
- [Real World Flux Architecture on iOS](http://blog.benjamin-encz.de/post/real-world-flux-ios/) :star:
- [Turning UIKit Inside Out](https://realm.io/news/altconf-benji-encz-uikit-inside-out-declarative-programming) :star:
- [Few.swift](https://github.com/joshaber/Few.swift) Views as functions of their state.
- [Aftermath](https://github.com/hyperoslo/Aftermath) Stateless message-driven micro-framework in Swift.
- [Renderer](https://github.com/alexdrone/Render) Swift and UIKit a la React.

## VIPER

- [Introduction to VIPER](http://mutualmobile.github.io/blog/2013/12/04/viper-introduction/)
- [Architecting iOS Apps with VIPER](http://www.objc.io/issues/13-architecture/viper/)
- [Brigade’s Experience Using an MVC Alternative](https://medium.com/brigade-engineering/brigades-experience-using-an-mvc-alternative-36ef1601a41f)
- [First Observations on TDD with VIPER](http://iosunittesting.com/tdd-with-viper/)
- [Building Modular iOS Apps](https://realm.io/news/modular-ios-apps/)
- [iPhreaks Show – VIPER with Conrad Stoll and Jeff Gilbert](http://devchat.tv/iphreaks/064-iphreaks-show-viper-with-conrad-stoll-and-jeff-gilbert)
- [Clean Architecture - VIPER by Redbooth](https://www.youtube.com/watch?v=OX4rLAJC7lw)
- [250 Days Shipping With Swift and VIPER](https://realm.io/news/altconf-brice-pollock-250-days-shipping-with-swift-and-viper/)
- [IOS ARCHITECTURE: REAL LIFE VIPER](http://www.outware.com.au/insights/ios-architecture-real-life-viper/)
- [Humble Object Pattern in Swift](https://medium.com/ios-os-x-development/humble-object-pattern-in-swift-de5efe8fe05a#.dmkvdbjoy)
- [iOS Architecture Patterns Demystifying MVC, MVP, MVVM and VIPER](https://medium.com/ios-os-x-development/ios-architecture-patterns-ecba4c38de52#.tliwdfd60)
- [Should I use Viper architecture for my next iOS application, or it is still very new to use?](https://www.quora.com/Should-I-use-Viper-architecture-for-my-next-iOS-application-or-it-is-still-very-new-to-use)
- [VIPER to be or not to be?](https://swifting.io/blog/2016/03/07/8-viper-to-be-or-not-to-be/)
- [iOS Project Architecture: Using VIPER](https://www.ckl.io/blog/ios-project-architecture-using-viper/)
- [iOSModulesArchitecture](https://github.com/JeanLebrument/iOSModulesArchitecture) Quick example of how divide an app into modules to respect the SOLID principles

## MVVM

- [Introduction to MVVM](https://www.objc.io/issues/13-architecture/mvvm/)
- [MVVM is Not Very Good](http://khanlou.com/2015/12/mvvm-is-not-very-good/)
- [Simplification Of IOS View Controllers: MVVM Or Presentation Controls?](http://blog.xebia.com/simplification-of-ios-view-controllers-mvvm-or-presentation-controls/)
- [On MVVM, and Architecture Questions](http://twocentstudios.com/2014/06/08/on-mvvm-and-architecture-questions/)
- [Reddit-MVVM-Benchmark](https://github.com/ivanbruel/Reddit-MVVM-Benchmark) MVVM with FRP Benchmark project


## Frameworks

- [RxSwift](https://github.com/ReactiveX/RxSwift) Reactive Programming in Swift
- [Operations](https://github.com/danthorpe/Operations) A Swift framework inspired by WWDC 2015 Advanced NSOperations session.

## Repos

- [modular-architecture](https://github.com/bricepollock/modular-architecture) Examples of iOS Modular Architecture in Swift
- [CleanStore](https://github.com/Clean-Swift/CleanStore) A sample iOS app built using the Clean Swift architecture
- [Delta](https://github.com/thoughtbot/Delta) Delta takes an app that has custom state management spread throughout all the VCs and simplifies it by providing a simple interface to change state and subscribe to its changes.
- [eigen](https://github.com/artsy/eigen/blob/master/docs/overview.md) The Art World in Your Pocket or Your Trendy Tech Company's Tote, Artsy's iOS app

# Data Source

## Posts

- [Lightweight iOS View Controllers](https://yalantis.com/blog/lightweight-ios-view-controllers-separate-data-sources-guided-mvc/)
- [Apple’s Take on App Architecture](http://oleb.net/blog/2014/06/apples-take-on-app-architecture/)
- [Fluent Pagination - no more jumpy scrolling](http://www.iosnomad.com/blog/2014/4/21/fluent-pagination)
- [AdvancedCollectionView](https://github.com/zwaldowski/AdvancedCollectionView)
- [iOS: UITableView controller](http://blog.mobiledev.pl/2014/01/12/uitableview-controller/)
- [Nestable](http://khanlou.com/2015/04/nestable/)
- [Advanced UITableViews Made Simple: YLTableView](http://engineeringblog.yelp.com/2015/06/advanced-uitableviews-made-simple-yltableview.html)
- [Typed, yet Flexible Table View Controller](http://holko.pl/2016/01/05/typed-table-view-controller/)
- [Complex table view state changes made easy](https://engineering.kitchenstories.io/this-simple-trick-will-change-how-you-think-about-table-views-706193654974#.raaqvz1yi)


## Videos

- [UMT2016 - John Sundell - Building component-driven UIs at Spotify](https://www.youtube.com/watch?v=vuCfKjOwZdU&feature=youtu.be)

## Repos

- [Mensa](https://github.com/jordanekay/Mensa) Smart, modern table and collection views on iOS.
- [RLDTableViewSuite](https://github.com/rlopezdiez/RLDTableViewSuite) Reusable table view controller, data source and delegate for all your UITableView needs
- [PagedArray](https://github.com/MrAlek/PagedArray) A Swift data structure for easier pagination
- [ReadingList](https://github.com/gonzalezreal/ReadingList) An example on using the Mantle Modeling Framework with Overcoat AFNetworking extension.
- [DTTableViewManager](https://github.com/DenHeadless/DTTableViewManager) Protocol-oriented UITableView management, powered by generics and associated types.
- [StatefulViewController](https://github.com/aschuch/StatefulViewController) Placeholder views based on content, loading, error or empty states
- [Spots](https://github.com/hyperoslo/Spots) Spots is a view controller framework that makes your setup and future development blazingly fast :star::star:
- [JSQDataSourcesKit](https://github.com/jessesquires/JSQDataSourcesKit) Type-safe, value-oriented, composable data source objects that keep your view controllers light
- [AutoTablel](https://github.com/ben-g/autotable) Demonstration of wrapping a UIKit API into a declarative API Layer
- [HubFramework](https://github.com/spotify/HubFramework) Spotify’s component-driven UI framework for iOS :star::star::star:

Licence
--
This project is released under the MIT license. See LICENSE.md.
