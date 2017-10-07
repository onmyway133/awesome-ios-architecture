# 𝙛𝙖𝙣𝙩𝙖𝙨𝙩𝙞𝙘 𝙞𝙤𝙨 𝙖𝙧𝙘𝙝𝙞𝙩𝙚𝙘𝙩𝙪𝙧𝙚
Better ways to structure apps

![](Screenshots/Banner.png)

Content
==

<!-- TOC depthFrom:1 depthTo:6 withLinks:1 updateOnSave:1 orderedList:0 -->

- [General](#general)
- [Clean Architecture](#clean-architecture)
- [Unidirectional Data Flow](#unidirectional-data-flow)
- [MVC](#mvc)
- [VIPER](#viper)
- [MVVM](#mvvm)
- [Data Source](#data-source)
- [Sync](#sync)
- [Cache](#cache)
- [Asynchronous Programming](#asynchronous-programming)
- [Navigation](#navigation)

<!-- /TOC -->

# General

### Posts

- [Clean Cocoa](http://www.fantageek.com/blog/2015/12/03/clean-cocoa/) :star:
- [iOS Development: You're Doing It Wrong](http://doing-it-wrong.mikeweller.com/2013/06/ios-app-architecture-and-tdd-1.html)
- [How to separate view controllers from their view logic](http://jpellat.com/how-to-separate-view-controllers-from-his-view-logic/)
- [8 Patterns to Help You Destroy Massive View Controller](http://khanlou.com/2014/09/8-patterns-to-help-you-destroy-massive-view-controller/)
- [API Design](http://mattgemmell.com/api-design/)
- [Intentions](http://chris.eidhof.nl/posts/intentions.html)
- [Model-View-ViewModel for iOS](http://www.teehanlax.com/blog/model-view-viewmodel-for-ios/)
- [Singletons, AppDelegates and top-level data.](http://www.cocoawithlove.com/2008/11/singletons-appdelegates-and-top-level.html)
- [Collection Extensions](http://kickingbear.com/blog/archives/9)
- [Model View Controller Presenter](https://medium.com/ios-apprentice/model-view-controller-presenter-8bb4149fa5ef)
- [Model View Whatever](http://khanlou.com/2014/03/model-view-whatever/)
- [How We Modularized Medium’s iOS codebase](https://medium.com/medium-eng/how-we-modularized-mediums-ios-codebase-8f8f26965c76)
- [Lighter View Controller Swift](http://blog.vikingosegundo.de/2014/06/16/lighter-view-controller-swift/)
- [Improve your iOS Architecture with FlowControllers](http://merowing.info/2016/01/improve-your-ios-architecture-with-flowcontrollers/)
- [Massive View Controller](http://khanlou.com/2015/12/massive-view-controller/)
- [Modern application architectures (Reactive programming, MVVM and beyond)](https://slack-files.com/T051G5Y6D-F0HABHKDK-8e9141e191)
- [“Tree of Models” as an Alternative App Architecture Model](https://yalantis.com/blog/tree-of-models-as-an-alternative-app-architecture-model/) :star:
- [A composable pattern for pure state machines with effects](https://gist.github.com/andymatuschak/d5f0a8730ad601bcccae97e8398e25b2)
- [Architectures comparison](https://swifting.io/blog/2016/09/07/architecture-wars-a-new-hope/)
- [Basecamp 3 for iOS: Hybrid Architecture](https://m.signalvnoise.com/basecamp-3-for-ios-hybrid-architecture-afc071589c25)
- [Highly maintainable app architecture](http://aplus.rs/2017/highly-maintainable-app-architecture/) :star:
- [Everyone is an API designer](https://vimeo.com/234961067) :rocket:
- [Driving view state through data](https://academy.realm.io/posts/try-swift-nyc-2017-matt-gallagher-driving-view-state-through-data/)
- [Architecture Wars – A New Hope](https://swifting.io/blog/2016/09/07/architecture-wars-a-new-hope/)
- [Improving Existing Apps with Modern Best Practices](https://developer.apple.com/videos/play/wwdc2016/213/) :rocket:
 
### AppDelegate

- [SERVICE-ORIENTED APPDELEGATE](http://sizeof.io/service-oriented-appdelegate/)
- [Lighter AppDelegate](http://www.fantageek.com/blog/2015/10/31/lighter-appdelegate/)
- [Service-oriented AppDelegate](https://medium.com/ios-os-x-development/pluggableapplicationdelegate-e50b2c5d97dd#.scovfjixy)

### Videos

- [Platformizing UI code](https://www.youtube.com/watch?v=TCPWckSi0Xs&feature=youtu.be)
- [The State of Statelessness](https://realm.io/news/pragma-hannes-verlinde-statelessness-react-native/)
- [Good iOS Application Architecture](https://academy.realm.io/posts/krzysztof-zablocki-mDevCamp-ios-architecture-mvvm-mvc-viper) :rocket:

### Misc

- [Logician](https://github.com/mdiep/Logician) Logic programming in Swift
- [modular-architecture](https://github.com/bricepollock/modular-architecture) Examples of iOS Modular Architecture in Swift
- [Delta](https://github.com/thoughtbot/Delta) Delta takes an app that has custom state management spread throughout all the VCs and simplifies it by providing a simple interface to change state and subscribe to its changes.
- [eigen](https://github.com/artsy/eigen/blob/master/docs/overview.md) The Art World in Your Pocket or Your Trendy Tech Company's Tote, Artsy's iOS app
- [ENGINEERING THE ARCHITECTURE BEHIND UBER’S NEW RIDER APP](https://eng.uber.com/new-rider-app/)

# Clean Architecture

### Posts

- [Clean Swift iOS Architecture for Fixing Massive View Controller](http://clean-swift.com/clean-swift-ios-architecture/)

### Repos

- [CleanStore](https://github.com/Clean-Swift/CleanStore) A sample iOS app built using the Clean Swift architecture
- [CleanArchitectureRxSwift](https://github.com/sergdort/CleanArchitectureRxSwift) Example of Clean Architecture of iOS app using RxSwift :rocket:

# Unidirectional Data Flow

### Posts

- [Unidirectional Data Flow in Swift: An Alternative to Massive View Controllers](https://realm.io/news/benji-encz-unidirectional-data-flow-swift/)
- [Ziggurat iOS App Architecture](https://corner.squareup.com/2015/12/ziggurat-ios-app-architecture.html)
- [ziggurat](https://github.com/alanf/ziggurat) App architecture with one-way data data flow and view models
- [Rethinking iOS App Architecture Using a One Way Data Flow](https://www.youtube.com/watch?v=4cP1p5VOrSI)
- [Elmification of Swift](https://medium.com/design-x-code/elmification-of-swift-af14b7f92b30#.7twj79puf)
- [StateView](https://github.com/sahandnayebaziz/StateView) Views that automatically update themselves.
- [Render](https://github.com/alexdrone/Render) Swift and UIKit a la React.
- [Real World Flux Architecture on iOS](http://blog.benjamin-encz.de/post/real-world-flux-ios/) :star:
- [Turning UIKit Inside Out](https://realm.io/news/altconf-benji-encz-uikit-inside-out-declarative-programming) :star:
- [App Coordinators and Redux on iOS](http://willowtreeapps.com/ideas/app-coordinators-and-redux-on-ios/)
- [ReSwift Tutorial: Memory Game App](https://www.raywenderlich.com/155815/reswift-tutorial-memory-game-app)
- [App Coordinators and Redux on iOS](https://willowtreeapps.com/ideas/app-coordinators-and-redux-on-ios/)
- [Building a Unidirectional Data Flow App in Swift with Realm](https://realm.io/news/unidirectional-data-flow-in-swift/)
- [Architecture Thoughts: Migrating Marvel's iOS App to ReSwift ..](https://medium.com/cocoaacademymag/architecture-thoughts-migrating-marvels-ios-app-to-reswift-ef7f20e84e60)

### Repos

- [ReSwift](https://github.com/ReSwift/ReSwift) Unidirectional Data Flow in Swift - Inspired by Redux :star::star::star:
- [Reactor](https://github.com/jarsen/Reactor) Unidirectional data flow in Swift
- [Aftermath](https://github.com/hyperoslo/Aftermath) Stateless message-driven micro-framework in Swift. :star::star:
- [Renderer](https://github.com/alexdrone/Render) Swift and UIKit a la React.
- [Few.swift](https://github.com/joshaber/Few.swift) Views as functions of their state.
- [SwiftFlux](https://github.com/yonekawa/SwiftFlux) A type-safe Flux implementation for Swift
- [katana-swift](https://github.com/BendingSpoons/katana-swift) Swift Apps in a Swoosh
- [Dispatch](https://github.com/alexdrone/Dispatch) Multi-store Flux implementation in Swift.
- [ReactorKit](https://github.com/ReactorKit/ReactorKit) A framework for reactive and unidirectional Swift application architecture :rocket: :rocket:
- [RxFeedback](https://github.com/kzaher/RxFeedback) Architecture for RxSwift
- [tea-in-swift](https://github.com/chriseidhof/tea-in-swift) The Elm Architecture in Swift
- [Suas-iOS](https://github.com/zendesk/Suas-iOS) Unidirectional data flow architecture implementation for iOS, macOS, tvOS and watchOS http://suas.readme.io

# MVC

### Posts

- [Looking at Model-View-Controller in Cocoa](https://www.cocoawithlove.com/blog/mvc-and-cocoa.html)
- [Do MVC like it’s 1979](https://badootech.badoo.com/do-mvc-like-its-1979-da62304f6568)

# VIPER

### Posts

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
- [ARCHITECTING MOBILE APPS WITH (B)VIPER MODULES - A STRUCTURED ENGINEERING APPROACH FOR BIG MOBILE APPS](http://www.mttnow.com/blog/architecting-mobile-apps-with-bviper-modules)
- [Clean Architecture - VIPER at Redbooth](https://speakerdeck.com/sergigracia/clean-architecture-viper) by [@sergigracia](https://twitter.com/sergigracia)
- [VIPER to be or not to be](https://swifting.io/blog/2016/03/07/8-viper-to-be-or-not-to-be/)
- [Building iOS App With VIPER Architecture](https://blog.mindorks.com/building-ios-app-with-viper-architecture-8109acc72227)
- [Viper Framework for iOS using Swift v3](https://github.com/ferranabello/Viperit)
- [VIPER-S: WRITING YOUR OWN ARCHITECTURE AND UNDERSTAND ITS IMPORTANCE (PART 3)](http://www.thinkandbuild.it/viper-s-writing-your-own-architecture-and-understand-its-importance-part-3/)
- [Facing the VIPER](https://vimeo.com/album/4786409/video/235312913)

### Repos

- [iOS-Viper-Architecture](https://github.com/MindorksOpenSource/iOS-Viper-Architecture) A detailed sample app that implements VIPER architecture
- [iOSSwiftStarter](https://github.com/RoRoche/iOSSwiftStarter) A sample iOS app written in Swift using the VIPER architecture. 

# MVVM

### Posts

- [Introduction to MVVM](https://www.objc.io/issues/13-architecture/mvvm/)
- [MVVM is Not Very Good](http://khanlou.com/2015/12/mvvm-is-not-very-good/)
- [Simplification Of IOS View Controllers: MVVM Or Presentation Controls?](http://blog.xebia.com/simplification-of-ios-view-controllers-mvvm-or-presentation-controls/)
- [On MVVM, and Architecture Questions](http://twocentstudios.com/2014/06/08/on-mvvm-and-architecture-questions/)
- [Reddit-MVVM-Benchmark](https://github.com/ivanbruel/Reddit-MVVM-Benchmark) MVVM with FRP Benchmark project
- [The MVVM Pattern for iOS Apps in Swift: a Pragmatic Approach](http://matteomanferdini.com/mvvm-pattern-ios-swift/)
- [MVVM Is Quite Okay at What It Is Supposed to Do](https://christiantietze.de/posts/2016/08/mvvm-is-okay-for-what-it-does/)
- [MVVM-C In Practice](https://www.youtube.com/watch?v=9VojuJpUuE8)
- [MVVM in Practice - RWDevCon Session](https://www.youtube.com/watch?v=sWx8TtRBOfk)
- [View Models at Kickstarter ](https://talk.objc.io/episodes/S01E47-view-models-at-kickstarter)

### Repos

- [TheReactiveArchitecture](https://github.com/devxoul/TheReactiveArchitecture) The modern and reactive architecture for RxSwift application
- [kickstarter vm structure](https://github.com/kickstarter/native-docs/blob/master/vm-structure.md) Rx input and output
- [Coordinator-MVVM-Rx-Example](https://github.com/uptechteam/Coordinator-MVVM-Rx-Example) Example of MVVM-C architecture implemented with RxSwift

# Data Source

### Posts

- [Lightweight iOS View Controllers](https://yalantis.com/blog/lightweight-ios-view-controllers-separate-data-sources-guided-mvc/)
- [Apple’s Take on App Architecture](http://oleb.net/blog/2014/06/apples-take-on-app-architecture/)
- [Fluent Pagination - no more jumpy scrolling](http://www.iosnomad.com/blog/2014/4/21/fluent-pagination)
- [AdvancedCollectionView](https://github.com/zwaldowski/AdvancedCollectionView)
- [iOS: UITableView controller](http://gosuwachu.io/2014/01/12/uitableview-controller/)
- [Nestable](http://khanlou.com/2015/04/nestable/)
- [Advanced UITableViews Made Simple: YLTableView](http://engineeringblog.yelp.com/2015/06/advanced-uitableviews-made-simple-yltableview.html)
- [Typed, yet Flexible Table View Controller](http://holko.pl/2016/01/05/typed-table-view-controller/)
- [Complex table view state changes made easy](https://engineering.kitchenstories.io/this-simple-trick-will-change-how-you-think-about-table-views-706193654974#.raaqvz1yi)


### Videos

- [UMT2016 - John Sundell - Building component-driven UIs at Spotify](https://www.youtube.com/watch?v=vuCfKjOwZdU&feature=youtu.be)
- [Refactoring at Scale – Lessons Learned Rewriting Instagram’s Feed](https://realm.io/news/tryswift-ryan-nystrom-refactoring-at-scale-lessons-learned-rewriting-instagram-feed/)

### Repos

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
- [ComponentKit](https://github.com/facebook/componentkit) A React-inspired view framework for iOS
- [IGListKit](https://github.com/instagram/IGListKit) A data-driven UICollectionView framework for building fast and flexible lists. :star::star::star:
- [JASONETTE-iOS](https://github.com/Jasonette/JASONETTE-iOS) Native App over HTTP :star::star::rocket:
- [StatefulViewController](https://github.com/aschuch/StatefulViewController) Placeholder views based on content, loading, error or empty states
- [StackScrollView](https://github.com/muukii/StackScrollView) iOS Form UI Builder in Swift (powered by UICollectionView)
- [ScrollingStackViewController](https://github.com/justeat/ScrollingStackViewController) A view controller that uses root views of child view controllers as views in a UIStackView.
- [ScrollingStackContainer](https://github.com/malcommac/ScrollingStackContainer) Efficient Scrolling UIStackView in Swift

# Sync

### Posts

- [Introducing the Realm Mobile Platform: Realtime Sync Plus Fully Open Source Databas](https://realm.io/news/introducing-realm-mobile-platform/)

### Repos

- [wire-ios-sync-engine](https://github.com/wireapp/wire-ios-sync-engine) iOS synchronization library for Wire

# Cache

### Posts

- [MVC-RS](https://medium.com/swift-programming/mvc-rs-8780e73e9ff4)
- [The Missing Light Persistence Layer for Swift](https://medium.com/ios-os-x-development/the-missing-light-persistence-layer-for-swift-35ce75d02d47)
- [How to Abstract Your Persistence Layer and Migrate to Another One on iOS With JustPersist](http://albertodebortoli.com/blog/2017/03/02/How-to-abstract-your-persistence-layer-and-migrate-to-another-one-on-iOS-with-JustPersist/)
- [The Flat Cache](http://khanlou.com/2017/10/the-flat-cache/)

### Repos

- [Cache](https://github.com/hyperoslo/Cache) Nothing but Cache
- [RocketData](https://github.com/linkedin/RocketData)
- [Managing Consistency of Immutable Models](https://realm.io/news/slug-peter-livesey-managing-consistency-immutable-models/)
- [CTPersistance](https://github.com/casatwy/CTPersistance)
- [JustPersist](https://github.com/justeat/JustPersist)
- [Pantry](https://github.com/nickoneill/Pantry)

# Asynchronous Programming

### Posts

- [Comparative Asynchronous Programming](https://ashfurrow.com/blog/comparative-asynchronous-programming/)
- [Thinking in RxSwift](http://adamborek.com/thinking-rxswift/)
- [Reducers](http://chris.eidhof.nl/post/reducers/)

### Repos

- [RxSwift](https://github.com/ReactiveX/RxSwift) Reactive Programming in Swift
- [Operations](https://github.com/danthorpe/Operations) A Swift framework inspired by WWDC 2015 Advanced NSOperations session.

# Navigation

### Posts

- [Coordinators Redux](http://khanlou.com/2015/10/coordinators-redux/)
- [Deep links with no brainer](http://ilya.puchka.me/deeplinks-no-brainer/)
- [Flow Controllers on iOS for a Better Navigation Control](http://albertodebortoli.github.io/blog/2014/09/03/flow-controllers-on-ios-for-a-better-navigation-control/)
- [Improve your iOS Architecture with FlowControllers](http://merowing.info/2016/01/improve-your-ios-architecture-with-flowcontrollers/)
- [Coordinators Essential tutorial](https://medium.com/blacklane-engineering/coordinators-essential-tutorial-part-i-376c836e9ba7)
- [MVVM-C A simple way to navigate](http://tech.trivago.com/2016/08/26/mvvm-c-a-simple-way-to-navigate/)

### Repos

- [Compass](https://github.com/hyperoslo/Compass) Compass helps you setup a central navigation system for your application 

Licence
--
This project is released under the MIT license. See LICENSE.md.
