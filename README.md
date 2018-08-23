# 𝙛𝙖𝙣𝙩𝙖𝙨𝙩𝙞𝙘 𝙞𝙤𝙨 𝙖𝙧𝙘𝙝𝙞𝙩𝙚𝙘𝙩𝙪𝙧𝙚
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
- [Clean Architecture](#clean-architecture)
- [Unidirectional Data Flow](#unidirectional-data-flow)
- [VIPER](#viper)
- [VIP](#vip)
- [Data Source](#data-source)
- [Misc](#misc)


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

### Repos

- [TheReactiveArchitecture](https://github.com/devxoul/TheReactiveArchitecture) The modern and reactive architecture for RxSwift application
- [kickstarter vm structure](https://github.com/kickstarter/native-docs/blob/master/vm-structure.md) Rx input and output
- [Coordinator-MVVM-Rx-Example](https://github.com/uptechteam/Coordinator-MVVM-Rx-Example) Example of MVVM-C architecture implemented with RxSwift

# Clean Architecture

### Posts

- [Clean Swift iOS Architecture for Fixing Massive View Controller](http://clean-swift.com/clean-swift-ios-architecture/)

### Repos

- [CleanStore](https://github.com/Clean-Swift/CleanStore) A sample iOS app built using the Clean Swift architecture
- [CleanArchitectureRxSwift](https://github.com/sergdort/CleanArchitectureRxSwift) Example of Clean Architecture of iOS app using RxSwift :rocket:
- [Reminders](https://github.com/tiagomartinho/Reminders) An iOS application written in Swift to demonstrate how to implement a Clean Architecture in iOS

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

# VIPER
View Interactor Presenter Entity Router

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

### Repos

- [iOS-Viper-Architecture](https://github.com/MindorksOpenSource/iOS-Viper-Architecture) A detailed sample app that implements VIPER architecture
- [iOS Viper XCode Templates](https://github.com/infinum/iOS-VIPER-Xcode-Templates) Another detailed sample app that implements VIPER architecture with code generation templates
- [iOSSwiftStarter](https://github.com/RoRoche/iOSSwiftStarter) A sample iOS app written in Swift using the VIPER architecture. 

# VIP
View Interactor Presenter

### Posts

- [Architecture Wars – A New Hope](https://swifting.io/blog/2016/09/07/architecture-wars-a-new-hope/)
- [Introducing Clean Swift Architecture (VIP)](https://hackernoon.com/introducing-clean-swift-architecture-vip-770a639ad7bf)

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
 
# Misc

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
- [Everyone is an API designer](https://vimeo.com/234961067) :rocket:
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

### API

- [API Design](http://mattgemmell.com/api-design/)
- [Testable interface design with enums](https://kandelvijaya.com/2018/03/03/testableinterfacedesignwithenums/)

### Refactoring

- [Similar Prefixes](http://khanlou.com/2018/08/similar-prefixes/)
- [Structuring Swift code](https://www.swiftbysundell.com/posts/structuring-swift-code)

### Coordinator

- [Coordinators Essential tutorial. Part I](https://medium.com/blacklane-engineering/coordinators-essential-tutorial-part-i-376c836e9ba7)
- [Coordinators Essential tutorial. Part II](https://medium.com/blacklane-engineering/coordinators-essential-tutorial-part-ii-b5ab3eb4a74)
- [Coordinators Redux](http://khanlou.com/2015/10/coordinators-redux/)
- [Coordinators – Soroush Khanlou - CocoaHeads Stockholm](https://www.youtube.com/watch?v=a1g3k3NObkE)
- [Passing dependencies through Coordinator chain](http://aplus.rs/2017/passing-dependencies-through-coordinator-chain/)
- [MVC-C · Injecting Coordinator pattern in UIKit](http://aplus.rs/2017/mvc-c-injecting-coordinator-pattern-in-uikit/)

### FlowController

- [Coordinator and FlowController](https://github.com/onmyway133/blog/issues/106)

### View and Model

- [View Descriptors](https://152percent.com/blog/2018/4/16/view-descriptors)
- [Preventing views from being model aware in Swift](https://www.swiftbysundell.com/posts/preventing-views-from-being-model-aware-in-swift)
- [UITableViewCell and Model](https://github.com/onmyway133/blog/issues/154)

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

### Asynchronous Programming

- [Comparative Asynchronous Programming](https://ashfurrow.com/blog/comparative-asynchronous-programming/)
- [Thinking in RxSwift](http://adamborek.com/thinking-rxswift/)
- [Reducers](http://chris.eidhof.nl/post/reducers/)
- [RxSwift](https://github.com/ReactiveX/RxSwift) Reactive Programming in Swift
- [Operations](https://github.com/danthorpe/Operations) A Swift framework inspired by WWDC 2015 Advanced NSOperations session.
- [Modern RxSwift Architectures](https://academy.realm.io/posts/try-swift-nyc-2017-krunoslav-zaher-modern-rxswift-architectures/)

### Navigation

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

### Analytics

- [Building an enum-based analytics system in Swift](https://www.swiftbysundell.com/posts/building-an-enum-based-analytics-system-in-swift)
- [When Not to Use an Enum](http://matt.diephouse.com/2017/12/when-not-to-use-an-enum/)
- [Misusing enums](https://davedelong.com/blog/2017/12/07/misusing-enums/)
- [Logging in Swift](http://merowing.info/2016/07/logging-in-swift/)
- [Swift Analytics](http://chris.eidhof.nl/post/swift-analytics/)

Licence
--
This project is released under the MIT license. See LICENSE.md.
