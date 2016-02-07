# Набор пусть частично полезных ссылок по разработке

## Various
* badges for projects http://shields.io/
* недо-RPG из проекта - http://getbadges.io - пример https://intari-readingtracker.getbadges.io/activity


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
* FutureStud's book about Retrofit (they also have one on Picasso) https://futurestud.io/books

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
*оно - бесплатное. в отличии от Amplitude….и имеет лимиты https://developers.google.com/analytics/devguides/collection/other/limits-quotas а 500 hits per session может стать проблемой.

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


### Android/Various
* Что есть java.lang.Object http://habrahabr.ru/post/265373/
* Kata: Robolectric Integration http://coreylatislaw.com/kata-robolectric-integration/
* TDD vs BDD. В чем разница? http://dou.ua/forums/topic/8897/
* Варианты сжатия текстур на Android https://habrahabr.ru/company/intel/blog/276089/
* Кому жить, а кому умереть: приоритеты процессов в Android https://habrahabr.ru/post/276381/


## iOS
* AsyncDisplayKit Tutorial: Achieving 60 FPS scrolling http://www.raywenderlich.com/86365/asyncdisplaykit-tutorial-achieving-60-fps-scrolling

### Circle CI
* https://circleci.com/docs/ios

### Typhoon
* Управляем зависимостями в iOS-приложениях правильно: Знакомство с Typhoon https://habrahabr.ru/company/rambler-co/blog/258325/
* Управляем зависимостями в iOS-приложениях правильно: Устройство Typhoon https://habrahabr.ru/company/rambler-co/blog/260355/
* Управляем зависимостями в iOS-приложениях правильно: Typhoon Tips & Tricks https://habrahabr.ru/company/rambler-co/blog/264683/
* Управляем зависимостями в iOS-приложениях правильно: Модульность Typhoon https://habrahabr.ru/company/rambler-co/blog/261537/



## Системные дела
* Памятка пользователям SSH от Amarao http://habrahabr.ru/post/122445/
* ssh: Вытаскиваем для себя чужой порт из-за NAT https://habrahabr.ru/post/249515/
* 