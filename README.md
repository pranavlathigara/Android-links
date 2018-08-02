# Android-links

Links about android development

## Links
- [Articles](#articles)
 	- [Fragment](#fragment)
 	- [Design patterns](#patterns)
 	- [Views](#views)
 	- [Tests](#tests)
 	- [Other](#other)
  - [Architecture](#architecture)
  - [Rx](#rx)
  - [Kotlin](#kotlin)
- [Videos](#videos)
- [Libraries](#libraries)
  - [DI](#di)
  - [Image Loader](#il)

# Articles
## Fragment
[Advocating Against Android Fragments](https://corner.squareup.com/2014/10/advocating-against-android-fragments.html)

[Fragment Transactions & Activity State Loss](http://www.androiddesignpatterns.com/2013/08/fragment-transaction-commit-state-loss.html)

[The Dark side of Fragments](https://android.jlelse.eu/the-dark-side-of-fragments-ca0f871b1199)

[Android Fragment Lifecycle for Professional Developers](https://www.techyourchance.com/android-fragment-lifecycle-for-professional-developers/)

## Patterns
[The Evolution Of The Repository Pattern - Be Aware Of Over Abstraction](http://hannesdorfmann.com/android/evolution-of-the-repository-pattern)

[Common Design Patterns for Android](https://www.raywenderlich.com/109843/common-design-patterns-for-android)

[Designing something solid](https://www.novoda.com/blog/designing-something-solid/)

[Don’t use DAO, use Repository](https://thinkinginobjects.com/2012/08/26/dont-use-dao-use-repository/)

## Views
[Say goodbye to findViewById. Say hello to Data Binding Library.](https://inthecheesefactory.com/blog/say-goodbye-to-findviewbyid-with-data-binding-library/en)

[Greyscale Views on Android](http://blog.bradcampbell.nz/greyscale-views-on-android/)

[Animating Android Activities and Views with Left and Right Slide Animations](https://kylewbanks.com/blog/left-and-right-slide-animations-on-android-activity-or-view)

[How to filter a RecyclerView with a SearchView](https://www.codementor.io/tips/1237823034/how-to-filter-a-recyclerview-with-a-searchview)

[Implementing a modal selection helper for RecyclerView](https://medium.com/@BladeCoder/implementing-a-modal-selection-helper-for-recyclerview-1e888b4cd5b9)

[RecyclerView animations done right](http://frogermcs.github.io/instamaterial-recyclerview-animations-done-right/)

[Writing Better Adapters](https://proandroiddev.com/writing-better-adapters-1b09758407d2)

[Using Custom Views As Menu Items](http://blog.stablekernel.com/using-custom-views-as-menu-items)

[Your ViewHolders are Dumb. Make ’em Not Dumb](https://jonfhancock.com/your-viewholders-are-dumb-make-em-not-dumb-82e6f73f630c)

[ConstraintLayout - Guidelines, Barriers, Chains and Groups](https://riggaroo.co.za/constraintlayout-guidelines-barriers-chains-groups/)

[ItemDecoration in Android](https://medium.com/proandroiddev/itemdecoration-in-android-e18a0692d848)

[Playing with elevation in Android](https://blog.usejournal.com/playing-with-elevation-in-android-91af4f3be596)

[An Android Toolbar and Action Bar Color Guide](https://www.codeandkits.com/Blog/2018/03/26/an-android-toolbar-and-action-bar-color-guide/)

[Drawing multiline text to Canvas](https://medium.com/over-engineering/drawing-multiline-text-to-canvas-on-android-9b98f0bfa16a)

[Spantastic text styling with Spans](https://medium.com/google-developers/spantastic-text-styling-with-spans-17b0c16b4568)

[RecyclerView — More Animations with Less Code using Support Library ListAdapter](https://medium.com/@trionkidnapper/recyclerview-more-animations-with-less-code-using-support-library-listadapter-62e65126acdb)

[Customizing Switch using XML](https://medium.com/@elye.project/customizing-switch-using-xml-ca0d37204a86)

## Tests
[Fast and reliable UI tests on Android](https://labs.ribot.co.uk/fast-and-reliable-ui-tests-on-android-17c261b8220c#.1bilhu4hg)

[Different ways of testing exceptions in Java and JUnit](https://blog.goyello.com/2015/10/01/different-ways-of-testing-exceptions-in-java-and-junit/)

[Espresso Test for Intent](http://pengj.me/android/test/2015/10/17/expresso-test-intent.html)

[How to be a mock star](https://medium.com/fueled-android/how-to-be-a-mock-star-fc00714d8c2f)

[Android testing: Unit testing (Part 1)](http://alexzh.com/tutorials/android-testing-unit-testing/)

[Android testing: Mockito and Robolectric (Part 2)](http://alexzh.com/tutorials/android-testing-mockito-robolectric/)

[Android testing: Espresso (Part 3)](http://alexzh.com/tutorials/android-testing-espresso-part-3/)

[Android testing: UI Automator (Part 4)](http://alexzh.com/tutorials/android-testing-ui-automator-part-4/)

[Dont Use Espresso Idling Resources like Google does](https://www.philosophicalhacker.com/post/psa-dont-use-esprsso-idling-resources-like-this/)

[How "Android Test Recorder" generate delays between actions](http://droidtestlab.com/delay.html)

[Should we use mocking libraries for go testing?](https://www.philosophicalhacker.com/2016/01/13/should-we-use-mocking-libraries-for-go-testing/)

[Simple way to test asynchronous actions in Android](https://medium.com/@v.danylo/simple-way-to-test-asynchronous-actions-in-android-service-asynctask-thread-rxjava-etc-d43b0402e005)

[Dagger 2 Testing](http://endlesswhileloop.com/blog/2016/06/23/dagger-2-testing/)

[Why I Don't use Robolectric](https://www.philosophicalhacker.com/post/why-i-dont-use-roboletric/)

[Junit testing and Android dependencies](https://android.jlelse.eu/junit-testing-and-android-dependencies-e65e66afce61)

[Clean tests: Naming](https://android.jlelse.eu/clean-tests-part-1-naming-cce94edf0522)

[Clean tests: Comments](https://android.jlelse.eu/clean-tests-part-2-comments-4016ee82f186)

[Unit testing protected lifecycle methods](https://medium.com/google-developer-experts/unit-testing-activity-lifecycle-4e740f71e68a)

[Unit Testable RecyclerViews](https://www.philosophicalhacker.com/post/unit-testable-recycler-views/)

[The 3 tiers of the Android test pyramid](https://medium.com/android-testing-daily/the-3-tiers-of-the-android-test-pyramid-c1211b359acd)

[Testing state vs. testing interaction](https://medium.com/android-testing-daily/testing-state-vs-testing-interaction-c5d7fe0bf247)

[Test doubles](https://medium.com/android-testing-daily/test-doubles-9a63dfaeb28b)

[Testing Views in Isolation at RoMOBOS](https://proandroiddev.com/testing-views-in-isolation-at-romobos-d288e76fe10e)

## Other
[Things You Should Never Do, Part I](http://www.joelonsoftware.com/articles/fog0000000069.html)

[Streamlining eero’s Android build process](https://medium.com/@jordanjoz/streamlining-eeros-android-build-process-6a870ef40a89#.svunhmwgi)

[10 Tips to Improve Your Gradle Build Time](http://www.universalmind.com/blog/10-tips-to-improve-your-gradle-build-time/)

[Great Adpater Hell Escape](http://hannesdorfmann.com/android/adapter-delegates)

[How to style AlertDialogs like a pro](http://blog.supenta.com/2014/07/02/how-to-style-alertdialogs-like-a-pro/)

[Rich text battle: TextView vs WebView](http://www.hidroh.com/2016/02/27/richtext-textview-versus-webview/)

[Introduction to SpringAnimation with examples](https://www.thedroidsonroids.com/blog/android/springanimation-examples/)

[A strategy to secure your API keys using Gradle](https://medium.com/@cassioso/a-strategy-to-secure-your-api-keys-using-gradle-b9c107272860)

[40 Hours is enough](https://hackernoon.com/40-hours-is-enough-86d7166911ea)

[Programmer 60-80 hour weeks](http://brianknapp.me/programmer-60-80-hour-weeks/)

[The Trouble with Checked Exceptions(part 1)](http://www.mindview.net/Etc/Discussions/CheckedExceptions)

[The Trouble with Checked Exceptions(part 2)](http://www.artima.com/intv/handcuffs.html)

[The Trouble with Checked Exceptions(part 3)](http://radio-weblogs.com/0122027/stories/2003/04/01/JavasCheckedExceptionsWereAMistake.html)

[Identifying an Android Device](http://handstandsam.com/2017/05/04/identifying-an-android-device/)

[Glide vs Picasso](https://medium.com/@multidots/glide-vs-picasso-930eed42b81d)

[Android Themes & styles, a real architecture](http://blog.octo.com/en/android-themes-styles-a-real-architecture/)

[Android Styles & Themes for developers](http://blog.octo.com/en/android-styles-themes-for-developers/)

[Understanding how references work in android and java](https://medium.com/google-developer-experts/finally-understanding-how-references-work-in-android-and-java-26a0d9c92f83)

[An introduction to Android Instant Apps](https://willowtreeapps.com/ideas/an-introduction-to-android-instant-apps)

[Live Template for RecyclerView Adapter in Android Studio](https://tech.fleka.me/live-template-for-recyclerview-adapter-in-android-studio-5a4e7342bffc)

[Android Task and Back Stack Review](https://blog.mindorks.com/android-task-and-back-stack-review-5017f2c18196)

[How to speed up your slow Gradle builds](https://android.jlelse.eu/how-to-speed-up-your-slow-gradle-builds-5d9a9545f91a)

[Android Resources Refactoring](https://news.realm.io/news/android-resources-refactoring/)

[On properly using volatile and synchronized](https://medium.com/google-developer-experts/on-properly-using-volatile-and-synchronized-702fc05faac2)

[Scrum and Kanban – Are They That Different After All?](https://perfectial.com/blog/scrum-and-kanban-are-they-that-different-after-all/)

[Keep Your Features in Progress Out of Your Release Builds](http://antoine-merle.com/blog/2015/10/10/keep-your-features-in-progress-out-of-your-release-builds/)

[What's the Difference? Agile vs Scrum vs Waterfall vs Kanban](https://www.smartsheet.com/agile-vs-scrum-vs-waterfall-vs-kanban)

[Context, What Context?](https://possiblemobile.com/2013/06/context/)

[Which Context should I use in Android?](https://medium.com/@ali.muzaffar/which-context-should-i-use-in-android-e3133d00772c)

[65K methods](https://medium.com/@rotxed/dex-skys-the-limit-no-65k-methods-is-28e6cb40cf71)

[I am the reason for Hungarian notation in Android](http://beust.com/weblog/2017/07/17/i-am-the-reason-for-hungarian-notation-in-android/)

[Going multiprocess on Android](https://medium.com/@rotxed/going-multiprocess-on-android-52975ed8863c)

[Tasting Dagger 2 on Android](https://fernandocejas.com/2015/04/11/tasting-dagger-2-on-android/)

[Dependency injection with Dagger 2 - Custom scopes](http://frogermcs.github.io/dependency-injection-with-dagger-2-custom-scopes/)

[Why Having Global Static References to Application Contexts is Probably not the Best Idea](https://www.philosophicalhacker.com/2015/07/14/why-static-references-to-application-contexts-are-probably-not-the-best-idea/)

[How to make complex requests simple with RxJava in Kotlin](https://blog.mindorks.com/how-to-make-complex-requests-simple-with-rxjava-in-kotlin-ccec004c5d10)

[Exploring the Android EmojiCompat Library](https://medium.com/exploring-android/exploring-the-android-emoji-compatibility-library-1b9f3bb724aa)

[Espresso Test Addiction: An Anti-pattern](https://www.philosophicalhacker.com/post/espresso-test-addiction/)

[Code Reviews Q&A](https://blog.babylonhealth.com/code-reviews-q-a-f33c72d3b2c3)

[Perfect code is an illusion](https://8thlight.com/blog/daniel-irvine/2016/11/11/perfect-code-is-an-illusion.html)

[The egoless programmer](https://8thlight.com/blog/daniel-irvine/2016/09/30/the-egoless-programmer.html)

[The problematic pull request](https://8thlight.com/blog/daniel-irvine/2016/11/18/the-problematic-pull-request.html)

[Default methods + lambdas = less code](https://android.jlelse.eu/default-methods-lambdas-less-code-aa0e63d6c5d9)

[Myths about Unit Tests](https://8thlight.com/blog/fabien-townsend/2017/09/19/myths-about-unit-tests.html)

[From Fragments to Activity: the Lambda Way](https://medium.com/groupon-eng/from-fragments-to-activity-the-lambda-way-32c768c72aa9)

[Mixing JUnit, Hamcrest and Mockito: Explaining java.lang.NoSuchMethodError](https://tedvinke.wordpress.com/2013/12/17/mixing-junit-hamcrest-and-mockito-explaining-nosuchmethoderror/)

[Optimizing the Performance of Vector Drawables](https://medium.com/upday-devs/optimizing-the-performance-of-vector-drawables-680a4c456286)

[“Eat, sleep, code, repeat” is such bullshit](https://m.signalvnoise.com/eat-sleep-code-repeat-is-such-bullshit-c2a4d9beaaf5)

[Advanced Retrofit](https://academy.realm.io/posts/advanced-retrofit-mobilization-2017/)

[A Curious Case of Multiple Locales](https://blog.egorand.me/a-curious-case-of-multiple-locales/)

[What you need to know about Android app memory leaks](https://techbeacon.com/what-you-need-know-about-android-app-memory-leaks)

[No Cause for Concern — RxJava and Retrofit Throwing a Tantrum](https://medium.com/square-corner-blog/no-cause-for-concern-rxjava-and-retrofit-throwing-a-tantrum-96c9e4ba8a6c)

[How to handle background services in Android O](https://medium.com/@kevalpatel2106/how-to-handle-background-services-in-android-o-f96783e65268)

[Android leak pattern: subscriptions in views](https://medium.com/square-corner-blog/android-leak-pattern-subscriptions-in-views-18f0860aa74c)

[Practical ProGuard rules examples](https://medium.com/google-developers/practical-proguard-rules-examples-5640a3907dc9)

[Task Stack](https://blog.stylingandroid.com/task-stack/)

[Android WebView — Downloading Images](https://medium.com/@trionkidnapper/android-webview-downloading-images-f0ec21ac75d2)

[Renaming Your Gradle Build Files](http://www.developerphil.com/renaming-your-gradle-build-files/)

[Exploring Android P: Fingerprint Dialog](https://medium.com/exploring-android/exploring-android-p-fingerprint-dialog-fa672ae62c6f)

[Is group chat making you sweat?](https://m.signalvnoise.com/is-group-chat-making-you-sweat-744659addf7d)

[Keep a readable Git history](https://fangpenlin.com/posts/2013/09/30/keep-a-readable-git-history/)

[Four Steps To Maintaining a Clean Git History](https://spin.atomicobject.com/2017/04/23/maintain-clean-git-history/)

[The Churn](http://blog.cleancoder.com/uncle-bob/2016/07/27/TheChurn.html)

[Objects vs. Data Structures](https://hackernoon.com/objects-vs-data-structures-e380b962c1d2)

[Rebuild or Report?](https://blog.photoeditorsdk.com/rebuild-or-report-211d6ac6e787)

[Android Context Needs Isolation](https://www.techyourchance.com/android-context-needs-isolation()

[Styling Colors & Drawables, Theme Attributes](https://www.androiddesignpatterns.com/2016/08/contextcompat-getcolor-getdrawable.html)

[Use the Android apk analyzer to reduce your apk size](https://riggaroo.co.za/use-android-apk-analyzer-reduce-apk-size/)

[-nodpi, -anydpi, and WTF?](https://commonsware.com/blog/2015/12/21/nodpi-anydpi-wtf.html)

[Mastering Android context](https://medium.freecodecamp.org/mastering-android-context-7055c8478a22)

[Services. The life with/without. And WorkManager](https://medium.com/google-developer-experts/services-the-life-with-without-and-worker-6933111d62a6)

[Polishing UI: Android StateListAnimator](https://android.jlelse.eu/polishing-ui-android-statelistanimator-7b74a06b85a5)

[Composite Views in Android: Composition over Inheritance](https://medium.com/@manuelvicnt/composite-views-in-android-composition-over-inheritance-4a7114609560)

[In-app navigation wih coordinators](http://hannesdorfmann.com/android/coordinators-android)

[Android Studio and Git Branches – How to Simplify Your Work](https://www.thedroidsonroids.com/blog/android-studio-and-git-branches-how-to-simplify-you-work)

## Architecture
[Interfaces for presenters in mvp are a waste of time](http://blog.karumi.com/interfaces-for-presenters-in-mvp-are-a-waste-of-time/)

[Weighing in on the Holy Architecture War](https://medium.com/@yonatanvlevin/weighing-in-on-the-holy-architecture-war-my-take-on-architecture-components-31f7025e9c66)

[Android Architecture(MVC, MVP, MVVM)](https://android.jlelse.eu/android-architecture-2f12e1c7d4db)

[Architectures of Android applications](https://medium.com/@bvmaks/architectures-of-android-applications-244a083bf132)

[Cargo Cult MVVM => The death knell of WPF](http://cargocultsoftwaredevelopment.blogspot.com/2010/10/cargo-cult-mvvm-death-knell-of-wpf.html)

[Android Architecture Components](https://proandroiddev.com/android-architecture-components-cb1ea88d3835)

[Introduction to Android Architecture Components](https://code.tutsplus.com/tutorials/introduction-to-android-architecture--cms-28749?_ga=2.12071028.1998131091.1501205919-2091102857.1500428525)

[Android Architecture Patterns Part 1: Model-View-Controller](https://medium.com/upday-devs/android-architecture-patterns-part-1-model-view-controller-3baecef5f2b6)

[Android MVP: Keeping Presenters Alive](https://medium.com/@trionkidnapper/android-mvp-keeping-presenters-alive-a91b9e080761)

[Presenters don't need lifecycle events](http://hannesdorfmann.com/android/presenters-dont-need-lifecycle)

[Architecture Components - I'm not a purist but](http://hannesdorfmann.com/android/arch-components-purist)

[Presenters are not for persisting](https://hackernoon.com/presenters-are-not-for-persisting-f537a2cc7962)

[Where to Unbind the Presenter](https://proandroiddev.com/where-to-unbind-the-presenter-e50ce343d4ce)

[MVP to MVVM transformation](https://proandroiddev.com/mvp-to-mvvm-transformation-611959d5e0ca)

[Background and Foreground events with Android Architecture Components](https://medium.com/@arturogdg/background-and-foreground-events-with-android-architecture-components-233fdd9fa855)

[ViewModels: Persistence, onSaveInstanceState(), Restoring UI State and Loaders](https://medium.com/google-developers/viewmodels-persistence-onsaveinstancestate-restoring-ui-state-and-loaders-fc7cc4a6c090)

## Rx
[RxJava cheat sheet, with a pinch of Android](https://zeroturnaround.com/rebellabs/rxjava-cheat-sheet-with-a-pinch-of-android/)

[Unit Testing with RxJava](http://alexismas.com/blog/2015/05/20/unit-testing-rxjava/)

[Rx java backpressure](https://stackoverflow.com/documentation/rx-java/2341/backpressure/10629/creating-backpressured-data-sources#t=201607290718331225652)

[Error handling in RxJava](http://blog.danlew.net/2015/12/08/error-handling-in-rxjava/)

[Retrofit 2 and Rx Java call adapter error handling](http://bytes.babbel.com/en/articles/2016-03-16-retrofit2-rxjava-error-handling.html)

[Combination of RxJava and DiffUtil](https://hellsoft.se/a-nice-combination-of-rxjava-and-diffutil-fe3807186012)

[Server polling and retrying failed operations, with Retrofit and RxJava](https://medium.com/@v.danylo/server-polling-and-retrying-failed-operations-with-retrofit-and-rxjava-8bcc7e641a5a)

[Overriding RxAndroid Schedulers in RxJava 2](https://medium.com/@peter.tackage/overriding-rxandroid-schedulers-in-rxjava-2-5561b3d14212)

[MVVM + RxJava: Common Mistakes](http://upday.github.io/blog/mvvm_rx_common_mistakes/)

[RxJava2: Dispose an Observable chain](https://android.jlelse.eu/rxjava2-dispose-an-observable-chain-684e6ca2790)

[The RxJava2 Default Error Handler](https://medium.com/@bherbst/the-rxjava2-default-error-handler-e50e0cab6f9f)

[Concurrency in RxJava 2](https://code.tutsplus.com/tutorials/concurrency-in-rxjava-2--cms-29288)

[RxJava - Schedulers - What, when and how to use it?](https://android.jlelse.eu/rxjava-schedulers-what-when-and-how-to-use-it-6cfc27293add)

[Learning Observable By Building Observable](https://medium.com/@benlesh/learning-observable-by-building-observable-d5da57405d87)

[Rx if the operators could speak](https://medium.freecodecamp.org/rx-if-the-operators-could-speak-58567c4618f1)

[Writing Custom Rx Operators Easily with Kotlin](https://upcurve.engineering/custom-rx-operators-kotlin/)

[RxJava as event bus, the right way](https://lorentzos.com/rxjava-as-event-bus-the-right-way-10a36bdd49ba)

[RxJava2 and Retrofit2 Error Handling on a single place](https://medium.com/mindorks/rxjava2-and-retrofit2-error-handling-on-a-single-place-8daf720d42d6)

[RxJava & State: The Basics](https://tech.instacart.com/rxjava-state-the-basics-f842eaee7ee1)

[Building an AutoCompleting EditText using RxJava](https://proandroiddev.com/building-an-autocompleting-edittext-using-rxjava-f69c5c3f5a40)

[Error handling in RxJava/RxKotlin](https://android.jlelse.eu/error-handling-in-rxjava-rxkotlin-e960300990e0)

[RxJava Backpressure and why should you care?](https://proandroiddev.com/rxjava-backpressure-and-why-you-should-care-369c5242c9e6)

[LCE: Modeling Data Loading in RxJava](https://tech.instacart.com/lce-modeling-data-loading-in-rxjava-b798ac98d80)

## Kotlin
[How kotlin became our primary language for android](https://medium.com/uptech-team/how-kotlin-became-our-primary-language-for-android-3af7fd6a994c#.hj4k8m25l)

[Starting Activities with Kotlin](https://medium.com/@passsy/starting-activities-with-kotlin-my-journey-8b7307f1e460)

[How to Abuse Kotlin Extension Functions](https://www.philosophicalhacker.com/post/how-to-abuse-kotlin-extension-functions/)

[How to remove all !! from your Kotlin code](https://android.jlelse.eu/how-to-remove-all-from-your-kotlin-code-87dc2c9767fb)

[Creating multiple constructors for Data classes in Kotlin](https://medium.com/proandroiddev/creating-multiple-constructors-for-data-classes-in-kotlin-32ad27e58cac)

[Gang of Four Patterns in Kotlin](https://dev.to/lovis/gang-of-four-patterns-in-kotlin)

[Anko for developer](https://www.kotlindevelopment.com/why-should-use-anko/)

[Kotlin tips: Singleton, Utility Functions, group Object Initialization](https://medium.com/default-to-open/kotlin-tips-singleton-utility-functions-group-object-initialization-and-more-27cdd6f63a41)

[Inlining Kotlin Properties](https://blog.egorand.me/inlining-kotlin-properties/amp/)

[Kotlin Type Hierarchy](http://natpryce.com/articles/000818.html)

[Nothing (else) matters in Kotlin](https://proandroiddev.com/nothing-else-matters-in-kotlin-994a9ef106fc)

[Where Should I Keep My Constants in Kotlin?](https://blog.egorand.me/where-do-i-put-my-constants-in-kotlin/)

[Function references in Kotlin](https://antonioleiva.com/function-references-kotlin/)

[Learning Kotlin by Mistake](https://engineering.udacity.com/learning-kotlin-by-mistake-b99304b7d724)

[Representing View State with Kotlin Data Classes](https://medium.com/@trionkidnapper/viewmodel-and-kotlin-data-class-7d3a3b854805)

[Listeners with several functions in Kotlin](https://antonioleiva.com/listeners-several-functions-kotlin/)

[Kotlin’s ‘Nothing’ Type](https://proandroiddev.com/kotlins-nothing-type-946de7d464fb)

[Simplified code with kotlin](https://android.jlelse.eu/simplified-code-with-kotlin-cda9915c9fb9)

[Kotlin is Dope And So Are Its Custom Property Delegates](https://robots.thoughtbot.com/kotlin-is-dope-and-so-are-its-custom-property-delegates)

[Preconditions.kt: Validate Your Kotlin](https://blog.egorand.me/preconditions-kt-validate-your-kotlin/)

[Getting rid of boilerplate with Kotlin Android Extensions](https://www.kotlindevelopment.com/kotlin_android_extensions_eliminate_findviewbyid/)

[How “Effective Java” may have influenced the design of Kotlin](http://www.lukle.at/blog/2017/08/how-effective-java-may-have-influenced-the-design-of-kotlin%E2%80%8A-%E2%80%8Apart-3/)

[Safe, concise text parsing with regex destructuring in Kotlin](https://medium.com/@garnop/safe-concise-text-parsing-with-regex-destructuring-in-kotlin-b8f77ef1e30c)

[A life without ifs](https://medium.com/a-problem-like-maria/a-life-without-ifs-e44967e5c77b)

[Modeling ViewModel States Using Kotlin’s Sealed Classes](https://engineering.udacity.com/modeling-viewmodel-states-using-kotlins-sealed-classes-a5d415ed87a7)

[Simple asynchronous loading with Kotlin Coroutines](https://hellsoft.se/simple-asynchronous-loading-with-kotlin-coroutines-f26408f97f46)

[Safely accessing lateinit properties in Kotlin](https://upcurve.engineering/accessing-lateinit-kotlin/)

[Data Classes are The Best Kotlin Feature](https://www.techyourchance.com/data-classes-best-kotlin-feature/)

[Diving deep into Kotlin Coroutines](https://www.kotlindevelopment.com/deep-dive-coroutines/)

[The Ins and Outs of Generic Variance in Kotlin](https://typealias.com/guides/ins-and-outs-of-generic-variance/)

[An Illustrated Guide to Covariance and Contravariance in Kotlin](https://typealias.com/guides/illustrated-guide-covariance-contravariance/)

[Comping with kotlin's scope functions](https://kotlinexpertise.com/coping-with-kotlins-scope-functions/)

[Simplify your Android code by delegating to sealed classes](https://medium.com/halcyon-mobile/simplify-your-android-code-by-delegating-to-sealed-classes-99304c509321)

[Kotlin + Dagger 2 Gotchas](https://medium.com/@vlazzle/kotlin-dagger-2-gotchas-ebb6bb2ac506)

[Custom attributes using BindingAdapters in Kotlin](https://proandroiddev.com/custom-attributes-using-bindingadapters-in-kotlin-971ef8fcc259)

# Videos
[Life Without Fragments](https://www.youtube.com/watch?v=jl1HRiCaAP4)

[Android Software Architecture by Example](https://www.youtube.com/watch?v=7t7MN8e1W7s)

[DAGGER 2 - A New Type of dependency injection](https://www.youtube.com/watch?v=oK_XtfXPkqw)

[The Future of Dependency Injection with Dagger 2](https://www.youtube.com/watch?v=plK0zyRLIP8)

[Half Way to clean architecture](https://www.youtube.com/watch?v=R89ufpJI3SY)

[View only Android apps at scale](https://www.youtube.com/watch?v=kAAnIN-IqWw&list=PLnVy79PaFHMXpPlgs1uUny8eb-PEfEQNn)

[Understanding and Experimenting with MultiDex](https://www.youtube.com/watch?v=skmOBriQ28E)

[Application Architecture: Designing Offline Application Case Studies](https://www.youtube.com/watch?v=n8nG5K_3BJM)

[Timing is Everything: How to use Timer, Handler, and AlarmManager](https://www.youtube.com/watch?v=CzNFjCQhCV0)

[Linty Fresh](https://www.youtube.com/watch?v=YseGWp7iouM)

[AutoValue Extensions](https://www.youtube.com/watch?v=FfBBTHkRC-o)

[Mastering RecyclerView Layouts](https://www.youtube.com/watch?v=gs_C1E8HwvE)

[Jack and Jill Build System](https://www.youtube.com/watch?v=IwklNEYYs2I)

[Requesting Permissions at Run Time](https://www.youtube.com/watch?v=WGz-alwVh8A)

[How the Main Thread works](https://www.youtube.com/watch?v=eAtMon8ndfk)

[Gradle: From User to Addict](https://www.youtube.com/watch?v=-C7TtnPJ7ms)

[Using Styles and Themes Without Going Crazy](https://www.youtube.com/watch?v=Jr8hJdVGHAk)

[Bulletproof Android](https://www.youtube.com/watch?v=1yF5sqGJo90)

[Exploring Custom Activity Transitions](https://www.youtube.com/watch?v=HLhA0I00TnI)

[Tools of the Trade](https://www.youtube.com/watch?v=AeoeD7K8vKI)

[Introduction to Functional Reactive Programming](https://www.youtube.com/watch?v=_XKX6UQfNGY)

[Exploring the Activity Lifecycle](https://realm.io/news/activities-in-the-wild-exploring-the-activity-lifecycle-android/)

[Loving Lean Layouts](https://www.youtube.com/watch?v=-xAdDqwaWJk)

[Advancing Android Development with Kotlin](https://realm.io/news/oredev-jake-wharton-kotlin-advancing-android-dev/)

[Kotlin in Production](https://www.youtube.com/watch?v=mDpnc45WwlI)

[Exploring RxJava 2 for Android](https://www.youtube.com/watch?v=htIXKI5gOQU)

[Common RxJava Mistakes](https://www.youtube.com/watch?v=QdmkXL7XikQ)

[Advanced RxJava and Conductor](https://www.youtube.com/watch?v=0XSf7sX2rCQ)

[Speeding Up Your Android Gradle Builds](https://www.youtube.com/watch?v=7ll-rkLCtyk)

[Clean App Design with Architecture Components](https://academy.realm.io/posts/360-andev-2017-chuck-greb-clean-app-design-architecture-components/)

# Libraries
## DI
[Roboguice](https://github.com/roboguice/roboguice)

[Dagger 2](https://github.com/google/dagger)

[Toothpick](https://github.com/stephanenicolas/toothpick)

## Image Loader
[Glide](https://github.com/bumptech/glide)

[Picasso](https://github.com/square/picasso)

[Universal ImageLoader](https://github.com/nostra13/Android-Universal-Image-Loader)
