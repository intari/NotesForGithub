# My link collection about various development issues

## Various
* badges for projects http://shields.io/

## iOS
### Circle CI
* https://circleci.com/docs/ios


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
* (Android Data Binding in RecyclerView)[http://habrahabr.ru/company/dataart/blog/267735/]
* (Data binding example with SearchView/RecyclerView) [https://github.com/ashdavies/data-binding]

### (Custom) Annotation processors
* (Annotation Processor to create arguments for android fragments without using reflections)[http://hannesdorfmann.com/android/fragmentargs/]
* (Annotation Processor to create arguments for android fragments without using reflections github)[https://github.com/sockeqwe/fragmentargs]
* (Parseleable Please)[http://hannesdorfmann.com/android/ParcelablePlease/]
* (Annotated Adapter)[http://hannesdorfmann.com/android/AnnotatedAdapter/] for ListViews/GridViews,etc
 

### Libraries by Jack Wharton,etc
* (Hugo - method call logger)[https://github.com/JakeWharton/hugo]
* Timber - autotagging logs

#### Butterknife
* Butterknife (GUI injection) https://github.com/JakeWharton/butterknife + https://jakewharton.github.io/butterknife/
* Butterknife vs Android Annotations htps://stackoverflow.com/questions/21279668/butterknife-vs-androidannotations
* How Butterknife actually works http://lgvalle.xyz/2015/05/04/butterknife/
* Knork: простейшая альтернатива ButterKnife в 160 строк кода http://habrahabr.ru/post/230857/

### Network
* API Debugging - Runscope https://www.runscope.com/pricing-and-plans

#### Retrofit
* Retrofit)[http://square.github.io/retrofit/
* Consuming APIs with Retrofit https://guides.codepath.com/android/Consuming-APIs-with-Retrofit
* Retrofit — Getting Started and Create an Android Client https://futurestud.io/blog/retrofit-getting-started-and-android-client
* FutureStud's book about Retrofit (they also have one on Picasso) https://futurestud.io/books


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





### Continouos Integration / Devlivery
* http://stablekernel.com/blog/continuous-delivery-android-part-1/
* http://stablekernel.com/blog/continuous-delivery-android-part-2/
* http://stablekernel.com/blog/unit-testing-continuous-delivery-for-android-part-3/

### Testing
* The evolution journey of Android GUI testing Cucumber — Espresso — Page Object Pattern)[https://medium.com/@neoranga55/the-evolution-journey-of-android-gui-testing-f65005f7ced8
* Roboletric,Espresso,JaCoCo,etc http://habrahabr.ru/company/rambler-co/blog/266837/
* Wait for it...a deep dive into Espresso's Idling Resources http://dev.jimdo.com/2014/05/09/wait-for-it-a-deep-dive-into-espresso-s-idling-resources/
* Заметки по тестированию, в том числе про mockito и Robotium https://www.bignerdranch.com/blog/testing-the-android-way/
* Working with Robolectric and Robotium in Android Studio and Gradle https://benwilcock.wordpress.com/2015/01/20/working-with-robolectric-and-robotium-in-android-studio-and-gradle/ + https://github.com/benwilcock/android-alltest-gradle-sample
* Different ways of testing exceptions in Java and JUnit http://blog.goyello.com/2015/10/01/different-ways-of-testing-exceptions-in-java-and-junit/

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


#### Travis CI
* com.android.ddmlib.ShellCommandUnresponsiveException  - http://stackoverflow.com/questions/32952413/gradle-commands-fail-on-api-23-google-api-emulator-image-armeabi-v7a bug in Android, one of workarounds https://code.google.com/p/android/issues/detail?id=189764&q=label%3APriority-Medium&colspec=ID%20Type%20Status%20Owner%20Summary%20Stars also put lower android emulator version
* issue with design support library https://github.com/codepath/android_guides/wiki/Setting-up-Travis-CI 
* https://blog.cyplo.net/2015/10/25/android-integration-test-timeouts/
* Google APIs http://stackoverflow.com/questions/28949722/android-tests-fail-on-travis-with-shellcommandunresponsiveexception/28949723#28949723
* Code coverage testing - https://github.com/ParsePlatform/Parse-SDK-Android + https://github.com/codecov/example-android/blob/master/.travis.yml
* see my  https://github.com/intari/MergeAdapterDemo


#### Circle CI
* 1 free builder even for private repositories (4 for OpenSource repositories). Github-only, no Bitbucket (per https://circleci.com/docs/faq )
* Looks like (per https://code.google.com/p/android/issues/detail?id=104305 ) they thought about android timeout issues...
* Continuous Integration on Android: Why we ditched Jenkins for Circle CI https://infinum.co/the-capsized-eight/articles/continuous-integration-on-android-why-we-ditched-jenkins-for-circle-ci
* Sample Circle CI + Espresso project https://discuss.circleci.com/t/a-sample-android-espresso-project/1212 https://github.com/circleci/EspressoSample
* Circle CI Dummy Android app https://github.com/circleci/circle-dummy-android
* What to do if timeout - https://stackoverflow.com/questions/33499046/android-project-automation-test-in-circleci-build-failed-with-an-exception (or read Espresso sample)

### JIRA Clients
* https://play.google.com/store/apps/details?id=jira.soap&amp;hl=en
* https://play.google.com/store/apps/details?id=com.mobilitystream.android.jiraconnectpro

### Play Store Autosubmission
* Gradle https://github.com/Triple-T/gradle-play-publisher (example from https://circleci.com/docs/android )
* Jenkins https://wiki.jenkins-ci.org/display/JENKINS/Google+Play+Android+Publisher+Plugin


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

## Системные дела
* Памятка пользователям SSH от Amarao http://habrahabr.ru/post/122445/
* ssh: Вытаскиваем для себя чужой порт из-за NAT https://habrahabr.ru/post/249515/
* 