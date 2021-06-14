
<p align="center">
  <a href="https://github.com/CarlyAdam/cracking-android">
    <img src="images/logo.png" alt="Logo" width="100" height="100">
  </a>

  <h3 align="center">Cracking the Android Interview</h3>


<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
     <a href="#About">About this project</a>
    </li>
      <li>
     <a href="#Fundamentals">Fundamentals</a>
    </li>
   <li>
     <a href="#Android_SDK">Android SDK </a>
    </li>
     <li>
      <a href="#Kotlin">Kotlin</a>
        </li>
  <li>
     <a href="#Gradle">Gradle</a>
    </li>
  <li>
     <a href="#Android_Studio">Android studio</a>
    </li>
   <li>
     <a href="#UI">UI</a>
    </li>
     <li>
     <a href="#Best_Practices">Best Practices</a>
    </li>
     <li>
     <a href="#Arquitecture">Arquitecture</a>
    </li>
  <li>
     <a href="#Network">Network operation</a>
    </li>
  <li>
     <a href="#Firebase">Firebase</a>
    </li>
   <li>
     <a href="#Test">Test</a>
    </li>
  <li>
     <a href="#Proguard">Proguard</a>
    </li>
  <li>
     <a href="#CI_CD">CI/CD</a>
    </li>
  <li>
     <a href="#Crash">Crash Reports</a>
    </li>
     <li>
     <a href="#MAD">MAD(Modern Android Development)</a>
    </li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About
After 7  years of experience in Android development, I have been on both sides as an interviewer and as a candidate.
Cracking a technical job interview can be a challenging task and we have to be prepared to demonstrate our knowledge. That's why I decided to create this study guide according to my experiences and try to keep it updated to help others and myself get the dream job when facing a new interview. 
Feel free to make a pull request and collaborate.

note: References come from authors of the blogs, stackoverflow posts and the online android community.

Enjoy it ;)

 ## Fundamentals
 🙂
 
