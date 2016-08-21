# Набор моих пусть частично полезных ссылок по разработке и не только, уровень...разный

## Android 

* Вообще Busy Coder's читаем сначала по всем пунктам

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
* Android и Data Binding: обработка действий https://habrahabr.ru/post/305916/

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

### Network

#### Retrofit
* Retrofit)[http://square.github.io/retrofit/
* Consuming APIs with Retrofit https://guides.codepath.com/android/Consuming-APIs-with-Retrofit
* Retrofit — Getting Started and Create an Android Client https://futurestud.io/blog/retrofit-getting-started-and-android-client
* FutureStud's book about Retrofit (they also have one on Picasso) https://futurestud.io/books + https://futurestud.io/blog/retrofit-series-round-up

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
* Introduction to Automated Android Testing – Part 1 https://riggaroo.co.za/introduction-automated-android-testing/ обзор методов и средств тестирования
* Introduction to Automated Android Testing – Part 2 – Setup https://riggaroo.co.za/automated-android-testing-part-2-setup/
* Introduction to Android Testing – Part 3 https://riggaroo.co.za/introduction-android-testing-part3/ 


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
* https://play.google.com/store/apps/details?id=com.mobilitystream.android.jiraconnectpro
* https://play.google.com/store/apps/details?id=com.strintec.jiramini
* https://play.google.com/store/apps/details?id=com.tempo.tempoapp
* возможно https://play.google.com/store/apps/details?id=jira.soap&amp;hl=en


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
* вступление в реактивное программирование которое вы пропустили https://habrahabr.ru/post/279715/
* Howdy RxJava. https://medium.com/fuzz/howdy-rxjava-8f40fef88181#.q1uxtz8gd
* также см про rxSwift/ReactiveCocoa про iOS
* лекции от e-Legion по rx и в комментах описания и ссылки на ролики как и зачем вообще придумали rx https://habrahabr.ru/company/e-Legion/blog/272459/
* Notes on Reactive Programming Part I: The Reactive Landscape https://spring.io/blog/2016/06/07/notes-on-reactive-programming-part-i-the-reactive-landscape
* Notes on Reactive Programming Part II: Writing Some Code https://spring.io/blog/2016/06/13/notes-on-reactive-programming-part-ii-writing-some-code
* введение в RxJava aka почему Rx http://habrahabr.ru/post/269417/
* Реактивный двигатель для вашего Android-приложения https://www.youtube.com/watch?v=Eatfi4am0HU&feature=youtu.be&ab_channel=Mobius
* rx. ключевые типы http://habrahabr.ru/post/270023/
* rx. Жизненный цикл подписки http://habrahabr.ru/post/270975/
* rxJava создание последовательности https://habrahabr.ru/post/281633/
* грокаем RxJava часть 1 http://habrahabr.ru/post/265269/ - крутая штука. но retrolambda очень желательно. паттерн наблюдатель на стероидах.
* грокаем RxJava часть 2 http://habrahabr.ru/post/265583/
* грокаем RxJava часть 3 http://habrahabr.ru/post/265727/
* грокаем RxJava часть 4: Реактивный Android https://habrahabr.ru/post/265997/
* Rx ключевые типы http://habrahabr.ru/post/270023/
* rx борьба с вызовами суровой действительности http://habrahabr.ru/post/267243/
* как код на RxJava тестировать https://fedepaol.github.io/blog/2015/09/13/testing-rxjava-observables-subscriptions/
* блог Advanced Rx http://akarnokd.blogspot.com/
* пример зачем нужен Dagger и как работать с rxPermissions (Android API 23+) https://habrahabr.ru/post/282193/ 
* сама RxPermissions https://github.com/tbruyelle/RxPermissions
* rxBinding https://github.com/tbruyelle/RxPermissions превращание event'ов в Observables
* The Art of Rx https://habrahabr.ru/company/jugru/blog/282784/
* Multicasting in rxJava http://blog.danlew.net/2016/06/13/multicasting-in-rxjava/
* Shake Detector для Android на RxJava https://habrahabr.ru/company/badoo/blog/304488/
* Основы реактивного программирования под Android на практическом пример https://habrahabr.ru/post/306746/


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
* быстрое создание красивой About page https://github.com/medyo/android-about-page
* Кюветы Android, часть 1: SDK https://habrahabr.ru/post/279811/
* Кюветы Android, часть 2: SDK & Libs https://habrahabr.ru/post/280190/
* Кюветы Android, часть 3: SDK & rxJava https://habrahabr.ru/post/281312/ 
* Dagger 2. Лечим зависимости по методике Google https://habrahabr.ru/company/dataart/blog/283018/
* Inject everything — ViewHolder and Dagger 2  https://medium.com/@froger_mcs/inject-everything-viewholder-and-dagger-2-e1551a76a908#.xf1xdklnv
* Dagger 2. Часть первая. Основы, создание графа зависимостей, Scopes https://habrahabr.ru/post/279125/
* Dagger 2. Часть вторая. Custom scopes, Component dependencies, Subcomponents https://habrahabr.ru/post/279641/
* Дружественное введение в Dagger 2 часть 2 https://habrahabr.ru/post/308040/
* Ловим усталось с помощью Android Wear https://geektimes.ru/company/dataart/blog/272074/
* Автоматизированное тестирование базовой доступности интерфейсов Android-приложений https://habrahabr.ru/post/280222/
* Краткое руководство по созданию навигации на основе фрагментов https://geektimes.ru/company/nixsolutions/blog/276362/ - вариант с одной активностью и кучей фрагментов
* Анимация Floating Action Button в Android https://geektimes.ru/company/nixsolutions/blog/276128/
* Овладение Coordinator Layout http://habrahabr.ru/post/270121/
* что есть Constraint Layout и зачем оно нужно - https://habrahabr.ru/company/livetyping/blog/302106/ если кратко - крутая штука
* https://blog.stylingandroid.com/constraintlayout-part-1/ + https://blog.stylingandroid.com/constraintlayout-part-2/ + https://blog.stylingandroid.com/constraintlayout-part-3/
* landing pages http://www.applandr.com/
* аудиорекордер с паузой https://github.com/lassana/continuous-audiorecorder
* Android RecyclerView Tutorial https://www.raywenderlich.com/126528/android-recyclerview-tutorial  для тех кто Busy Coder's не читал
* 3DO и Android NDK и как бы во что не вляпаться… https://habrahabr.ru/post/303888/
* Краткий обзор Kotlin и сравнение с C# https://habrahabr.ru/post/281759/
* Deep Linking на Android https://developer.android.com/training/app-indexing/deep-linking.html
* По следам Google I/O 2016 — новый Firebase: интеграция с Android https://habrahabr.ru/company/google/blog/305308/
* CWAC-NetSecurity - порт Network Security Configuration из Android N https://commonsware.com/blog/2016/07/11/backporting-android-n-network-security-configuration.html (подразумевается использование OkHttp3)
* Android Layouts - a new worlds - Google I/O 2016 https://www.youtube.com/watch?v=sO9aX87hq9c&ab_channel=AndroidDevelopers
* Android application architecture: Get ready for the next billion! https://www.youtube.com/watch?v=70WqJxymPr8
* Google I/O 2016 Live Blog http://www.anandtech.com/show/10332/google-io-2016-live-blog
* Android RecyclerView tutorial https://www.raywenderlich.com/126528/android-recyclerview-tutorial
* свой keyguard https://habrahabr.ru/post/220689/ + https://stackoverflow.com/questions/5829671/how-to-customize-androids-lockscreen
* Перехват вызовов функций нативных библиотек в Android приложениях https://habrahabr.ru/post/238619/
* Android string.xml — несколько вещей, которые стоит помнить https://habrahabr.ru/post/307798/

### Support library
#### Percent support library
да, теперь это официально
* Percent based layout https://plus.google.com/+AndroidDevelopers/posts/C8oaLunpEEj
* Официальное описание https://developer.android.com/tools/support-library/features.html?linkId=16439958#percent
* Как использовать, часть 1 https://blog.stylingandroid.com/percent-part-1/
* Как использовать, часть 2 https://blog.stylingandroid.com/percent-part-2/
* Использование библиотеки Android support percent на примере PercentRelativeLayout https://habrahabr.ru/post/308152/


### Аудиовидео плееры / Android
* https://google.github.io/ExoPlayer/ но смотрим https://habrahabr.ru/post/307232/про проблему с игрой нескольких потоков например
* https://github.com/Bilibili/ijkplayer


### Picture-in-Picture
Да, это есть на Android и давно было. И более общий функционал есть
* какие нужны permissions - «draw over other apps»  aka android.permission.SYSTEM_ALERT_WINDOW
* как сделать - а читаем https://stackoverflow.com/questions/10266959/having-application-running-above-other-app

#### Примеры
* https://play.google.com/store/apps/details?id=gpc.myweb.hinet.net.PopupVideo просто видео с popup'ами
* штатно поддерживает BSPlayer http://android.mobile-review.com/articles/40661/   https://play.google.com/store/apps/details?id=com.bsplayer.bspandroid.free&hl=ru - включается долгим тапом по Back
* https://play.google.com/store/apps/details?id=sgw.seegoatworks.android.app.floattube
* https://play.google.com/store/apps/details?id=ms.dev.luaplayer_va
* Awesome Pop-up video - с XPosed может очень многое но можно и без
* Facebook - используется не для видио а для показа когда кто-то что-то прилслал




### Android TV
* Портирование Android-приложения под Android TV и Nexus Player https://habrahabr.ru/company/intel/blog/251323/
* Device Lab от Google: Android TV https://habrahabr.ru/article/302492/
* NVIDIA Shield и Plex - как пример возможностей https://www.plex.tv/blog/nvidia-shield-you-complete-us/


## iOS 
* Сертификация в Apple Developer Center простым и понятным языком https://habrahabr.ru/post/280626/ для чайников или если последовательность забыта
* Оформление как Российской организации (или ИП! так можно!) в Apple Developer Program https://habrahabr.ru/company/scorocode/blog/305990/
* Использование NSOperation и NSOperationQueue в Swift http://habrahabr.ru/post/267843/ (перевод туториала Ray Wenderlich)
* Multithreading using NSOperation - хорошее описание включая например паузу https://izeeshan.wordpress.com/2014/08/17/multi-threading-using-nsoperation/
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
* типа красивый способ сделать синглтон https://habrahabr.ru/post/282169/ обертки,все такое - правда если оно вообще надо
* как создать Static Framework под iOS https://habrahabr.ru/post/280286/ 
* Пишем VoIP iOS чат на CORE AUDIO для конкурса VK Mobile Challenge https://habrahabr.ru/post/279517/
* рассылка iOS Dev Weekly с полезными ссылками для разработчиков https://iosdevweekly.com
* имитация Remote Notifications для симулятора https://github.com/acoomans/SimulatorRemoteNotifications (старый старый проект)
* полезные утилиты и так далее для разработчика под iOS https://habrahabr.ru/post/283576/
* Creating and distributing iOS Frameworks https://www.raywenderlich.com/126365/ios-frameworks-tutorial  (включая работу с CocoaPods и включая подключение Pod'ов с github url)
* Поддержка Siri в своем приложении https://habrahabr.ru/post/303316/
* Document provider tutorial https://www.raywenderlich.com/131668/document-provider-tutorial 
* Генерамба — кодогенератор для iOS разработки https://habrahabr.ru/company/rambler-co/blog/276275/ (для VIPER в том числе) 
* The Book of VIPER https://github.com/rambler-ios/The-Book-of-VIPER
* Блоки и target-action включая примеры как прописать использование блоков для кнопок например https://habrahabr.ru/post/276599/
* Как писать видео QuickTime Player'ом с iOS device http://www.apptamin.com/blog/capture-iphone-ipad-screen-video/
* визуальный редактор NSPredicate'ов https://github.com/arvindhsukumar/PredicateEditor  - iOS9, Swift-only
* Сколько приложению стоит одновременно держать сетевых коннектов http://blog.mugunthkumar.com/articles/mobile-apps-and-number-of-concurrent-connections/ 
* Avoiding Common Networking Mistakes от Apple https://developer.apple.com/library/mac/documentation/NetworkingInternetWeb/Conceptual/NetworkingOverview/CommonPitfalls/CommonPitfalls.html


# OS X 
* Core Graphics on OS X Tutorial https://www.raywenderlich.com/128614/core-graphics-os-x-tutorial  а вообще...PaintCode?

### In-app purchases
* In-App Purchases Tutorial: Getting Started https://www.raywenderlich.com/105365/in-app-purchases-tutorial-getting-started
* IAP Helper https://github.com/saturngod/IAPHelper для обычных
* MKStoreKit - странный он какой то
* RMStore https://github.com/robotmedia/RMStore - просто и удобно. недостаток - если надо reciept verification то придется отключать поддержку Bitcone (из-за OpenSSL)


### Swift
* как сделать это в Swift https://thatthinginswift.com/ - много интересного
* dispatch_async в Swift https://thatthinginswift.com/background-threads/ 
* замена dispatch_async в Swift более короткая https://ijoshsmith.com/2014/07/05/custom-threading-operator-in-swift/
* почему компиляция Swift может тормозить https://habrahabr.ru/post/283106/  + https://spin.atomicobject.com/2016/04/26/swift-long-compile-time/
* Testing in Swift https://spin.atomicobject.com/2016/05/02/testing-swift-code/
* What's New in Swift 3 https://www.raywenderlich.com/135655/whats-new-swift-3 
* Core Data + Swift для самых маленьких: необходимый минимум (часть 1) https://habrahabr.ru/post/303512/
* Core Data + Swift для самых маленьких: необходимый минимум (часть 2) https://habrahabr.ru/post/303798/
* Core Data + Swift для самых маленьких: необходимый минимум (часть 3) https://habrahabr.ru/post/304586/
* https://thatthinginswift.com/
* https://www.hackingwithswift.com/
* https://developer.apple.com/library/ios/documentation/Swift/Conceptual/BuildingCocoaApps/InteractingWithObjective-CAPIs.html
* доступ к Swift-коду из ObjC если оно "само" не получается http://stackoverflow.com/a/27251979/1063214
* Obj-C categories & Swift https://stackoverflow.com/questions/24064627/whats-the-proper-way-to-use-an-objective-c-category-within-swift
* Obj-C blocks & Swift https://stackoverflow.com/questions/27367768/how-to-write-this-objective-c-block-in-swift-syntax?rq=1
* CocoaPods & Swift https://www.raywenderlich.com/97014/use-cocoapods-with-swift - в том числе - зачем нужна use_frameworks! - а нужна она потому что стандартная библиотека Swift НЕ часть iOS
* В поисках чистой архитектуры (1-я часть) — Swift 3.0 https://habrahabr.ru/post/306206/   интересная статья заодно про VIPER-style
* Kill your giant viewDidLoad in Swift и зачем так https://thatthinginswift.com/kill-your-viewdidload/



### ReactiveCocoa/rXXX
* RxSwift в действии — пишем реактивное приложение https://habrahabr.ru/post/276971/
* введение реактива в архитектуру iOS-приложений https://habrahabr.ru/post/300962/
* шпаргалка по операторам rxSwift https://habrahabr.ru/post/281292/ 
* rxSwift работа с GUI https://habrahabr.ru/post/283128/ 
* Тестируем реактивность — как писать unit-тесты для RxSwift tutorial https://habrahabr.ru/post/304866/

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
* IBInspectable/IBDesignable http://nshipster.com/ibinspectable-ibdesignable/ - если проблемы то значит собрали статикой и либо use_frameworks либо исходники в текст
* CustomViewKit https://github.com/yume190/CustomView
* Custom AlertView https://github.com/Raizlabs/RaisinToast
* расширенный выбор картинки в зависимости от набора/ориентации https://github.com/kevindelord/UIImage-Autoresize
* как сделать свою кнопку на ячейке таблицы...не одну https://habrahabr.ru/post/261905/
* custom tabbar https://github.com/winslowdibona/TabDrawer
* https://thatthinginswift.com/upgrade-tableview-loading-state/ как сделать Table View с Loading state не завязывая все на один гигатский класс, Swift
* как использовать XLIFF https://habrahabr.ru/company/redmadrobot/blog/302682/ (также в комментах - как тестировать под другой локалью)
* Model-View-Controller (MVC) in iOS: A Modern Approach https://www.raywenderlich.com/132662/mvc-in-ios-a-modern-approach
* Self-sizing Table View Cells https://www.raywenderlich.com/129059/self-sizing-table-view-cells
* Если хочется UILabel с анимацией текста если он не влезает https://github.com/cbpowell/MarqueeLabel - заодно это пример на IB_DESIGNABLE
* Если хочется замену UILabel с наворотами https://github.com/TTTAttributedLabel/TTTAttributedLabel - заодно это пример на IB_DESIGNABLE
* Пробуем XCode Live Rendering https://habrahabr.ru/post/239257/
* как сделать свой аналог UIAlertController с вводом текста читаем https://github.com/mattneub/custom-alert-view-iOS7 iOS8+/Swift
* как работать с клавиатурой http://macoscope.com/blog/working-with-keyboard-on-ios/ - а есть и просто https://github.com/FinalCAD/iOS-KeyboardManager и https://github.com/kam800/KBKeyboardObserver


#### ObjC непонятки
* http://goshdarnblocksyntax.com/

#### Блоки (Если лень книжку почитать, все ОЧЕНЬ старое)
* О блоках и их использовании в Objective-C часть 1-ая https://habrahabr.ru/post/119877/
* О блоках и их использовании в Objective-C часть 2-ая https://habrahabr.ru/post/120869/
* О блоках и их использовании в Objective-C часть 3-ая https://habrahabr.ru/post/121958/
* Objective-C: как работают блоки https://habrahabr.ru/post/271255/ - в том числе про милые команды вроде clang -rewrite-objc -ObjC main.m -o out.cpp

#### Cocoapods если не в других местах
* Сеть - более качественная замена AFNetworking https://github.com/Alamofire/Alamofire
* обфускация важных констант https://github.com/pjebs/Obfuscator-iOS
* обфускация бинарников https://github.com/Polidea/ios-class-guard
* потереть все комменты https://github.com/igorbarinov/deployment-scrpits/tree/master/remove-comments

#### Тесты
* Да начнется unit-тестирование (Objective-C) https://habrahabr.ru/post/258953/
* Практический применение Unit-тестирования под iOS https://habrahabr.ru/post/262945/
    
#### Аудио-видео плееры / iOS
* AVPlayer и компания системные конечно же. например PiP даже на iOS10 будет только с ними. Но требования по форматам, иногда долгий старт при сетевой загрузке.

##### MobileVLCKit
MobileVLCKit http://code.videolan.org/videolan/VLCKit.git 
* http://www.feepk.net/2014/12/02/mobilevlckit-and-vlckit-part-1/ + http://www.feepk.net/2015/02/18/mobilevlckit-and-vlckit-part-2/
* брать либо pod MobileVLC-prod - он 2.7.9
* либо ручками собрать:
```Shell
cd %DIR%
git clone -v http://code.videolan.org/videolan/VLCKit.git
cd VLCKit
git fetch origin
git branch -v -a посмотреть бранчи
git checkout -b iOS-2.7 origin/iOS-2.7
./buildMobileVLCKit.sh -f #  build for simulator and device
```
чтобы потом пересобрать - грохнуть MobileVLCKit/ImportedSources надо как минимум
* лицензия: судя по том что делает pod install - достаточно  положить в папку рядом с MobileVLCKit.Framework файл лицензии и выложить свои патчи к самому MobileVLCKit
* как образец плеера - Dropin-Player - он под еще более либеральной лицензией
         
##### IJKPlayer ? 
* https://github.com/Bilibili/ijkplayer  iOS (в будущем)/Android
    
     
    
#### Чем нарезать GUI
* Sketch (вместо фотошопа) http://habrahabr.ru/post/252063/ - OS X only. а еще см https://vc.ru/p/sketch - на тему чем оно лучще фотошопа
* Droptimizer http://12rockets.com/droptimizer/ нарезка правильного арта по @3x
* Slicy http://www.macrabbit.com/slicy/help/  - автонарезатор из фотошопа (но надо тегировать специальным образом). @3x не поддерживается пока.
* PaintCode (если он нам подходит)
* А еще есть Sketch-style IBAnimatable https://github.com/JakeLin/IBAnimatable/ - дизайн GUI ЦЕЛИКОМ в XCode…хмм

#### AppStore tools,etc
* простая и удобная запись видео с симулятора с аннотациями и так далее http://www.jaml.co.uk/simcap.html 
* тоже самое бесплатно но чуть сложнее - https://stackoverflow.com/questions/26523622/how-can-i-run-record-an-ios-app-in-the-xcode-6-ios-simulator
 
 
#### Autolayout
* Auto Layout Tutorial in iOS 9 Part 1: Getting Started https://www.raywenderlich.com/115440/auto-layout-tutorial-in-ios-9-part-1-getting-started-2
* Auto Layout Tutorial in iOS 9 Part 2: Constraints https://www.raywenderlich.com/115444/auto-layout-tutorial-in-ios-9-part-2-constraints
* Autolayout DSL https://github.com/SnapKit/SnapKit
* KeepLayout https://github.com/Tricertops/KeepLayout - выглядит неплохо, умеет анимации
* вообще возможно лучще PureLayout https://github.com/PureLayout/PureLayout - там почти 1:1 соответствие API  c Apple + смотрим https://github.com/PureLayout/PureLayout/wiki/Tips-and-Tricks
* Сравнение PureLayout и остальных подходов https://github.com/PureLayout/PureLayout#purelayout-vs-the-rest
* Advanced AutoLayout https://www.objc.io/issues/3-views/advanced-auto-layout-toolbox/

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
* еще одна библиотека для стилизации https://github.com/146BC/StyleKit  Swift/Carthage  (хотя pod можно подключить)




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

### Как сделать submit в AppStore если клиент имеет Individual account
#### Ситуация
* у нас есть свой Individual-аккаунт
* у клиента Individual account, пароль от аккаунта он давать не хочет. Company account тоже не хочет делать. 
* Надо выложить приложение от имени клиента
* Xcode 7

#### Что делать
* получаем у клиента доступ в iTunes Connect на новый Apple ID (не тот на котором у нас все) с правами Application Manager / Developer
* просим клиента (или через удаленный доступ на его машине) создаем application record. можно и через Xcode
* просим клиента (или через удаленный доступ на его машине)  его developer profile (да да я в курсе что можно руками все сертификаты и профили попросить но это дольше будет)
* у себя при сборке ставим нужным provisioning profile (XC:…клиента)  а code signing - automatic (или iOS Developer клиента ).
* Собирать для build-only device
* Archive
* Export с use local signing assets. экспортируется все подписанное distribution-сертификатом клиента если все правильно сделали. Если получаем ругань от XCode на этой стадии - удаляем Developer Profile клиента (сертификаты останутся) и перезапускаем XCode
* заходим своим  новым Apple ID в Application Loader и выгружаем через него IPA. Он успешно загрузится
* настраиваем своим новым Apple ID все что нужно в iTunes Connect

####  на что обратить внимание
* что у клиента получены все сертификаты (запросить если нет
* что у клиента корректно настроен provisioning profile (если надо in-app, push и так далее). Если настраивали через XCode то это будет XC:…профиль
* при отправке не забываем in-app'ы тоже добавить в список на отправку если они есть.

#### что делать в случае проблем
* если после установки Developer Profile клиента система просит пароль от его Apple ID…удаляем профиль (сертификаты и provisioning profile останутся)
* после любых операций с профилями и малейших глюках - перезапуск XCode

#### что видимо не будет работать
* crash log’и от Apple не получить, те что через XCode

####  полезные утилиты для iTunes Connect
* генерация Privacy Policy http://generator.appprivacy.net/privacy/ если руками никак
* скриншоты - https://shotbot.io/ (19,99 USD  one time)
* автонарезалка иконок https://makeappicon.com/ios9icon

#### полезная информация
* App Store Review times http://appreviewtimes.com/ aka https://twitter.com/appreviewtimes ну и https://developer.apple.com/support/app-review/  - пока что - 1-2 дня включая выходные. Просят пополнять их базу
* How to reproduce bugs reported against App Store submissions https://developer.apple.com/library/ios/qa/qa1764/_index.html



### вспомогательные средства отладки GUI
* платный Reveal http://revealapp.com/ 
* платный Spark Inspector http://sparkinspector.com/ , умеет и Notification Center мониторить, умеет подключатся прямо в процессе работы (к симулятору правда, к устройствам надо framework)
* Debug view hierarchy кнопочка в XCode начиная с XCode 6 ( смотрим https://stackoverflow.com/questions/5150186/how-do-i-inspect-the-view-hierarchy-in-ios/ ) , в отличии от Reveal - не умеет менять данные и вообще менее...удобна 
* опенсорсный https://github.com/glock45/iOS-Hierarchy-Viewer (заодно и для CoreData), работает через браузер

### CloudKit и CoreData-с-синхронизацией
* Basic intro to CloudKit http://szulctomasz.com/cloudkit-introduction-and-lets-build-an-app/
* Еще одно https://yalantis.com/blog/work-cloudkit/
* CloudKit: The fastest route to implementing the auto-synchronizing app you've been working on? https://www.bignerdranch.com/blog/cloudkit-the-fastest-route-to-implementing-the-auto-synchronizing-app-youve-been-working-on/
* More detailed intro - iOS 8 By tutorials, Chapters 15 & 16
* БД с готовой синхронизацией с CloudKit https://github.com/yapstudios/YapDatabase/wiki/YapDatabaseCloudKit
* Swift 2.0 фреймворк для поддержки по сути CoreData через CloudKit https://github.com/nofelmahmood/Seam
* Как (правильно) сделать Tiny data/All devices на CloudKit http://initwithfunk.com/blog/2015/06/26/as-i-learn-cloudkit-part-0/
* А еще можно просто Ensembles использовать хотя бы бесплатный - http://www.ensembles.io/ спасибо http://mjtsai.com/blog/2016/06/17/the-deprecation-of-icloud-core-data/
** https://stackoverflow.com/questions/30675541/ensembles-in-ios-swift
** https://github.com/drewmccormack/ensembles/tree/master/Examples/Simple%20Sync
** https://github.com/drewmccormack/ensembles - можно с него начать



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
* https://www.raywenderlich.com/128313/parse-server-tutorial migration
* Российская Scorocode https://habrahabr.ru/company/scorocode/blog/303954/ https://vc.ru/p/app-creation-time


### Parse Server Hosting 
* https://www.nodechef.com/pricing - самый на мой взгляд нормальный пока
* http://yourparse.com/
* http://parsehosting.net/
* как поставить на GAE+MongoLab https://medium.com/google-cloud/deploying-parse-server-to-google-app-engine-6bc0b7451d50#.bzan9x91a
* настройка с RocksDB https://github.com/ParsePlatform/parse-server/wiki/MongoRocks
* Back4App https://www.back4app.com/pricing/ большой план для разработчиков. лимиты по количеству запросов в месяц всегда
* https://www.sashido.io/#Pricing pay-as-you-go и минимум - 5 usd/месяц. база - 1 Gb, дополнительно - 16US$/gb. Social login тоже прямо заявлен только а зачем он нужен? free private github repo for each app. блин - там waitlist. они НЕ готовы
* http://parse-hosting.oursky.com/ 20 USD/месяц, billed annually
* https://www.backand.com/parse-alternative/
* и Heroku и помним что есть интеграция Parse и Heroku http://blog.parse.com/announcements/introducing-heroku-parse/
* DigitalOcean как руками настроить : https://www.digitalocean.com/community/tutorials/how-to-run-parse-server-on-ubuntu-14-04 + https://www.digitalocean.com/community/tutorials/how-to-migrate-a-parse-app-to-parse-server-on-ubuntu-14-04
* смотрим также https://github.com/ParsePlatform/parse-server/wiki

#### NodeChef
изначально - хостинг для приложений Meteor

* цены https://nodechef.com/pricing - от 9 USD, искуственных лимитов на количество запросов - нет
* deploy cloud coude - одной командой (как и deploy статики)
* используют RocksDB Storage Engine в MongoDB.
* автоматические бекапы MongoDB каждые 16 часов + можно подключится MongoChef'ом и самостоятельно сделать
* автоматический SSL (Let's Encrypt используют, можно свои сертификаты)
* есть US-East и EU-West локации.
* Static asset hosting + реверс-прокси
* Background Jobs есть (в отличии от некоторых конкурентов)
* LiveQuery есть (на данный момент - при одном App Container)
* Различные метрики как БД так и AppServer есть
* шаблоны писем и страниц для e-mail verification, сброса пароля и так далее - можно настроить например чтобы было MyCoolAppName
* ParseConfig поддерживается
* Почту отправляют через MailGun / Sendgrid (пользователь должен указать API Key)
* Выбор версии Parse Server при желании
* база где то 12 USD/Gb/Месяц после первого Gb

#### Недостатки
* если кусок CloudCode упал - он просто упал. в логах чисто. надо обертывать в try/catch и писать в console.error
* их гуглогруппу надо читать, настройки шаблонов почты...это было не очевидно
* логи Cloud Code смотрятся ТОЛЬКО через App Logs (и в обратной сортировке). Через ту же Parse Dashboard - не видно вообще. транслировать 
* деплой-тулза требует указания логина и пароля....каждый раз. или в командной строке.
* не прописано внятно что для работы e-mail verification/сбросов пароля, указанный домен должен 1:1 совпадать с тем что в MailGun

#### SashiDo
* интеграция с github а не своя деплоилка как у NodeChef https://blog.sashido.io/how-to-set-up-cloud-code-on-sashido/
* 4.95 USD/месяц минимум за приложение. но есть лимиты на запросы (превышение - платно). 
* Второй и дальше гигабайты базы - по 16 USD/Gb/месяц
* Логи в панельке таки есть
* Advanced Cloud Code - там и custom express.js apps https://blog.sashido.io/our-big-things-to-announce/ - хотя сильно новое?
* база видно что двухузловая
* есть в том их примере на github как все локально запускать и чтобы после заливки тоже жило

#### Недостатки
* за custom domain вроде как в саппорт
* LiveQuery - ?
* background jobs нет. обещали к сентябрю 2016
* про бекапы пока не слышно. может и есть но не заявлено как получить доступ к 


### MongoDB hosting
* ObjectRocket https://objectrocket.com/parse 
* MongoLab/mLab https://mlab.com/plans/pricing/
* Хостинг MongoDB, Postgres,etc https://www.compose.io/pricing/ 
* Еще хостинг MongoDB https://scalegrid.io/pricing.html
* Cравнение двух предыдущих от Scalegrid https://scalegrid.io/mongodb/hosting-comparison.html

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
* вообще по Postgres читаем например https://habrahabr.ru/users/rdruzyagin/topics/  
* Работа с геолокациями в режиме highload https://habrahabr.ru/post/228023/
* Аудит таблиц с пространственными объектами в PostGIS/PostgreSQL https://habrahabr.ru/post/137161/

  
## Web Dev  

### Extensions
* Chrome Extension in 15 seconds http://extensionizr.com/ https://github.com/altryne/extensionizr
* создаем свое расширение для Google Chrome http://habrahabr.ru/post/198652/


### ASP.NET 
* серия уроков ASP.NET MVC http://habrahabr.ru/post/175999/
* пишем приложения для ASP.NET vNext на Mac http://habrahabr.ru/post/243483/  

### Flask
*  Мега-учебник Flask http://habrahabr.ru/post/193242/
   
## Various (=растащить в будущем по разным местам)
* Удачная модель ветвления для Git http://habrahabr.ru/post/106912/ - must read вообще то и в системах поддержано
* Rebase Flow. Способ приготовления и его поддержка в GitHub, GitLab, BitBucket https://habrahabr.ru/company/at_consulting/blog/283326/
* Wakatime http://wakatime.com и да - Chrome если надо  - поддерживается
* Rescuetime http://rescuetime.com 
* badges for projects http://shields.io/
* недо-RPG из проекта - http://getbadges.io - пример https://intari-readingtracker.getbadges.io/activity
* Как парсить сайты - jsoup https://jsoup.org/  https://stackoverflow.com/questions/9071568/parse-web-site-html-with-java
* Что нам стоит сайт распарсить. Основы webdriver API http://habrahabr.ru/post/272105/ это если мало прошлого варианта
* stock-картинки в том числе бесплатные stock.xchng сейчас они http://www.freeimages.com/
* в тему "Заблуждения программистов о.." - Заблуждения программистов о телефонных номерах https://habrahabr.ru/post/279751/
* бесплатные сайты с векторной графикой https://habrahabr.ru/company/ua-hosting/blog/278473/
* альтернативы Mandrill (который сильно платным стал даже на минимальном плане) https://habrahabr.ru/post/280634/ (реально - Mailgun вполне себе)
* генерация случайных картинок с роботами https://robohash.org/
* шпаргалки для Java-программиста: коллекции в Java, стандартные и не очень https://habrahabr.ru/company/luxoft/blog/256877/
* полезные ссылки для Java-программиста https://habrahabr.ru/company/luxoft/blog/280784/ aka https://github.com/Vedenin/useful-java-links / https://github.com/Vedenin/useful-java-links/tree/master/link-rus
* типовые задачи: обход Map, подсчет количества вхождений в подстроку https://habrahabr.ru/company/luxoft/blog/278313/
* шпаргалки для Java-программиста: InputStream в строку https://habrahabr.ru/company/luxoft/blog/278233/
* шпаргалки для Java-программиста: библиотеки для парсинга JSON https://habrahabr.ru/company/luxoft/blog/280782/ + общее оглавление
* расширения Stream API java 8 https://habrahabr.ru/post/262139/
* сборка гибридного приложения под Android https://habrahabr.ru/post/277729/
* PDF в России - стандарт или не стандарт? https://habrahabr.ru/company/abbyy/blog/105006/
* PDF с точки зрения программиста https://habrahabr.ru/company/abbyy/blog/108459/
* Блог Алексея Шипилева по производительности Java https://shipilev.net/
* как ПРАВИЛЬНО делать микробенчмарки в Java https://stackoverflow.com/questions/504103/how-do-i-write-a-correct-micro-benchmark-in-java
* эффективное использование github https://habrahabr.ru/company/2gis/blog/306166/
* обход certificate pinning на Android https://habrahabr.ru/post/307774/
* Как думать на SQL? https://habrahabr.ru/post/305926/
* В чем должен разбираться Frontend-разработчик https://habrahabr.ru/post/306716/
* Git Rebase: руководство по использованию https://habrahabr.ru/post/161009/
* Git rebase «по кнопке» https://habrahabr.ru/company/badoo/blog/193258/
* Чем опасен rebase, или как получилось, что 2*3=5 https://habrahabr.ru/post/179123/



### Вспомогательные средства для разработки
#### Системы удаленного логгирования
* Rollbar http://rollbar.com  По умолчанию просто последовательные логи. Умеет креши тоже. по умолчанию не делает группировку. dSYM'ы с пробелом в имени обрабатывает некорректно. Бесплатный план 5k событий в месяц. первый платный за 29 usd - 100k событий в месяц
* Sentry http://getsentry.com  Умеет NSError, вроде не умеет Android. Не умеет последовательно список событий вроде бы. Креши не умеет но вроде делают. Группировка по умолчанию странная. бесплатный - 250 событий day, а затем - за 9 долларов план с 9 событий в минуту. Opensource. и можно поставить себе.

#### Аналитика (все и под Android/iOS тоже живет)
* Countly http://count.ly. есть cloud edition, есть opensource edition есть enterprise edition. красивые графики и все такое. APM - конфликтует с кучей всего 
** установка OpenSource-версии на DigitalOcean https://medium.com/@countly/how-to-install-upgrade-and-backup-countly-on-a-digital-ocean-droplet-a-step-by-step-guide-8dde2764e407
** совсем однокликовый инсталлер Countly на DigitalOcean http://do.count.ly/install 
* Mixpanel http://mixpanel.com/free Timed events, visual events editor, user tracker, A/B test support. очень удобная, только надо немного разобратся. умеет автогенерить аналитику по переходам между view controllers на iOS.тарифы приемлимые (смотря для кого да) и есть партнерский план. есть user analytics. сам SDK - в исходниках.
* Amplitude https://amplitude.com/pricing Costs...a lot lot. big free plan, revenue verification
* Devtodev http://megamozg.ru/company/devtodev/blog/18664/
* Facebook Mobile Analytics https://vc.ru/p/facebook-mobile-analytics
* AWS Mobile Analytics https://aws.amazon.com/ru/mobileanalytics/faqs/
* также смотрим статью https://vc.ru/p/begin-app - там много советов в том числе по аналитике (а еще как трекер можно branch.io использовать)


#### Ловля крешей
* Testfairy умеет(если dSYM не с прробелом), Rollbar умеет(если dSYM не с пробелом), Countly заявлено что умеет в Opensource  edition(минимум какой то) и в Enterprise
* Crashlytics http://try.crashlytics.com crash reporting. бесплатно независимо от обьемов. умеет и NSLog'и с собой в крешлог включать.
* Hockeyapp - куплен MS. что-то последние версии у меня совсем мышей не ловили на iOS.
* Buddybuild - в том числе и ловля крешей с видеозаписю (а вообще это CI-система + аналог старого testflight)

#### CI
* Buddybuild бесплатный тариф есть но так - весьма платный
* Bitrise https://www.bitrise.io/
* Travis CI (для OpenSource либо платный)
* https://greenhouseci.com/
* Circle CI
* упрощенно и ручками - fastlane
* вообще смотрим https://github.com/ligurio/Continuous-Integration-services/blob/master/continuous-integration-services-list.md
* подьем CI iOS своими руками https://habrahabr.ru/company/livetyping/blog/302642/
* Jenkins - hosted
* Bamboo - hosted

#### Патчи
* Rollout https://rollout.io/ пока только iOS причем поддержку Swift только обещают. Минимальный hotpatching iOS-приложений даже в AppStore. В основном по сути защита от ситуаций "ой а оно внезапно падает на девайсах X а апдейт Apple долго аппрувит" но вообще можно все что угодно на JS цеплять к вызовам методов, например аналитику.

#### Видеозапись
* Testfairy цены https://app.testfairy.com/account/action/create-bug видеозапись действий приложения, NSLog'ов, сетевых запросов. заменой старому TestFlight тоже обещают что может. бесплатный план - 1k сессий в месяц. первый платный за 119 usd в месяц - 10к сессий. http://seductive-mobile.com/playbook/testfairy-visual-beta-testing-service-overview/ . Может не поймать логи за момент непосредственно перед крешем.
* UXCam https://uxcam.com/ video recording,heatmaps,etc

#### API Emulation
* Fake the backend while you develop the frontend http://jsonstub.com/
* Server Mock from https://apiary.io/

#### API Debugging 
* Runscope https://www.runscope.com/pricing-and-plans




### Вспомогательные средства для создания мессенджеров
* https://layer.com/features
* q-municate от quickblox

### custom apis,etc
* https://market.mashape.com/
* https://github.com/natanrolnik/NLRMashapeClient iOS-библиотека к ним


