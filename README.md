# awesome iOS architecture [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

❤️ Support my apps ❤️ 

- [Push Hero - pure Swift native macOS application to test push notifications](https://onmyway133.com/pushhero)
- [PastePal - Pasteboard, note and shortcut manager](https://onmyway133.com/pastepal)
- [Quick Check - smart todo manager](https://onmyway133.com/quickcheck)
- [Alias - App and file shortcut manager](https://onmyway133.com/alias)
- [My other apps](https://onmyway133.com/apps/)

❤️❤️😇😍🤘❤️❤️

Better ways to structure apps

![](Screenshots/Banner.png)

```swift
let buzzWords = [
  "Model", "View", "Controller", "Entity", "Router", "Clean", "Reactive", 
  "Presenter", "Interactor", "Megatron", "Coordinator", "Flow", "Manager"
]
let architecture = buzzWords.shuffled().takeRandom()
let acronym = architecture.makeAcronym()
```

Content
==

- [MVC](#mvc)
- [MVP](#mvp)
- [MVVM](#mvvm)
- [Composable Archiecture](#composable-architecture)
- [Clean Architecture](#clean-architecture)
- [Unidirectional Data Flow](#unidirectional-data-flow)
- [VIPER](#viper)
- [VIP](#vip)
- [SwiftUI](#swiftui)
- [Data Source](#data-source)
- [Best Practices](#best-practices)


# MVC
Model View Controller

### Posts

- [Model-View-Controller, Apple Docs](https://developer.apple.com/library/content/documentation/General/Conceptual/CocoaEncyclopedia/Model-View-Controller/Model-View-Controller.html)
- [Looking at Model-View-Controller in Cocoa](https://www.cocoawithlove.com/blog/mvc-and-cocoa.html)
- [Do MVC like it’s 1979](https://badootech.badoo.com/do-mvc-like-its-1979-da62304f6568)
- [A Better MVC, Part 1: The Problems](https://davedelong.com/blog/2017/11/06/a-better-mvc-part-1-the-problems/) :rocket:
- [Using child view controllers as plugins in Swift](https://www.swiftbysundell.com/posts/using-child-view-controllers-as-plugins-in-swift)
- [MVC.](http://codeplease.io/2017/11/19/mvc/)
- [Model-View-Controller without the Controller](https://www.cocoawithlove.com/blog/mvc-without-the-c.html)
- [Just Controllers](http://khanlou.com/2018/02/just-controllers/)
- [A Better MVC](https://www.youtube.com/watch?v=YWVzCd5FYbs)
- [MVC: Many View Controllers](https://www.youtube.com/watch?v=ZShE3toDPIk)

### Repos

- [MVCTodo](https://github.com/davedelong/MVCTodo) A very simple "To Do" app to illustrate the principles from my "A Better MVC" talk

# MVP
Model View Presenter

### Posts

- [A dumb UI is a good UI: Using MVP in iOS with swift](http://iyadagha.com/using-mvp-ios-swift/)
- [Going from MVC to MVP on iOS](https://blog.moove-it.com/going-from-mvc-to-mvp-on-ios/)

### Repos

- [AppDemo](https://github.com/SSamanta/AppDemo)
- [foodMVP](https://github.com/voghDev/foodMVP)
- [ios-mvp-clean-architecture](https://github.com/FortechRomania/ios-mvp-clean-architecture)
- [iOS_MVC_MVP_MVVM_SampleApp](https://github.com/rajagp/iOS_MVC_MVP_MVVM_SampleApp)
- [MVP-iOS](https://github.com/Quaggie/MVP-iOS)
- [MVP-iOS](https://github.com/baoshanf/MVP-iOS)
- [MVPExample](https://github.com/amacou/MVPExample)
- [MVP](https://github.com/shuilinok/MVP)

# MVVM
Model View ViewModel

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
- [How not to get desperate with MVVM implementation](https://medium.com/flawless-app-stories/how-to-use-a-model-view-viewmodel-architecture-for-ios-46963c67be1b)
- [iOS Architecture: A State Container based approach](https://jobandtalent.engineering/ios-architecture-an-state-container-based-approach-4f1a9b00b82e) :rocket:
- [Different flavors of view models in Swift](https://www.swiftbysundell.com/posts/different-flavors-of-view-models-in-swift)
- [Reactive view models, simplified](https://www.youtube.com/watch?v=uTLG_LgjWGA)

### Repos

- [TheReactiveArchitecture](https://github.com/devxoul/TheReactiveArchitecture) The modern and reactive architecture for RxSwift application
- [kickstarter vm structure](https://github.com/kickstarter/native-docs/blob/master/vm-structure.md) Rx input and output
- [Coordinator-MVVM-Rx-Example](https://github.com/uptechteam/Coordinator-MVVM-Rx-Example) Example of MVVM-C architecture implemented with RxSwift
- [RxCoordinator](https://github.com/quickbirdstudios/RxCoordinator) iOS framework that helps you implement Model-View-ViewModel-Coordinator architecture.
- [ModernMVVM](https://github.com/V8tr/ModernMVVM) - A movie iOS app built with the MVVM architecture, Combine and SwiftUI frameworks

# Composable Architecture

### Repos

- [swift-composable-architecture](https://github.com/pointfreeco/swift-composable-architecture) A library for building applications in a consistent and understandable way, with composition, testing, and ergonomics in mind.

# Clean Architecture

### Posts

- [Clean Swift iOS Architecture for Fixing Massive View Controller](http://clean-swift.com/clean-swift-ios-architecture/)

### Repos

- [CleanStore](https://github.com/Clean-Swift/CleanStore) A sample iOS app built using the Clean Swift architecture
- [CleanArchitectureRxSwift](https://github.com/sergdort/CleanArchitectureRxSwift) Example of Clean Architecture of iOS app using RxSwift :rocket:
- [Reminders](https://github.com/tiagomartinho/Reminders) An iOS application written in Swift to demonstrate how to implement a Clean Architecture in iOS
- [CleanSwiftArchitectureGenerator](https://github.com/emrcftci/CleanSwiftArchitectureGenerator) A generator of Clean Swift Architecture files

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
- [Building a Unidirectional Data Flow App in Swift with Realm](https://realm.io/news/unidirectional-data-flow-in-swift/)
- [Architecture Thoughts: Migrating Marvel's iOS App to ReSwift ..](https://medium.com/cocoaacademymag/architecture-thoughts-migrating-marvels-ios-app-to-reswift-ef7f20e84e60)
- [Functional architecture for Swift](https://medium.com/@PallasR/functional-architecture-for-swift-dfa8854239cb)
- [iOS Architecture: Separating logic from effects](https://jobandtalent.engineering/ios-architecture-separating-logic-from-effects-7629cb763352) :star:

### Repos

- [ReSwift](https://github.com/ReSwift/ReSwift) Unidirectional Data Flow in Swift - Inspired by Redux :star:
- [Reactor](https://github.com/jarsen/Reactor) Unidirectional data flow in Swift
- [Aftermath](https://github.com/hyperoslo/Aftermath) Stateless message-driven micro-framework in Swift
- [Renderer](https://github.com/alexdrone/Render) Swift and UIKit a la React.
- [Few.swift](https://github.com/joshaber/Few.swift) Views as functions of their state.
- [SwiftFlux](https://github.com/yonekawa/SwiftFlux) A type-safe Flux implementation for Swift
- [katana-swift](https://github.com/BendingSpoons/katana-swift) Swift Apps in a Swoosh
- [Dispatch](https://github.com/alexdrone/Dispatch) Multi-store Flux implementation in Swift.
- [ReactorKit](https://github.com/ReactorKit/ReactorKit) A framework for reactive and unidirectional Swift application architecture :rocket: :rocket:
- [RxFeedback](https://github.com/kzaher/RxFeedback) Architecture for RxSwift
- [tea-in-swift](https://github.com/chriseidhof/tea-in-swift) The Elm Architecture in Swift
- [Suas-iOS](https://github.com/zendesk/Suas-iOS) Unidirectional data flow architecture implementation for iOS, macOS, tvOS and watchOS http://suas.readme.io
- [ReactComponentKit](https://github.com/ReactComponentKit/ReactComponentKit) ReactComponentKit is a library for building UIViewController based on Components.

# VIPER
View Interactor Presenter Entity Router

### Posts

- [Introduction to VIPER](https://github.com/strongself/The-Book-of-VIPER/blob/master/english/introduction-to-viper.md)
- [Architecting iOS Apps with VIPER](http://www.objc.io/issues/13-architecture/viper/)
- [Brigade’s Experience Using an MVC Alternative](https://medium.com/brigade-engineering/brigades-experience-using-an-mvc-alternative-36ef1601a41f)
- [First Observations on TDD with VIPER](http://iosunittesting.com/tdd-with-viper/)
- [Building Modular iOS Apps](https://realm.io/news/modular-ios-apps/)
- [iPhreaks Show – VIPER with Conrad Stoll and Jeff Gilbert](http://devchat.tv/iphreaks/064-iphreaks-show-viper-with-conrad-stoll-and-jeff-gilbert)
- [Clean Architecture - VIPER by Redbooth](https://www.youtube.com/watch?v=OX4rLAJC7lw)
- [250 Days Shipping With Swift and VIPER](https://realm.io/news/altconf-brice-pollock-250-days-shipping-with-swift-and-viper/)
- [IOS ARCHITECTURE: REAL LIFE VIPER](http://www.outware.com.au/insights/ios-architecture-real-life-viper/)
- [Humble Object Pattern in Swift](https://medium.com/ios-os-x-development/humble-object-pattern-in-swift-de5efe8fe05a#.dmkvdbjoy)
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
- [Building a Framework with VIPER](https://academy.realm.io/posts/try-swift-nyc-sonam-dhingra-building-viper-framework/)
- [Implementing VIPER Architecture Pattern for iOS](https://medium.com/flawless-app-stories/implementing-viper-archticture-pattern-for-ios-d24a6def8ba2)

### Repos

- [iOS-Viper-Architecture](https://github.com/MindorksOpenSource/iOS-Viper-Architecture) A detailed sample app that implements VIPER architecture
- [iOS Viper XCode Templates](https://github.com/infinum/iOS-VIPER-Xcode-Templates) Another detailed sample app that implements VIPER architecture with code generation templates
- [iOSSwiftStarter](https://github.com/RoRoche/iOSSwiftStarter) A sample iOS app written in Swift using the VIPER architecture. 
- [VIPER-TDD](https://github.com/hendych/VIPER-TDD/) A sample iOS app written in Swift 4 using VIPER architecture with unit tests.

# VIP
View Interactor Presenter

### Posts

- [Architecture Wars – A New Hope](https://swifting.io/blog/2016/09/07/architecture-wars-a-new-hope/)
- [Introducing Clean Swift Architecture (VIP)](https://hackernoon.com/introducing-clean-swift-architecture-vip-770a639ad7bf)

# SwiftUI

### Posts

- [SwiftUI Architectures: Model-View, Redux & MVVM](https://quickbirdstudios.com/blog/swiftui-architecture-redux-mvvm/)
- [Building a Scalable SwiftUI Architecture](https://basememara.com/building-scalable-swiftui-architecture-app/)
- [SwiftUI and State Management](https://www.pointfree.co/episodes/ep65-swiftui-and-state-management-part-1)
- [Building complex modular architectures with SwiftUI, Combine and Swift Package Manager (SPM)](https://medium.com/cristian-ortega/modular-architectures-swiftui-combine-swift-package-manager-80820b4ff463)

### Repos

- [Harvest](https://github.com/inamiy/Harvest) Harvest: Apple's Combine.framework + State Machine, inspired by Elm.

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
- [UMT2016 - John Sundell - Building component-driven UIs at Spotify](https://www.youtube.com/watch?v=vuCfKjOwZdU&feature=youtu.be)
- [Refactoring at Scale – Lessons Learned Rewriting Instagram’s Feed](https://realm.io/news/tryswift-ryan-nystrom-refactoring-at-scale-lessons-learned-rewriting-instagram-feed/)
- [IGListKit Tutorial: Better UICollectionViews](https://www.raywenderlich.com/147162/iglistkit-tutorial-better-uicollectionviews)
- [Dealing with Complex Table Views in iOS and Keeping Your Sanity](https://medium.cobeisfresh.com/dealing-with-complex-table-views-in-ios-and-keeping-your-sanity-ff5fee1fbb83)
 - [iOS: How to build a Table View with multiple cell types](https://medium.com/@stasost/ios-how-to-build-a-table-view-with-multiple-cell-types-2df91a206429)
 - [Using Dedicated Objects as Delegates & Datasources](https://alisoftware.github.io/architecture/2018/05/20/dedicated-datasources/)
 - [Reusable data sources in Swift](https://www.swiftbysundell.com/posts/reusable-data-sources-in-swift)
- [UITableView Datasource with SwiftUI-style syntax](https://medium.com/@_myrddin_/tableview-datasource-with-swiftui-style-syntax-1372b3a04687)

### Repos

- [Mensa](https://github.com/jordanekay/Mensa) Smart, modern table and collection views on iOS.
- [RLDTableViewSuite](https://github.com/rlopezdiez/RLDTableViewSuite) Reusable table view controller, data source and delegate for all your UITableView needs
- [PagedArray](https://github.com/MrAlek/PagedArray) A Swift data structure for easier pagination
- [ReadingList](https://github.com/gonzalezreal/ReadingList) An example on using the Mantle Modeling Framework with Overcoat AFNetworking extension.
- [DTTableViewManager](https://github.com/DenHeadless/DTTableViewManager) Protocol-oriented UITableView management, powered by generics and associated types.
- [Spots](https://github.com/hyperoslo/Spots) Spots is a view controller framework that makes your setup and future development blazingly fast :star:
- [JSQDataSourcesKit](https://github.com/jessesquires/JSQDataSourcesKit) Type-safe, value-oriented, composable data source objects that keep your view controllers light
- [HubFramework](https://github.com/spotify/HubFramework) Spotify’s component-driven UI framework for iOS
- [ComponentKit](https://github.com/facebook/componentkit) A React-inspired view framework for iOS
- [IGListKit](https://github.com/instagram/IGListKit) A data-driven UICollectionView framework for building fast and flexible lists.
- [JASONETTE-iOS](https://github.com/Jasonette/JASONETTE-iOS) Native App over HTTP :star::star::rocket:
- [StackScrollView](https://github.com/muukii/StackScrollView) iOS Form UI Builder in Swift (powered by UICollectionView)
- [ScrollingStackViewController](https://github.com/justeat/ScrollingStackViewController) A view controller that uses root views of child view controllers as views in a UIStackView.
- [ScrollingStackContainer](https://github.com/malcommac/ScrollingStackContainer) Efficient Scrolling UIStackView in Swift
- [Flow](https://github.com/malcommac/Flow) A new declarative approach to UITableView
- [FlowKit](https://github.com/malcommac/FlowKit) Declarative type-safe manager for UITableView & UICollectionView
- [Static](https://github.com/venmo/Static) Simple static table views for iOS in Swift.
- [Bento](https://github.com/Babylonpartners/Bento) Swift library for building component-based interfaces on top of UITableView
- [ReactiveLists](https://github.com/plangrid/ReactiveLists) React-like API for UITableView & UICollectionView
- [LiveCollections](https://github.com/scribd/LiveCollections)
- [AloeStackView](https://github.com/airbnb/AloeStackView) A simple class for laying out a collection of views with a convenient API, while leveraging the power of Auto Layout :star:
- [Carbon](https://github.com/ra1028/Carbon) A declarative library for building component-based user interfaces in UITableView and UICollectionView
- [Owl](https://github.com/malcommac/Owl) A declarative type-safe framework for building fast and flexible lists with Tables & Collections
- [Collor](https://github.com/voyages-sncf-technologies/Collor) A MVVM data-oriented framework for UICollectionView with great and useful features.
- [FunctionalTableData](https://github.com/Shopify/FunctionalTableData) Declarative UITableViewDataSource implementation
- [Upstream](https://github.com/onmyway133/Upstream) ⛲️ Adapted Data Source in Swift and a little bit more :rocket: :rocket:
- [Micro](https://github.com/onmyway133/Micro) Fast diffing and type safe SwiftUI style data source for UICollectionView :rocket: :rocket:
- [Epoxy](https://github.com/airbnb/epoxy-ios) - Epoxy is a suite of declarative UI APIs for building UIKit applications in Swift
 
# Best Practices

### General

- [Benchmarking MVC vs MVP vs MVVM in iOS](https://www.simform.com/mvc-mvp-mvvm-ios-app-development/)
- [iOS Architecture Patterns Demystifying MVC, MVP, MVVM and VIPER](https://medium.com/ios-os-x-development/ios-architecture-patterns-ecba4c38de52#.tliwdfd60) :rocket:
- [Clean Cocoa](http://www.fantageek.com/blog/2015/12/03/clean-cocoa/) :star:
- [iOS Development: You're Doing It Wrong](http://doing-it-wrong.mikeweller.com/2013/06/ios-app-architecture-and-tdd-1.html)
- [How to separate view controllers from their view logic](http://jpellat.com/how-to-separate-view-controllers-from-his-view-logic/)
- [8 Patterns to Help You Destroy Massive View Controller](http://khanlou.com/2014/09/8-patterns-to-help-you-destroy-massive-view-controller/)
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
- [Driving view state through data](https://academy.realm.io/posts/try-swift-nyc-2017-matt-gallagher-driving-view-state-through-data/)
- [Improving Existing Apps with Modern Best Practices](https://developer.apple.com/videos/play/wwdc2016/213/) :rocket:
- [Platformizing UI code](https://www.youtube.com/watch?v=TCPWckSi0Xs&feature=youtu.be)
- [The State of Statelessness](https://realm.io/news/pragma-hannes-verlinde-statelessness-react-native/)
- [Good iOS Application Architecture](https://academy.realm.io/posts/krzysztof-zablocki-mDevCamp-ios-architecture-mvvm-mvc-viper) :rocket:
- [Much ado about iOS app architecture](http://aplus.rs/2017/much-ado-about-ios-app-architecture/) :star:
- [The Presentation Model](https://medium.com/@sandofsky/the-presentation-model-6aeaaab607a0)
- [The New Swipe Right with Swift](http://tech.gotinder.com/the-new-swipe-right-with-swift/)
- [Zero Knowledge Architectures for Mobile Applications](https://medium.com/@vixentael/zero-knowledge-architectures-for-mobile-applications-b00a231fda75)
- [Top-down iOS error architecture](https://medium.com/@londeix/top-down-error-architecture-d8715a28d1ad)
- [App Architectures: Remixed](https://skillsmatter.com/skillscasts/11527-app-architectures-remixed)
- [iOS Application Architecture](https://www.youtube.com/watch?v=PdkWjdKOqfo)
- [How to move data sources and delegates out of your view controllers](https://www.hackingwithswift.com/articles/86/how-to-move-data-sources-and-delegates-out-of-your-view-controllers)
- [App Architecture and Object Composition in Swift](https://medium.com/flawless-app-stories/app-architecture-and-object-composition-in-swift-c9101a9e37e3)
- [Let's Talk Architecture](https://kean.github.io/post/app-architecture)
- [The Lost Art of System Design](https://www.youtube.com/watch?v=ujOc3a7Hav0)
- [Maintaining architecture in iOS apps](https://www.youtube.com/watch?v=kyOtj16k_lQ)
- [Four Rules of Simpler iOS Software Design](https://medium.com/flawless-app-stories/four-rules-of-simpler-ios-software-design-c371818d08e0)
- [The Art of Designing Code](https://www.youtube.com/watch?v=_qKlb7MbeKA) :star:
- [Why UI Design matters](https://www.scnsoft.com/services/ui-design)

### API Design

- [Everyone is an API designer](https://vimeo.com/234961067) :rocket:
- [Lightweight API design in Swift](https://www.swiftbysundell.com/articles/lightweight-api-design-in-swift/)
- [API Design](http://mattgemmell.com/api-design/)
- [Testable interface design with enums](https://kandelvijaya.com/2018/03/03/testableinterfacedesignwithenums/)
- [Designing Swift APIs](https://www.swiftbysundell.com/posts/designing-swift-apis)
- [Designing Accessible APIs](https://learntalks.com/try-Swift-New-York/2019/try!-Swift-New-York-2019-Designing-Accessible-APIs-Dave-DeLong/)

### Dependency Injection

- [Managing objects using Locks & Keys in Swift](https://www.swiftbysundell.com/posts/managing-objects-using-locks-and-keys-in-swift) :star:
- [How To Control The World](https://www.pointfree.co/blog/posts/21-how-to-control-the-world)
- [Structure and Interpretation of Swift Programs](https://www.youtube.com/watch?v=V-YvI83QdMs)
- [Extracting view controller actions in Swift](https://www.swiftbysundell.com/posts/extracting-view-controller-actions-in-swift)
- [Behaviors in iOS Apps](https://www.objc.io/issues/13-architecture/behaviors/)
- [Logic controllers in Swift](https://www.swiftbysundell.com/posts/logic-controllers-in-swift)
- [Model controllers in Swift](https://www.swiftbysundell.com/posts/model-controllers-in-swift)
- [Using protocol compositon for dependency injection](http://merowing.info/2017/04/using-protocol-compositon-for-dependency-injection/)
- [Cleaning up your dependencies with protocols](https://www.donnywals.com/cleaning-up-your-dependencies-with-protocols/)
- [Swift Dependency Injection via Property Wrapper](https://basememara.com/swift-dependency-injection-via-property-wrapper/)

### Refactoring

- [Similar Prefixes](http://khanlou.com/2018/08/similar-prefixes/)
- [Structuring Swift code](https://www.swiftbysundell.com/posts/structuring-swift-code)

### Model

- [Structuring model data in Swift](https://www.swiftbysundell.com/posts/structuring-model-data-in-swift)
- [Utilizing value semantics in Swift](https://www.swiftbysundell.com/posts/utilizing-value-semantics-in-swift)
- [Type safe temporary models](https://iankeen.tech/2018/06/05/type-safe-temporary-models/)
- [Defining testing data in Swift](https://swiftbysundell.com/articles/defining-testing-data-in-swift/)

### View and Model

- [View Descriptors](https://152percent.com/blog/2018/4/16/view-descriptors)
- [Preventing views from being model aware in Swift](https://www.swiftbysundell.com/posts/preventing-views-from-being-model-aware-in-swift)
- [UITableViewCell and Model](https://github.com/onmyway133/blog/issues/154)
- [Building Better Views](https://www.fabisevi.ch/2019/12/26/building-better-views-part-i/)

### AppDelegate

- [SERVICE-ORIENTED APPDELEGATE](http://sizeof.io/service-oriented-appdelegate/)
- [Lighter AppDelegate](http://www.fantageek.com/blog/2015/10/31/lighter-appdelegate/)
- [Service-oriented AppDelegate](https://medium.com/ios-os-x-development/pluggableapplicationdelegate-e50b2c5d97dd#.scovfjixy)

### Repos

- [Logician](https://github.com/mdiep/Logician) Logic programming in Swift
- [modular-architecture](https://github.com/bricepollock/modular-architecture) Examples of iOS Modular Architecture in Swift
- [Delta](https://github.com/thoughtbot/Delta) Delta takes an app that has custom state management spread throughout all the VCs and simplifies it by providing a simple interface to change state and subscribe to its changes.
- [eigen](https://github.com/artsy/eigen/blob/master/docs/overview.md) The Art World in Your Pocket or Your Trendy Tech Company's Tote, Artsy's iOS app
- [ENGINEERING THE ARCHITECTURE BEHIND UBER’S NEW RIDER APP](https://eng.uber.com/new-rider-app/)
- [RIBs](https://github.com/uber/RIBs) Uber's cross-platform mobile architecture framework.
- [Alicerce](https://github.com/Mindera/Alicerce) A base for iOS Applications by Mindera
- [Flint](https://github.com/MontanaFlossCo/Flint) The Flint framework for building apps on Apple platforms using Feature Driven Development
- [ios-architecture](https://github.com/tailec/ios-architecture) A collection of iOS architectures - MVC, MVVM, MVVM+RxSwift, VIPER, RIBs and many others
- [SwiftHub](https://github.com/khoren93/SwiftHub) GitHub iOS client in RxSwift and MVVM-C clean architecture

### Sync

- [Introducing the Realm Mobile Platform: Realtime Sync Plus Fully Open Source Databas](https://realm.io/news/introducing-realm-mobile-platform/)
- [wire-ios-sync-engine](https://github.com/wireapp/wire-ios-sync-engine) iOS synchronization library for Wire

### Cache

- [MVC-RS](https://medium.com/swift-programming/mvc-rs-8780e73e9ff4)
- [The Missing Light Persistence Layer for Swift](https://medium.com/ios-os-x-development/the-missing-light-persistence-layer-for-swift-35ce75d02d47)
- [How to Abstract Your Persistence Layer and Migrate to Another One on iOS With JustPersist](http://albertodebortoli.com/blog/2017/03/02/How-to-abstract-your-persistence-layer-and-migrate-to-another-one-on-iOS-with-JustPersist/)
- [The Flat Cache](http://khanlou.com/2017/10/the-flat-cache/)
- [Cache](https://github.com/hyperoslo/Cache) Nothing but Cache
- [RocketData](https://github.com/linkedin/RocketData)
- [Managing Consistency of Immutable Models](https://realm.io/news/slug-peter-livesey-managing-consistency-immutable-models/)
- [CTPersistance](https://github.com/casatwy/CTPersistance)
- [JustPersist](https://github.com/justeat/JustPersist)
- [Pantry](https://github.com/nickoneill/Pantry)
- [The Many Offline Options for iOS Apps](https://medium.com/device-blogs/the-many-offline-options-for-ios-apps-2922c9b3bff3)
- [How to Design Offline-first Approach in a Mobile App](https://www.netguru.com/blog/how-to-design-offline-first-approach-in-mobile-app)
- [Flannel: An Application-Level Edge Cache to Make Slack Scale](https://slack.engineering/flannel-an-application-level-edge-cache-to-make-slack-scale-b8a6400e2f6b)

### Asynchronous/Reactive Programming

- [Comparative Asynchronous Programming](https://ashfurrow.com/blog/comparative-asynchronous-programming/)
- [Thinking in RxSwift](http://adamborek.com/thinking-rxswift/)
- [Reducers](http://chris.eidhof.nl/post/reducers/)
- [RxSwift](https://github.com/ReactiveX/RxSwift) Reactive Programming in Swift
- [Operations](https://github.com/danthorpe/Operations) A Swift framework inspired by WWDC 2015 Advanced NSOperations session.
- [Modern RxSwift Architectures](https://academy.realm.io/posts/try-swift-nyc-2017-krunoslav-zaher-modern-rxswift-architectures/)
- [Architecturing an app with functional reactive programming](https://www.welcometothejungle.co/fr/articles/functional-reactive-programming-architecture)
- [TheBinderArchitecture](https://github.com/DeclarativeHub/TheBinderArchitecture) A declarative architecture based on bindings

### Navigation/Coordinator/FlowController

- [Coordinators Redux](http://khanlou.com/2015/10/coordinators-redux/)
- [Deep links with no brainer](http://ilya.puchka.me/deeplinks-no-brainer/)
- [Flow Controllers on iOS for a Better Navigation Control](http://albertodebortoli.github.io/blog/2014/09/03/flow-controllers-on-ios-for-a-better-navigation-control/)
- [Improve your iOS Architecture with FlowControllers](http://merowing.info/2016/01/improve-your-ios-architecture-with-flowcontrollers/)
- [Coordinators Essential tutorial](https://medium.com/blacklane-engineering/coordinators-essential-tutorial-part-i-376c836e9ba7)
- [MVVM-C A simple way to navigate](http://tech.trivago.com/2016/08/26/mvvm-c-a-simple-way-to-navigate/)
- [Compass](https://github.com/hyperoslo/Compass) Compass helps you setup a central navigation system for your application 
- [Deep Linking at Kickstarter](https://talk.objc.io/episodes/S01E49-deep-linking-at-kickstarter)
- [One navigator to rule them all - iOS Conf SG 2017](https://www.youtube.com/watch?v=7kchC7OoMHk)
- [URL Routing with Compass](https://github.com/onmyway133/blog/issues/110) :star:
- [Weavy](https://github.com/twittemb/Weavy) Navigation framework for iOS applications based on a weaving pattern
- [RxFlow](https://github.com/RxSwiftCommunity/RxFlow) RxFlow is a navigation framework for iOS applications based on a Reactive Flow Coordinator pattern
- [A Flexible Routing Approach in an iOS App](https://medium.com/rosberryapps/the-flexible-routing-approach-in-an-ios-app-eb4b05aa7f52)
- [Navigation in Swift](https://www.swiftbysundell.com/posts/navigation-in-swift)
- [Coordinators Essential tutorial. Part I](https://medium.com/blacklane-engineering/coordinators-essential-tutorial-part-i-376c836e9ba7)
- [Coordinators Essential tutorial. Part II](https://medium.com/blacklane-engineering/coordinators-essential-tutorial-part-ii-b5ab3eb4a74)
- [Coordinators Redux](http://khanlou.com/2015/10/coordinators-redux/)
- [Coordinators – Soroush Khanlou - CocoaHeads Stockholm](https://www.youtube.com/watch?v=a1g3k3NObkE)
- [Passing dependencies through Coordinator chain](http://aplus.rs/2017/passing-dependencies-through-coordinator-chain/)
- [MVC-C · Injecting Coordinator pattern in UIKit](http://aplus.rs/2017/mvc-c-injecting-coordinator-pattern-in-uikit/)
- [XCoordinator](https://github.com/quickbirdstudios/XCoordinator) Powerful navigation library for iOS based on the coordinator pattern
- [Controlling Hierachies](https://sandofsky.com/blog/controller-hierarchies.html)
- [Coordinator and FlowController](https://github.com/onmyway133/blog/issues/106)
- [Advanced coordinators in iOS](https://www.hackingwithswift.com/articles/175/advanced-coordinator-pattern-tutorial-ios)
- [iOS Coordinators: A Storyboard Approach](https://thoughtbot.com/blog/ios-coordinators-a-storyboard-approach)
- [The Navigator](https://jobandtalent.engineering/the-navigator-420b24fc57da)

### Analytics

- [Building an enum-based analytics system in Swift](https://www.swiftbysundell.com/posts/building-an-enum-based-analytics-system-in-swift)
- [When Not to Use an Enum](http://matt.diephouse.com/2017/12/when-not-to-use-an-enum/)
- [Misusing enums](https://davedelong.com/blog/2017/12/07/misusing-enums/)
- [Logging in Swift](http://merowing.info/2016/07/logging-in-swift/)
- [Swift Analytics](http://chris.eidhof.nl/post/swift-analytics/)
- [Analytics - How to avoid common mistakes in iOS](https://benoitpasquier.com/common-mistakes-analytics-ios-app/)

### SDK

- [line-sdk-ios-swift](https://github.com/line/line-sdk-ios-swift) Provides a modern way of implementing LINE APIs
- [BackchannelSDK-iOS](https://github.com/backchannel/BackchannelSDK-iOS) The official iOS SDK for Backchannel
- [SpotifyLogin](https://github.com/spotify/SpotifyLogin) Swift framework for authenticating with the Spotify API
- [stripe-ios](https://github.com/stripe/stripe-ios) Stripe iOS SDK

### Functional

- [Proof in Functions](https://www.fewbutripe.com/swift/math/2015/01/06/proof-in-functions.html) :rocket:
- [Instance Methods are “Curried” Functions in Swift](https://oleb.net/blog/2014/07/swift-instance-methods-curried-functions/)

### Types

- [Making illegal states unrepresentable](https://oleb.net/blog/2018/03/making-illegal-states-unrepresentable/)
- [Functional Snippet #13: Phantom Types](https://www.objc.io/blog/2014/12/29/functional-snippet-13-phantom-types/)
- [Never](https://nshipster.com/never/)
- [Pure functions in Swift](https://www.swiftbysundell.com/posts/pure-functions-in-swift)
- [Phantom types in Swift](https://www.swiftbysundell.com/posts/phantom-types-in-swift)

### Protocols

- [Mixins over Inheritance](https://alisoftware.github.io/swift/protocol/2015/11/08/mixins-over-inheritance/)
- [Mixins and traits in Swift 2.0](http://machinethink.net/blog/mixins-and-traits-in-swift-2.0/)
- [Protocol Oriented Programming is Not a Silver Bullet](http://chris.eidhof.nl/post/protocol-oriented-programming/)
- [Value-Oriented Programming](https://matt.diephouse.com/2018/08/value-oriented-programming/)
- [Beyond Crusty: Real-World Protocols](https://www.dotconferences.com/2016/01/rob-napier-beyond-crusty-real-world-protocols)
- [A Little Respect for AnySequence](http://robnapier.net/erasure)
- [Protocols Sidebar I: Protocols Are Nonconformists](http://robnapier.net/nonconformist)
- [Protocols II: A Mockery of Protocols](http://robnapier.net/a-mockery-of-protocols)
- [A case of premature abstractions](https://swiftindepth.com/2019-03-24/a-case-of-premature-abstractions)
- [Protocol-Oriented Library Design](https://www.pointfree.co/episodes/ep37-protocol-oriented-library-design-part-1)
- [Protocol Witnesses - Brandon Williams - App Builders 2019](https://www.youtube.com/watch?v=3BVkbWXcFS4)

### Code

- [Splash](https://github.com/JohnSundell/Splash) A fast, lightweight and flexible Swift syntax highlighter for blogs, tools and fun!

### Separation of Concerns

- [The trouble with manager objects](https://sandofsky.com/blog/manager-classes.html)

### Testing

- [Defining testing data in Swift](https://www.swiftbysundell.com/posts/defining-testing-data-in-swift)
- [Time traveling in Swift unit tests](https://www.swiftbysundell.com/articles/time-traveling-in-swift-unit-tests/)
- [The power of UserDefaults in Swift](https://www.swiftbysundell.com/articles/the-power-of-userdefaults-in-swift/)
- [Unit testing asynchronous Swift code](https://www.swiftbysundell.com/articles/unit-testing-asynchronous-swift-code/)

### Generic

- [Generalizing Swift code](https://www.swiftbysundell.com/posts/generalizing-swift-code)
- [Alternatives to protocols in Swift](https://www.swiftbysundell.com/articles/alternatives-to-protocols-in-swift/)

### Cross platform

- [LibSlack: the C++ library at the foundation of our client application architecture](https://slack.engineering/libslack-the-c-library-at-the-foundation-of-our-client-application-architecture-97470b5ef9b3)
- [The (not so) hidden cost of sharing code between iOS and Android](https://blogs.dropbox.com/tech/2019/08/the-not-so-hidden-cost-of-sharing-code-between-ios-and-android/)
- [Client Consistency at Slack: Beyond Libslack](https://slack.engineering/client-consistency-at-slack-beyond-libslack-c9cfbe778fb7)

### Remote Config / Feature Flagging

- [A Smart Feature Flagging System for iOS](https://albertodebortoli.com/2019/11/26/a-smart-feature-flagging-system-for-ios/)

Licence
--
This project is released under the MIT license. See [LICENSE.md.](https://github.com/onmyway133/awesome-ios-architecture/blob/master/LICENSE)
