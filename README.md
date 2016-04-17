# Набор моих пусть частично полезных ссылок по разработке и не только, уровень...разный

## Android 

### Data binding
TODO:
* Official Guide https://developer.android.com/tools/data-binding/guide.html
* https://blog.stylingandroid.com/data-binding-part-1/
* https://blog.stylingandroid.com/data-binding-part-2/
* https://blog.stylingandroid.com/data-binding-part-3/
* https://blog.stylingandroid.com/data-binding-part-4/

#### Data-binding & RecyclerView/ListView h
* https://github.com/evant/binding-collection-adapter 
* https://github.com/radzio/android-data-binding-recyclerview
* Android Data Binding in RecyclerView http://habrahabr.ru/company/dataart/blog/267735/
* Data binding example with SearchView/RecyclerView https://github.com/ashdavies/data-binding

### (Custom) Annotation processors
* Annotation Processor to create arguments for android fragments without using reflections http://hannesdorfmann.com/android/fragmentargs/
* Annotation Processor to create arguments for android fragments without using reflections github https://github.com/sockeqwe/fragmentargs/
* Parseleable Please http://hannesdorfmann.com/android/ParcelablePlease/
* Annotated Adapter http://hannesdorfmann.com/android/AnnotatedAdapter/ for ListViews/GridViews,etc
 

### Libraries and Apps by Jack Wharton,etc
* Hugo - method call logger https://github.com/JakeWharton/hugo
* Timber - autotagging logs https://github.com/JakeWharton/timber
* SDK Manager plugin - autodownload SDK components https://github.com/JakeWharton/sdk-manager-plugin
* Telecine - screen recording for Android https://github.com/JakeWharton/Telecine + https://play.google.com/store/apps/details?id=com.jakewharton.telecine
* Scalpel - A surgical debugging tool to uncover the layers under your app. https://github.com/JakeWharton/scalpel  - mini-Reveal for Android?


#### Butterknife
* Butterknife (GUI injection) https://github.com/JakeWharton/butterknife + https://jakewharton.github.io/butterknife/
* Butterknife vs Android Annotations htps://stackoverflow.com/questions/21279668/butterknife-vs-androidannotations
* How Butterknife actually works http://lgvalle.xyz/2015/05/04/butterknife/
* Knork: простейшая альтернатива ButterKnife в 160 строк кода http://habrahabr.ru/post/230857/

### Other debugging tools
* LeakCanary: Detect all memory leaks! https://corner.squareup.com/2015/05/leak-canary.html  https://github.com/square/leakcanary
* TinyDancer - FPS measurement library https://github.com/brianPlummer/TinyDancer

### Coordinator Layout
* Овладение Coordinator Layout http://habrahabr.ru/post/270121/

### Network