* ✔️ Android components   :[ Reference](https://developer.android.com/guide/components/fundamentals)
* ✔️ Fragment lifecycle and Activity lifecyle
* ✔️ Implicity vs explicity intents
* ✔️ .dex files  :[ Reference](https://stackoverflow.com/questions/7750448/what-are-dex-files-in-android)
* ✔️ Multidex :[ Reference](https:/developer.android.com/studio/build/multidex)

* ✔️ Abstract class vs interface  :[ Reference](https://www.javatpoint.com/difference-between-abstract-class-and-interface)


## Android_SDK 
🛠
* ✔️ Components, Patterns, Architecture :[ Reference](https://code.tutsplus.com/es/tutorials/the-android-sdk-tutorial--cms-34623)


## Kotlin
😃

* ✔️ Advantages vs Java :[ Reference](https://kotlinlang.org/docs/comparison-to-java.html#what-kotlin-has-that-java-does-not)
* ✔️ Inline functions
* ✔️ Differents between lazy, latein :[ Reference](https://stackoverflow.com/questions/36623177/kotlin-property-initialization-using-by-lazy-vs-lateinit)
* ✔️ Extension functions :[ Reference](https://antonioleiva.com/extension-functions-kotlin/)
* ✔️ Kotlin kapt :[ Reference](https://mdapp.medium.com/annotation-processing-with-kapt-and-gradle-237793f2be57)
* ✔️ Data class :[ Reference](https://devexperto.com/data-classes-kotlin/)
* ✔️ Static class Kotlin :[ Reference](https://stackoverflow.com/questions/40352684/what-is-the-equivalent-of-java-static-methods-in-kotlin)
* ✔️ Singleton in Kotlin   :[ Reference](https:/devexperto.com/object-kotlin-singleton)

## Gradle
😅
```
-Gradle settings
-Build config
-Builtypes
-Signing configuration
-Android keystore
-Flavors

```

## Android_Studio 
🧑‍💻
```
-Profile tools
-Apk analyzer
-Database inspector

```

## UI 
🧑‍🎨
```
-Viewbindings vs databinding vs kotlin sintetics
-RecyclerView.Adapter.StateRestorationPolicy
-Recycler adapter why list adapter, Adapter viewholder,onbindviewholder,oncreateviewholder definitions
-Diff call utils
-UX patterns

```

## Best_Practices
💪
* ✔️ Design Patterns :[ Reference](https:/www.raywenderlich.com/18409174-common-design-patterns-and-app-architectures-for-android)
* ✔️ SOLID :[ Reference](https://profile.es/blog/principios-solid-desarrollo-software-calidad/)
* ✔️ Inversion Control vs dependency injection  :[ Reference](https://stackoverflow.com/questions/6550700/inversion-of-control-vs-dependency-injection)
* ✔️ HILT  vs Koin vs Dagger 2  :[ Reference](https://proandroiddev.com/how-dagger-hilt-and-koin-differ-under-the-hood-c3be1a2959d7?gi=584e22c8ecd2)
* ✔️ Ktlint  :[ Reference](https://github.com/pinterest/ktlint)
* ✔️ Memory leaks  :[ Reference](https://www.raywenderlich.com/4690472-memory-leaks-in-android)
* ✔️ Png to webp/ vector smaller apk 


## Arquitecture 
😎
* ✔️ MVVM  :[ Reference](https://devexperto.com/arquitecturas-android/)
* ✔️ MVVM vs MVC vs MVI :[ Reference](https://www.mobindustry.net/mvc-vs-mvp-vs-mvvm-vs-mvi-choosing-an-architecture-for-android-app/)
* ✔️ Clean Arquitecture  :[ Reference](https://stackoverflow.com/questions/58484680/what-is-difference-between-mvvm-with-clean-architecture-and-mvvm-without-clean-a)
* ✔️ SaveStateHandle advantages

## Network 
📱
```
✔️ Retrofit vs ktor vs volley
✔️ Converter gson vs moshi
✔️ Parcelable vs Serializable
✔️ Okhttp
✔️ Interceptors
✔️ Glide vs Picasso vs Koil
```

## Firebase 
🔧
```
✔️ Crashlitics
✔️ Push Notifications
✔️ Firebase test labs

```

## Test
✅
* ✔️ Fundamentals :[ Reference](https://developer.android.com/training/testing/fundamentals)
* ✔️ Robolectric :[ Reference](http://robolectric.org/)
* ✔️ Mockk  :[ Reference](https://mockk.io/)
* ✔️ Mock, stups, spies :[ Reference](https://stackoverflow.com/questions/24413184/difference-between-mock-stub-spy-in-spock-test-framework)
* ✔️ Screenshots test  :[ Reference]()
* ✔️ Expresso :[ Reference]()
* ✔️ Mockwebserver :[ Reference]()
* ✔️ Firebase remote config  A/B testing :[ Reference]()

## Proguard 
⚙️
```
✔️ Rules
✔️ Advantages

```

## CI_CD
💻
```
✔️ Bitrise vs Github actions vs Jenkins

```

## Crash
❌
* ✔️ Bugsnag vs Crashlitics:[ Reference](https://www.trustradius.com/compare-products/bugsnag-vs-firebase-crashlytics)

## MAD
👌
* ✔️ AndroidX:[ Reference](https://developer.android.com/jetpack/androidx)
* ✔️ Jetpack :[ Reference](https://developer.android.com/jetpack)
* ✔️ Arquitecture components :[ Reference](https://developer.android.com/topic/libraries/architecture)
* ✔️ Flow – Livedata :[ Reference](https://devexperto.com/stateflow-kotlin/)
* ✔️ Coroutines Advantages coroutines vs rx java, rx android :[ Reference]()
* ✔️ Room :[ Reference]()
* ✔️ Pagin :[ Reference]()



<!-- CONTACT -->
## Contact

Carlos Adan - [@carlyad4m](https://twitter.com/carlyad4m)