#### Retrofit
* Retrofit)[http://square.github.io/retrofit/
* Consuming APIs with Retrofit https://guides.codepath.com/android/Consuming-APIs-with-Retrofit
* Retrofit — Getting Started and Create an Android Client https://futurestud.io/blog/retrofit-getting-started-and-android-client
* FutureStud's book about Retrofit (they also have one on Picasso) https://futurestud.io/books + https://futurestud.io/blog/retrofit-series-round-up

#### API Emulation
* Fake the backend while you develop the frontend http://jsonstub.com/
* Server Mock from https://apiary.io/

#### API Debugging 
* Runscope https://www.runscope.com/pricing-and-plans


### Analytics systems
* Flurry - no comments
* Count.ly https://count.ly/compare/ Opensource + cloud service, opensource client
* Amplitude https://amplitude.com/pricing Costs...a lot lot. big free plan, revenue verification
* Mixpanel https://mixpanel.com/free/ Timed events, visual events editor, user tracker, A/B test support
* Devtodev http://megamozg.ru/company/devtodev/blog/18664/
* Facebook Mobile Analytics https://vc.ru/p/facebook-mobile-analytics
* AWS Mobile Analytics https://aws.amazon.com/ru/mobileanalytics/faqs/
* UXCam https://uxcam.com/ video recording,heatmaps,etc

#### Google Universal Analytics
* что есть measurment protocol в universal analytics внятное описание http://spark.ru/startup/adstein/blog/8762/otslezhivanie-offlajn-konversij-cherez-google-analytics?from=zp
* нужно для кроссплатформенной интеграции в том числе и с оффлайном, построено на том что ид клиента уникальный
*  http://megamozg.ru/post/8074/ - пример использования в бизнесе (с CRM-системой)
* как еще можно использовать именно с физическим миром http://nicomiceli.com/tracking-your-home-with-google-analytics/ (sleep patterns,amount of time door opens,еще можно то что у меня в в трекере страниц было)
* еще http://www.optimizesmart.com/understanding-universal-analytics-measurement-protocol/
* замечание - а почему бы так не использовать ту же amplitude analytics?api то есть же вроде - https://amplitude.com/docs/api/http - и стиль как у гугла…одна из причин чем лучще гугл - а тем что И мобильный API И MeasurementProtocol И Web. у Ampltude web…ну формально есть https://cloud.mantano.com/book/list?sort=created&order=desc - но вот всякие детали… и то что на тесте - не запустилось...
* оно - бесплатное. в отличии от Amplitude….и имеет лимиты https://developers.google.com/analytics/devguides/collection/other/limits-quotas а 500 hits per session может стать проблемой.

### Интересные (чем то) рекламные системы
* Appodeal - медиатор http://megamozg.ru/post/15272/ aka http://appodeal.ru/
* i402 - ультралокальный геотаргетинг https://habrahabr.ru/post/276119/ + http://doc.402targeting.com/ (правда ультралокальность проявляется и в том что только Москва и СПб)



### Continouos Integration / Devlivery
* http://stablekernel.com/blog/continuous-delivery-android-part-1/
* http://stablekernel.com/blog/continuous-delivery-android-part-2/
* http://stablekernel.com/blog/unit-testing-continuous-delivery-for-android-part-3/

### Testing
* The evolution journey of Android GUI testing Cucumber — Espresso — Page Object Pattern https://medium.com/@neoranga55/the-evolution-journey-of-android-gui-testing-f65005f7ced8
* Roboletric,Espresso,JaCoCo,etc http://habrahabr.ru/company/rambler-co/blog/266837/
* Wait for it...a deep dive into Espresso's Idling Resources http://dev.jimdo.com/2014/05/09/wait-for-it-a-deep-dive-into-espresso-s-idling-resources/
* Заметки по тестированию, в том числе про mockito и Robotium https://www.bignerdranch.com/blog/testing-the-android-way/
* Working with Robolectric and Robotium in Android Studio and Gradle https://benwilcock.wordpress.com/2015/01/20/working-with-robolectric-and-robotium-in-android-studio-and-gradle/ + https://github.com/benwilcock/android-alltest-gradle-sample
* Different ways of testing exceptions in Java and JUnit http://blog.goyello.com/2015/10/01/different-ways-of-testing-exceptions-in-java-and-junit/
* Why run unit tests on CI server https://programmers.stackexchange.com/questions/308515/whats-the-point-of-running-unit-tests-on-a-ci-server


#### mockito
* Описание mockito http://site.mockito.org/mockito/docs/current/org/mockito/Mockito.html
* http://monkeyisland.pl/2008/04/26/asking-and-telling/
* Unit tests with Mockito - Tutorial http://www.vogella.com/tutorials/Mockito/article.html
* https://corner.squareup.com/2012/10/mockito-android.html

#### Roboletric
* Unit Testing with Robolectric https://github.com/codepath/android_guides/wiki/Unit-Testing-with-Robolectric 
* вообще https://github.com/codepath/android_guides полезный репозиторий
* How to test options menu with Robolectric https://stackoverflow.com/questions/21856053/how-to-test-menu-in-android-with-robolectric
* Driving activity lifecycle http://robolectric.org/activity-lifecycle/
* Using qualified resources http://robolectric.org/using-qualifiers/
* Unit Testing Android Activity with Robolectric http://roboguicetutorials.blogspot.com/2014/10/unit-testing-android-activity-with-robolectric.html
* TDD with Robolectric https://colabug.gitbooks.io/intro-to-android/content/tdd_with_robolectric/README.html
* Robolectric + Espresso examples https://github.com/robolectric/deckard (именно гибридный вариант - когда то одно то другое)
* Perform Clicks in Android Robolectric Unit Test http://timnew.me/blog/2014/10/27/perform-clicks-in-android-robolectric-unit-test/

#### Jenkins / Android Emulator issues
* https://devmaze.wordpress.com/2011/12/12/starting-and-stopping-android-emulators/
* http://blog.daanraman.com/coding/automatically-detect-if-the-android-emulator-is-running/
* wait-for-emulator.sh Reading Tracker'а 
* постаратся ЛЮБОЙ ценой использовать x86-64/x86 эмулятор. да, даже в VMWare ESXi. Да, это МОЖНО сделать. Если железо держит Nested Virtualization (у меня к сожалению не держит) https://forum.ivorde.com/kvm-nested-in-vmware-esxi-5-5-enable-guest-hypervisor-vmx-svm-flags-without-vsphere-web-client-t19773.html

#### Genymotion 
* Что с Play Services делать https://stackoverflow.com/questions/20121883/how-to-install-google-play-services-in-a-genymotion-vm-with-no-drag-and-drop-su


#### Travis CI
* com.android.ddmlib.ShellCommandUnresponsiveException  - http://stackoverflow.com/questions/32952413/gradle-commands-fail-on-api-23-google-api-emulator-image-armeabi-v7a bug in Android, one of workarounds https://code.google.com/p/android/issues/detail?id=189764&q=label%3APriority-Medium&colspec=ID%20Type%20Status%20Owner%20Summary%20Stars also put lower android emulator version
* issue with design support library https://github.com/codepath/android_guides/wiki/Setting-up-Travis-CI 
* https://blog.cyplo.net/2015/10/25/android-integration-test-timeouts/
* Google APIs http://stackoverflow.com/questions/28949722/android-tests-fail-on-travis-with-shellcommandunresponsiveexception/28949723#28949723
* Code coverage testing - https://github.com/ParsePlatform/Parse-SDK-Android + https://github.com/codecov/example-android/blob/master/.travis.yml
* see my  https://github.com/intari/MergeAdapterDemo
* Travis CI vs Circle CI https://strongloop.com/strongblog/node-js-travis-circle-codeship-compare/
* Bamboo vs Travis CI vs Circle CI https://www.itcentralstation.com/product_reviews/travis-ci-review-32073-by-ben-dougherty

#### Circle CI
* 1 free builder even for private repositories (4 for OpenSource repositories). Github-only, no Bitbucket (per https://circleci.com/docs/faq )
* Looks like (per https://code.google.com/p/android/issues/detail?id=104305 ) they thought about android timeout issues...
* Continuous Integration on Android: Why we ditched Jenkins for Circle CI https://infinum.co/the-capsized-eight/articles/continuous-integration-on-android-why-we-ditched-jenkins-for-circle-ci
* Sample Circle CI + Espresso project https://discuss.circleci.com/t/a-sample-android-espresso-project/1212 https://github.com/circleci/EspressoSample
* Circle CI Dummy Android app https://github.com/circleci/circle-dummy-android
* What to do if timeout - https://stackoverflow.com/questions/33499046/android-project-automation-test-in-circleci-build-failed-with-an-exception (or read Espresso sample or just use Robolectric)
* Интеграции... http://blog.circleci.com/flowdock-integration/
* Gamification https://getbadges.io/integration/circle



### JIRA Clients
* https://play.google.com/store/apps/details?id=jira.soap&amp;hl=en
* https://play.google.com/store/apps/details?id=com.mobilitystream.android.jiraconnectpro

### Play Store Autosubmission
* Gradle https://github.com/Triple-T/gradle-play-publisher (example from https://circleci.com/docs/android )
* Jenkins https://wiki.jenkins-ci.org/display/JENKINS/Google+Play+Android+Publisher+Plugin

### Android tricks
* Как узнать текущую активити на любой версии Android включая 6.0 https://stackoverflow.com/questions/3873659/android-how-can-i-get-the-current-foreground-activity-from-a-service/27642535#27642535  (недостаток - надо запрашивать Accessibility Service, Reading Tracker теперь таким образом работает потому что ему все равно сервис нужен)
* А если Android 6.0 не волнует а вот Accessibility Service - волнует https://stackoverflow.com/questions/33918528/android-5-0-getrunningtasks-is-deprecated 



### Android bootstrapers
#### Android Bootstrap
* http://www.androidbootstrap.com/
* http://www.slideshare.net/donnfelker/android-bootstrap-14359986
* http://www.slideshare.net/donnfelker/android-bootstrap
* RoboGuice 
* Robotium
* Account Manager
* GSON
* ...

#### Android Kickstartr
* http://androidkickstartr.com/

### rxJava
* лекции от e-Legion по rx и в комментах описания и ссылки на ролики как и зачем вообще придумали rx https://habrahabr.ru/company/e-Legion/blog/272459/
* введение в RxJava aka почему Rx http://habrahabr.ru/post/269417/
* rx. ключевые типы http://habrahabr.ru/post/270023/
* rx. Жизненный цикл подписки http://habrahabr.ru/post/270975/
* rxJava создание последовательности https://habrahabr.ru/post/281633/
* грокаем RxJava часть 1 http://habrahabr.ru/post/265269/ - крутая штука. но retrolambda очень желательно. паттерн наблюдатель на стероидах.
* грокаем RxJava часть 2 http://habrahabr.ru/post/265583/
* грокаем RxJava часть 3 http://habrahabr.ru/post/265727/
* Rx ключевые типы http://habrahabr.ru/post/270023/
* rx борьба с вызовами суровой действительности http://habrahabr.ru/post/267243/
* как код на RxJava тестировать https://fedepaol.github.io/blog/2015/09/13/testing-rxjava-observables-subscriptions/
* блог Advanced Rx http://akarnokd.blogspot.com/


### Android/Various
* Что есть java.lang.Object http://habrahabr.ru/post/265373/
* Kata: Robolectric Integration http://coreylatislaw.com/kata-robolectric-integration/
* TDD vs BDD. В чем разница? http://dou.ua/forums/topic/8897/
* Варианты сжатия текстур на Android https://habrahabr.ru/company/intel/blog/276089/
* Кому жить, а кому умереть: приоритеты процессов в Android https://habrahabr.ru/post/276381/
* Отзывчивое Android-приложение или 1001 способ загрузить картинку https://habrahabr.ru/company/eastbanctech/blog/192998/
* Построение Android приложений шаг за шагом, часть первая https://habrahabr.ru/company/rambler-co/blog/275943/
* Построение Android приложений шаг за шагом, часть вторая https://habrahabr.ru/company/rambler-co/blog/277343/
* Android runtime permissions. Почему, зачем и как (про 6.0) https://habrahabr.ru/post/278945/ 
* VIPER для Android https://habrahabr.ru/company/rambler-co/blog/277003/
* ScribeJava - простая OAUTH - библиотека https://habrahabr.ru/company/hh/blog/278957/ + SunScribe - расширение

## iOS
* Использование NSOperation и NSOperationQueue в Swift http://habrahabr.ru/post/267843/ (перевод туториала Ray Wenderlich)
* AsyncDisplayKit Tutorial: Achieving 60 FPS scrolling http://www.raywenderlich.com/86365/asyncdisplaykit-tutorial-achieving-60-fps-scrolling - про тулкит от Facebook для ускорения процесса
* как за 7 дней превратится из сервер сайд в клиент-сайд разработчика https://habrahabr.ru/company/mailru/blog/277495/ (также смотрим полезные для начинающего iOS-разработчика ссылки)
* простой шаблон синглтона https://gist.github.com/intari/e62ccd4c60eb36eabc82 (через GCD dispatch_once)
* жизненный цикл UIViewController’а https://habrahabr.ru/post/129557/ читать даже тем кто уверен что знает, есть некоторые...тонкости. недостаток - даже Storyboards не учтены
* Преодолеваем скрытые опасности KVO в Objective C https://habrahabr.ru/company/eastbanctech/blog/202884/
* Обзор библиотеки для скачки/кэширования/обработки картинок, Swift http://www.raywenderlich.com/118361/what-is-nuke
* библиотека для удобной работы с Keychain https://github.com/ObjColumnist/MCSMKeychainItem
* библиотека для работы с JSON сразу обьектами (чтобы не руками) https://github.com/hkellaway/Gloss + http://harlankellaway.com/Gloss/
* пример работы с Goodreads API с OAUTH на Swift https://www.goodreads.com/topic/show/18044457-ios-swift-example?comment=148726023#comment_148726023 https://github.com/danielbmarques/GROAuthExample
* генерация иконок http://makeappicon.com/ и там же какие надо размеры для iOS9/Android. поддерживает и iOS и Android
* делалка локализованных скриншотов для iTunes Connect http://shotbot.io/ - обещана
* 27 интересных библиотек для iOS https://medium.com/app-coder-io/27-ios-open-source-libraries-to-skyrocket-your-development-301b67d3124c#.elevhjnzb
* Magical Record - упрощение работы с CoreData https://github.com/magicalpanda/MagicalRecord
* iRate - еще один компонент для запроса рейтинга в сторе https://github.com/nicklockwood/iRate
* Стриминг iOS приложений (и некоторых Андроид), платно https://appetize.io (реально симуляторные сборки используют)
* еще как (в том числе) средство прототипирования - http://www.pixate.com/  - куплено гуглом
* продвинутая расшаривалка https://github.com/ShareKit/ShareKit
* старый способ как сделать instance properties для категорий http://oleb.net/blog/2011/05/faking-ivars-in-objc-categories-with-associative-references/
* как лучще NSError'ы свои описывать https://agilewarrior.wordpress.com/2016/03/24/nice-pattern-for-defining-nserror-constants/
* как правильно и зачем перегружать isEqual http://nshipster.com/equality/
* кастомные клавиатуры https://habrahabr.ru/post/235917/
* как method swizzling делать http://nshipster.com/method-swizzling/
* готовый фильтр Блума под iOS https://github.com/rgerard/ios-bloom-filter 

### In-app purchases
* In-App Purchases Tutorial: Getting Started https://www.raywenderlich.com/105365/in-app-purchases-tutorial-getting-started
* IAP Helper https://github.com/saturngod/IAPHelper для обычных
* MKStoreKit - странный он какой то
* RMStore 

### ReactiveCocoa
* шпаргалка по операторам rxSwift https://habrahabr.ru/post/281292/ 

### GUI
* жизненный цикл UIViewController https://habrahabr.ru/post/129557/  
* еще последовательность старта view и view controller https://stackoverflow.com/questions/5107604/can-somebody-explain-the-process-of-a-uiviewcontroller-birth-which-method-follo
* Xcode Live Rendering https://habrahabr.ru/post/239257/
* показ специальных картинок для пустых UITableView / UICollectionView https://github.com/dzenbot/DZNEmptyDataSet
* простой компонент календаря https://github.com/jivesoftware/PDTSimpleCalendar
* GPUImage - обработка видео и фото https://github.com/BradLarson/GPUImage
* Flat colors for iOS https://github.com/ViccAlexander/Chameleon
* главный кусок чата из Slack for iOS (с текстовым окном крутым и так далее) https://github.com/slackhq/SlackTextViewController
* Data-driven table view https://github.com/romaonthego/RETableViewManager
* PermissionScope - типа универсальный способ показа и проверки доступа https://github.com/nickoneill/PermissionScope
* SVProgressHUD https://github.com/SVProgressHUD/SVProgressHUD анимация загрузки
* FontAwesomeKit https://github.com/PrideChung/FontAwesomeKit
* идеальные плавные uitableview http://habrahabr.ru/post/264817/ - там же и советы по по отпимизации графики вообще  и тому как на симулятор ловить проблемы с этим 
* table view с дополнительными кнопками http://www.raywenderlich.com/62435/make-swipeable-table-view-cell-actions-without-going-nuts-scroll-views (просто удаление то просто сделать)
* как бесконечный скролл UITableView https://stackoverflow.com/questions/10404116/uitableview-infinite-scrolling - там и ручками пример и с SVPullToRefresh http://samvermette.com/314 - заодно это и реализация pullToRefresh нормальная
* как продвинуто со шрифтами работать http://www.raizlabs.com/dev/2015/08/advanced-ios-typography/
* создание пользовательской палитры в XCode https://www.natashatherobot.com/xcode-color-palette/
* как сделать Action Sheet как в Apple Music - смотрим https://stackoverflow.com/questions/31521741/how-did-apple-do-their-action-sheet-like-this   https://stackoverflow.com/questions/31310259/groups-or-separator-in-uialertcontroller-as-in-new-music-app - на https://github.com/JonasGessner/JGActionSheet намекают
* Popover controller кастомный - пример https://github.com/nicolaschengdev/WYPopoverController
* IBInspectable/IBDesignable http://nshipster.com/ibinspectable-ibdesignable/
* CustomViewKit https://github.com/yume190/CustomView
* Custom AlertView https://github.com/Raizlabs/RaisinToast
* расширенный выбор картинки в зависимости от набора/ориентации https://github.com/kevindelord/UIImage-Autoresize



    
#### Чем нарезать GUI
* Sketch (вместо фотошопа) http://habrahabr.ru/post/252063/ - OS X only. а еще см https://vc.ru/p/sketch - на тему чем оно лучще фотошопа
* Droptimizer http://12rockets.com/droptimizer/ нарезка правильного арта по @3x
* Slicy http://www.macrabbit.com/slicy/help/  - автонарезатор из фотошопа (но надо тегировать специальным образом). @3x не поддерживается пока.
* PaintCode (если он нам подходит)
* А еще есть Sketch-style IBAnimatable https://github.com/JakeLin/IBAnimatable/ - дизайн GUI ЦЕЛИКОМ в XCode…хмм

 
 
#### Autolayout
* Autolayout DSL https://github.com/SnapKit/SnapKit
* KeepLayout https://github.com/Tricertops/KeepLayout - выглядит неплохо, умеет анимации
* вообще возможно лучще PureLayout https://github.com/PureLayout/PureLayout - там почти 1:1 соответствие API  c Apple + смотрим https://github.com/PureLayout/PureLayout/wiki/Tips-and-Tricks
* Сравнение PureLayout и остальных подходов https://github.com/PureLayout/PureLayout#purelayout-vs-the-rest


#### Appearance proxy,etc
* как работать с Appearance proxy - http://nscookbook.com/2013/01/ios-programming-recipe-8-using-uiappearance-for-a-custom-look/  и http://nshipster.com/uiappearance/
* https://stackoverflow.com/questions/26460706/uialertcontroller-custom-font-size-color
* официальная документация Apple https://developer.apple.com/library/ios/documentation/UIKit/Reference/UIAppearance_Protocol/#//apple_ref/occ/intfcm/UIAppearance/appearanceWhenContainedIn:
* Tutorial от Raywenderlich на эту тему https://www.raywenderlich.com/21703/user-interface-customization-in-ios-6
* CSS-style библиотека для Appearance https://github.com/robertwijas/UISS  - даже с поддержкой загрузки описаний с удаленного сервера
* еще одна CSS-style библиотека для Appearance https://github.com/tombenner/nui - вроде почаще обновляется и умеет и с конкретными экземплярами работать
* обзор существующих библиотек http://h4ckish.com/2015/12/31/how-to-style-your-ios-app-with-nui/
* UIAppearance for custom views еще статья http://petersteinberger.com/blog/2013/uiappearance-for-custom-views/
* как быть если с UIAlertView это все не работает а хочется tintColor задать - а например https://stackoverflow.com/questions/32856892/how-to-change-uialertcontroller-button-text-colour-in-ios9



#### Navigation Drawer (aka Slide-out)
* как ручками такой контроллер сделать https://www.raywenderlich.com/32054/how-to-create-a-slide-out-navigation-like-facebook-and-path
* https://habrahabr.ru/post/255209/ про SWRevealViewController с примерами красивыми, Storyboards умеет
* https://github.com/SocialObjects-Software/AMSlideMenu еще вариант
* https://github.com/aryaxt/iOS-Slide-Menu еще один простой вариант (TODO:а как там элементы то открываются? а со Storyboards как?)
* https://github.com/pkluz/PKRevealController PKRevealController2 - еще вариант


### Beta Testflight
* как это все вообще делается http://www.raywenderlich.com/101790/ios-beta-testing-with-testflight-tutorial
* если виснет на Authenticating with iTunes Store то может помочь https://stackoverflow.com/questions/18971710/application-loader-stuck-at-the-stage-of-authenticating-with-the-itunes-store
* ITMS-90096 - если все точно сделано (и файл - Default-568@2x.png) то читаем https://stackoverflow.com/questions/28830013/your-binary-is-not-optimized-for-iphone-5-itms-90096-when-submitting

### вспомогательные средства отладки GUI
* платный Reveal http://revealapp.com/ 
* платный Spark Inspector http://sparkinspector.com/ , умеет и Notification Center мониторить, умеет подключатся прямо в процессе работы (к симулятору правда, к устройствам надо framework)
* Debug view hierarchy кнопочка в XCode начиная с XCode 6 ( смотрим https://stackoverflow.com/questions/5150186/how-do-i-inspect-the-view-hierarchy-in-ios/ ) , в отличии от Reveal - не умеет менять данные и вообще менее...удобна 
* опенсорсный https://github.com/glock45/iOS-Hierarchy-Viewer (заодно и для CoreData), работает через браузер

### CloudKit
* Basic intro to CloudKit http://szulctomasz.com/cloudkit-introduction-and-lets-build-an-app/
* More detailed intro - iOS 8 By tutorials, Chapters 15 & 16
* БД с готовой синхронизацией с CloudKit https://github.com/yapstudios/YapDatabase/wiki/YapDatabaseCloudKit

### RestKit
* https://github.com/RestKit/RestKit
* http://www.raywenderlich.com/58682/introduction-restkit-tutorial
* https://github.com/RestKit/RKGist/blob/master/TUTORIAL.md

### Websocket library for iOS
* Например SocketRocket https://corner.squareup.com/2012/02/socketrocket-websockets.html
* Еще туториал по SocketRocket https://habrahabr.ru/post/214579/
* вообще с вебсокетами можно с http://www.elabs.se/blog/66-using-websockets-in-native-ios-and-android-apps начинать (и для Android - тоже)
* если на OS X эта несчастная демка руби-сервера из строки выше не ставится читаем все из https://stackoverflow.com/questions/8389301/os-x-rails-failed-to-build-gem-native-extension (есть например xcode-select)...
* Получаем данные по websocket используя swift и заполняем UITableView (сервер node.js)  https://habrahabr.ru/post/277635/  - см также комменты
* Библиотека для WebSocket на Swift https://github.com/daltoniam/Starscream и ее аналог на Objective-C https://github.com/acmacalister/jetfire - поддержка VoIP Sockets, Self-signed SSL, SSL pinning, возможность блоки использовать если нужно и других удобностей

### Circle CI
* https://circleci.com/docs/ios
 
### VIPER
* ссылки по VIPER от Rambler https://github.com/rambler-ios/The-Book-of-VIPER
* что есть VIPER https://github.com/rambler-ios/The-Book-of-VIPER/blob/master/IntroductionToVIPER.md
* кодогенератор для iOS-разработки от Rambler (с поддержкой VIPER) https://habrahabr.ru/company/rambler-co/blog/276275/

### Typhoon
* Управляем зависимостями в iOS-приложениях правильно: Знакомство с Typhoon https://habrahabr.ru/company/rambler-co/blog/258325/
* Управляем зависимостями в iOS-приложениях правильно: Устройство Typhoon https://habrahabr.ru/company/rambler-co/blog/260355/
* Управляем зависимостями в iOS-приложениях правильно: Typhoon Tips & Tricks https://habrahabr.ru/company/rambler-co/blog/264683/
* Управляем зависимостями в iOS-приложениях правильно: Модульность Typhoon https://habrahabr.ru/company/rambler-co/blog/261537/

### Плагины к Xcode
* How To Create an Xcode Plugin: Part 1/3 https://www.raywenderlich.com/94020/creating-an-xcode-plugin-part-1
* Xcode plugins http://nshipster.com/xcode-plugins/



## Системные дела
* Памятка пользователям SSH от Amarao http://habrahabr.ru/post/122445/
* ssh: Вытаскиваем для себя чужой порт из-за NAT https://habrahabr.ru/post/249515/

## Перехват трафика для отладки
* Charles Proxy кроссплатформенный https://www.charlesproxy.com/ 
* Cellist https://itunes.apple.com/us/app/cellist-http-debugging-proxy/id897814548?mt=12 

## NodeJS,etc
* 12 простых начальных шагов разработки модуля для Node.js от Митцгола http://habrahabr.ru/post/262057/

## Big Data и поисковые технологии

### Apache Spark/Hadoop
* знакомство с Apache Spark https://habrahabr.ru/company/piter/blog/276675/ - замена Hadoop более удобная и быстрая
* анализ логов с помощью Hadoop и Python http://habrahabr.ru/company/dca/blog/267107/ - по сути пример реализации DMP

### Scikit,etc 
* как узнать год выпуска песни по набору характеристик https://habrahabr.ru/post/264193/
* введение в машинное обучение со Scikit learn http://habrahabr.ru/post/264241/

### Apache Lucene/Nutch/YaCy/Поисковые технологии вообще
* Материал по работе с Apache Lucene и созданию простейшего нечёткого поиска https://habrahabr.ru/post/277509/
* Реализация поискового движка с ранжированием (простым) на python http://habrahabr.ru/post/263823/ и http://habrahabr.ru/post/263913/ и http://habrahabr.ru/post/263983/



## mBaaS
постепенно сюда переносить
* Parse Alternatives https://github.com/relatedcode/ParseAlternatives
* Top 5 Parse Alternatives http://www.raywenderlich.com/126098/top-5-parse-alternatives
* альтернативы parse https://habrahabr.ru/post/277979/
* Parse Server Guide https://github.com/ParsePlatform/parse-server/wiki/Parse-Server-Guide включая советы по тому где хостить 
* Что с Dashboard делать - а есть уже - parse server dashboard http://blog.parse.com/announcements/introducing-the-parse-server-dashboard/


### Parse Server Hosting 
* http://yourparse.com/
* http://parsehosting.net/
* как поставить на GAE+MongoLab https://medium.com/google-cloud/deploying-parse-server-to-google-app-engine-6bc0b7451d50#.bzan9x91a
* настройка с RocksDB https://github.com/ParsePlatform/parse-server/wiki/MongoRocks

### MongoDB hosting
* ObjectRocket https://objectrocket.com/parse 
* MongoLab/mLab https://mlab.com/plans/pricing/

### Realtime app framework с nodejs server
* http://socket.io/

## GameDev
* процедурная генерация случайных игровых подземелий https://habrahabr.ru/post/275727/
* процедурно-генерируемые карты мира на unity C#, часть 4(на 1-3 там ссылки внутри) https://habrahabr.ru/post/276551/


## Code generation
* http://habrahabr.ru/post/262711/быстрая и удобная генерация IL - как генерировать и ошибки решать (хочу на Java так!) и про обертку над ILGenerator. альтернатива - https://github.com/ElemarJR/FluentIL
* http://habrahabr.ru/post/254831/ генерация кода во время исполнения или пишем свой JIT-компилятор…базовые вещи как это все работает и простой пример. и ссылка на «совершенный код» - главу про динамическую генерацию кода для обработки изображений
* описание .NET Native http://habrahabr.ru/company/microsoft/blog/265889/
* Про Getting Started with LLVM Core Libraries https://www.goodreads.com/book/show/23381764 также не забываем и про примеры с Kaleidoscope / комменты про llst.org
* LLVM: компилятор своими руками. Введение https://habrahabr.ru/post/277717/
* исследования с LLVM http://habrahabr.ru/company/abbyy/blog/265871/ - пример как исследования проводить и как clang cо своим проходом использовать
* CLang API: начало http://habrahabr.ru/post/148508/ правда статья 2012 года
* http://www.dabeaz.com/ply/ - базовый аналог lex+yacc с кучей примеров на python
* Python ANTLR target https://github.com/antlr/antlr4-python2


## Базы данных
* как работает РСУБД http://habrahabr.ru/company/mailru/blog/266811/
* Postgres NoSQL лучше, чем MongoDB? http://habrahabr.ru/post/272735/
* проектирование документ-ориентированного API на Postgres http://habrahabr.ru/users/the_unbridled_goose/topics/
  
## Web Dev  

### Extensions
* Chrome Extension in 15 seconds http://extensionizr.com/ https://github.com/altryne/extensionizr
* создаем свое расширение для Google Chrome http://habrahabr.ru/post/198652/


### ASP.NET 
* серия уроков ASP.NET MVC http://habrahabr.ru/post/175999/
* пишем приложения для ASP.NET vNext на Mac http://habrahabr.ru/post/243483/  

### Flask
*  Мега-учебник Flask http://habrahabr.ru/post/193242/
   
    
## Системы сетевого логгирования 
* Sentry http://getsentry.com - умеет NSError, вроде не умеет Android, странные группировки, вроде opensource
* Rollbar http://rollbar.com 
    
## Various
* badges for projects http://shields.io/
* недо-RPG из проекта - http://getbadges.io - пример https://intari-readingtracker.getbadges.io/activity
* Что нам стоит сайт распарсить. Основы webdriver API http://habrahabr.ru/post/272105/
* stock-картинки в том числе бесплатные stock.xchng сейчас они http://www.freeimages.com/
* в тему "Заблуждения программистов о.." - Заблуждения программистов о телефонных номерах https://habrahabr.ru/post/279751/
* бесплатные сайты с векторной графикой https://habrahabr.ru/company/ua-hosting/blog/278473/
* альтернативы Mandrill (который сильно платным стал даже на минимальном плане) https://habrahabr.ru/post/280634/ 
* генерация случайных картинок с роботами https://robohash.org/
* полезные ссылки для Java-программиста https://habrahabr.ru/company/luxoft/blog/280784/ aka https://github.com/Vedenin/useful-java-links / https://github.com/Vedenin/useful-java-links/tree/master/link-rus
* шпаргалки для Java-программиста InputStream в строку https://habrahabr.ru/company/luxoft/blog/278233/ + общее оглавление


### Вспомогательные средства для создания мессенджеров
* https://layer.com/features
* q-municate от quickblox

