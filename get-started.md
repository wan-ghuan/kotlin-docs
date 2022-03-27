# Get started with Kotlin

[Kotlin](https://kotlinlang.org/) is a modern but already mature programming language aimed to make developers happier. It’s concise, safe, interoperable with Java and other languages, and provides many ways to reuse code between multiple platforms for productive programming.

Pick it up to start building powerful applications!



## Learn Kotlin fundamentals

- If you're already familiar with one or more programming languages and want to learn Kotlin, start with these [Kotlin learning materials](https://kotlinlang.org/docs/learning-materials-overview.html).
- If Kotlin is your first programming language, we recommend starting with the [Atomic Kotlin book](https://www.atomickotlin.com/atomickotlin/) or signing up for the free [Kotlin Basics track](https://hyperskill.org/tracks/18) on JetBrains Academy.



## Create your powerful application with Kotlin﻿



### Backend app

Here is how you can take the first steps in developing Kotlin server-side applications.

1. **Install the [latest version of IntelliJ IDEA](https://www.jetbrains.com/idea/download/index.html).**

2. **Create your first backend application:**

   - To start from scratch, [create a basic JVM application with the IntelliJ IDEA project wizard](https://kotlinlang.org/docs/jvm-get-started.html).
   - If you prefer more robust examples, choose one of the frameworks below and create a project:

   | Spring                                                       | Ktor                                                         |
   | ------------------------------------------------------------ | ------------------------------------------------------------ |
   | A mature family of frameworks with an established ecosystem that is used by millions of developers worldwide. [Create a RESTful web service with Spring Boot](https://kotlinlang.org/docs/jvm-spring-boot-restful.html).[Build web applications with Spring Boot and Kotlin](https://spring.io/guides/tutorials/spring-boot-kotlin/).[Use Spring Boot with Kotlin and RSocket](https://spring.io/guides/tutorials/spring-webflux-kotlin-rsocket/). | A lightweight framework for those who value freedom in making architectural decisions.[Create HTTP APIs with Ktor](https://ktor.io/docs/creating-http-apis.html).[Create a WebSocket chat with Ktor](https://ktor.io/docs/creating-web-socket-chat.html).[Create an interactive website with Ktor](https://ktor.io/docs/creating-interactive-website.html).[Publish server-side Kotlin applications: Ktor on Heroku](https://ktor.io/docs/heroku.html). |

3. **Use Kotlin and third-party libraries in your application**. Learn more about [adding library and tool dependencies to your project](https://kotlinlang.org/docs/gradle.html#configuring-dependencies).

   - The [Kotlin standard library](https://kotlinlang.org/api/latest/jvm/stdlib/) offers a lot of useful things such as [collections](https://kotlinlang.org/docs/collections-overview.html) or [coroutines](https://kotlinlang.org/docs/coroutines-guide.html).
   - Take a look at the following [third-party frameworks, libs and tools for Kotlin](https://blog.jetbrains.com/kotlin/2020/11/server-side-development-with-kotlin-frameworks-and-libraries/).

4. **Learn more about Kotlin for server-side:**

   - [How to write your first unit test](https://kotlinlang.org/docs/jvm-test-using-junit.html).
   - [How to mix Kotlin and Java code in your application](https://kotlinlang.org/docs/mixing-java-kotlin-intellij.html).

5. **Join the Kotlin server-side community:**

   - ![Slack](https://kotlinlang.org/docs/images/slack.svg) Slack: [get an invite](https://surveys.jetbrains.com/s3/kotlin-slack-sign-up) and join the [#getting-started](https://kotlinlang.slack.com/archives/C0B8MA7FA), [#server](https://kotlinlang.slack.com/archives/C0B8RC352), [#spring](https://kotlinlang.slack.com/archives/C0B8ZTWE4), or [#ktor](https://kotlinlang.slack.com/archives/C0A974TJ9) channels.
   - ![StackOverflow](https://kotlinlang.org/docs/images/stackoverflow.svg) StackOverflow: subscribe to the [“kotlin”](https://stackoverflow.com/questions/tagged/kotlin), ["spring-kotlin"](https://stackoverflow.com/questions/tagged/spring-kotlin), or ["ktor"](https://stackoverflow.com/questions/tagged/ktor) tags.

6. **Follow Kotlin** on ![Twitter](https://kotlinlang.org/docs/images/twitter.svg) [Twitter](https://twitter.com/kotlin), ![Reddit](https://kotlinlang.org/docs/images/reddit.svg) [Reddit](https://www.reddit.com/r/Kotlin/), and ![YouTube](https://kotlinlang.org/docs/images/youtube.svg) [Youtube](https://www.youtube.com/channel/UCP7uiEZIqci43m22KDl0sNw), and don't miss any important ecosystem updates.

If you've encountered any difficulties or problems, report an issue to our [issue tracker](https://youtrack.jetbrains.com/issues/KT).

### Cross-platform mobile app

Here you'll learn how to develop and improve your cross-platform mobile application using [Kotlin Multiplatform Mobile](https://kotlinlang.org/lp/mobile/).

1. **[Set up your environment for cross-platform mobile development](https://kotlinlang.org/docs/multiplatform-mobile-setup.html).**

2. **Create your first application for iOS and Android:**

   - To start from scratch, [create a basic cross-platform mobile application with the project wizard](https://kotlinlang.org/docs/multiplatform-mobile-create-first-app.html).
   - If you have an existing Android application and want to make it cross-platform, complete the [Make your Android application work on iOS](https://kotlinlang.org/docs/multiplatform-mobile-integrate-in-existing-app.html) tutorial.
   - If you prefer real-life examples, clone and play with an existing project, for example the networking and data storage project from the [hands-on tutorial](https://play.kotlinlang.org/hands-on/Networking and Data Storage with Kotlin Multiplatfrom Mobile/01_Introduction) or any [sample project](https://kotlinlang.org/docs/multiplatform-mobile-samples.html).

3. **Use a wide set of multiplatform libraries** to implement the required business logic only once in the shared module. Learn more about [adding dependencies](https://kotlinlang.org/docs/multiplatform-add-dependencies.html).

   | Library       | Details                                                      |
   | ------------- | ------------------------------------------------------------ |
   | Ktor          | [Docs](https://ktor.io/docs/client.html).                    |
   | Serialization | [Docs](https://kotlinlang.org/docs/serialization.html) and [sample](https://play.kotlinlang.org/hands-on/Networking and Data Storage with Kotlin Multiplatfrom Mobile/04_Creating_a_data_model). |
   | Coroutines    | [Docs](https://kotlinlang.org/docs/multiplatform-mobile-concurrency-overview.html) and [sample](https://kotlinlang.org/docs/multiplatform-mobile-concurrency-and-coroutines.html). |
   | DateTime      | [Docs](https://github.com/Kotlin/kotlinx-datetime#readme).   |
   | SQLDelight    | Third-party library. [Docs](https://cashapp.github.io/sqldelight/). |

   > ### 
   >
   > 
   >
   > You can also find a multiplatform library in the [community-driven list](https://libs.kmp.icerock.dev/).

4. **Learn more about Kotlin Multiplatform Mobile:**

   - Learn more about [Kotlin Multiplatform](https://kotlinlang.org/docs/multiplatform-get-started.html).
   - Look through [samples on GitHub](https://kotlinlang.org/docs/multiplatform-mobile-samples.html).
   - [Create and publish a multiplatform library](https://kotlinlang.org/docs/multiplatform-create-lib.html).
   - Learn how Kotlin Multiplatform is used at [Netflix](https://netflixtechblog.com/netflix-android-and-ios-studio-apps-kotlin-multiplatform-d6d4d8d25d23), [VMware](https://kotlinlang.org/lp/mobile/case-studies/vmware/), [Yandex](https://kotlinlang.org/lp/mobile/case-studies/yandex/), and [many other companies](https://kotlinlang.org/lp/mobile/case-studies/).

5. **Join the Kotlin Multiplatform community:**

   - ![Slack](https://kotlinlang.org/docs/images/slack.svg) Slack: [get an invite](https://surveys.jetbrains.com/s3/kotlin-slack-sign-up) and join the [#getting-started](https://kotlinlang.slack.com/archives/C0B8MA7FA) and [#multiplatform](https://kotlinlang.slack.com/archives/C3PQML5NU) channels.
   - ![StackOverflow](https://kotlinlang.org/docs/images/stackoverflow.svg) StackOverflow: Subscribe to the [“kotlin-multiplatform” tag](https://stackoverflow.com/questions/tagged/kotlin-multiplatform).

6. **Follow Kotlin** on ![Twitter](https://kotlinlang.org/docs/images/twitter.svg) [Twitter](https://twitter.com/kotlin), ![Reddit](https://kotlinlang.org/docs/images/reddit.svg) [Reddit](https://www.reddit.com/r/Kotlin/), and ![YouTube](https://kotlinlang.org/docs/images/youtube.svg) [Youtube](https://www.youtube.com/channel/UCP7uiEZIqci43m22KDl0sNw), and don't miss any important ecosystem updates.

If you've encountered any difficulties or problems, report an issue to our [issue tracker](https://youtrack.jetbrains.com/issues/KT).

### Frontend web app

Kotlin provides an ability to transpile your Kotlin code, the Kotlin standard library, and any compatible dependencies to JavaScript.

Here you'll learn how to develop and improve your frontend web application using [Kotlin/JS](https://kotlinlang.org/docs/js-overview.html).

1. **Install the [latest version of IntelliJ IDEA](https://www.jetbrains.com/idea/download/index.html).**

2. **Create your first frontend web application:**

   - To start from scratch, [create a basic browser application with the IntelliJ IDEA project wizard](https://kotlinlang.org/docs/js-project-setup.html).
   - If you prefer more robust examples, complete the [Building Web Applications with React and Kotlin/JS](https://play.kotlinlang.org/hands-on/Building Web Applications with React and Kotlin JS/01_Introduction) hands-on tutorial. It includes a sample project that can serve as a good starting point for your own projects, and contains useful snippets and templates.
   - Check out the list of [Kotlin/JS samples](https://kotlinlang.org/docs/js-samples.html) for more ideas on how to use Kotlin/JS.

3. **Use libraries in your application.** Learn more about [adding dependencies](https://kotlinlang.org/docs/js-project-setup.html#dependencies).

   | Library                                                      | Details                                                      |
   | ------------------------------------------------------------ | ------------------------------------------------------------ |
   | [stdlib](https://kotlinlang.org/api/latest/jvm/stdlib/)      | The Kotlin standard library included in all projects by default. |
   | [kotlinx.browser](https://kotlinlang.org/docs/browser-api-dom.html) | The Kotlin library for accessing browser-specific functionality, including typical top-level objects such as document and window. |
   | [kotlinx.html](https://kotlinlang.org/docs/typesafe-html-dsl.html) | The Kotlin library for generating DOM elements using statically-typed HTML builders. |
   | [Ktor](https://ktor.io/)                                     | The Kotlin multiplatform library for networking.             |
   | [KVision](https://kvision.io/)                               | A third-party object-oriented web framework for Kotlin/JS.   |
   | [fritz2](https://www.fritz2.dev/)                            | A third-party lightweight, high-performance, independent library for building reactive web apps in Kotlin that are heavily dependent on coroutines and flows. |
   | [Doodle](https://nacular.github.io/doodle/)                  | A third-party vector-based UI framework that uses browser's capabilities to draw user interfaces. |
   | Compose for Web, a part of [Compose Multiplatform](https://www.jetbrains.com/lp/compose-mpp/) | The JetBrains framework that brings [Google's Jetpack Compose UI toolkit](https://developer.android.com/jetpack/compose) to the browser. |
   | [kotlin-wrappers](https://github.com/JetBrains/kotlin-wrappers) | Provide convenient abstractions and deep integrations for one of the most popular JavaScript frameworks. Kotlin wrappers also provide support for a number of adjacent technologies like `react-redux`, `react-router`, or `styled-components`. |

4. **Learn more about Kotlin for frontend web development:**

   - The [new Kotlin/JS IR compiler](https://kotlinlang.org/docs/js-ir-compiler.html) (currently with [Beta](https://kotlinlang.org/docs/components-stability.html) stability).
   - [Using dependencies from npm](https://kotlinlang.org/docs/using-packages-from-npm.html).
   - [Using Kotlin code from JavaScript](https://kotlinlang.org/docs/js-to-kotlin-interop.html).

5. **Join the Kotlin frontend web community:**

   - ![Slack](https://kotlinlang.org/docs/images/slack.svg) Slack: [get an invite](https://surveys.jetbrains.com/s3/kotlin-slack-sign-up) and join the [#getting-started](https://kotlinlang.slack.com/archives/C0B8MA7FA) and [#javascript](https://kotlinlang.slack.com/archives/C0B8L3U69) channels.
   - ![StackOverflow](https://kotlinlang.org/docs/images/stackoverflow.svg) StackOverflow: subscribe to the [“kotlin-js” tag](https://stackoverflow.com/questions/tagged/kotlin-js).

6. **Follow Kotlin** on ![Twitter](https://kotlinlang.org/docs/images/twitter.svg) [Twitter](https://twitter.com/kotlin), ![Reddit](https://kotlinlang.org/docs/images/reddit.svg) [Reddit](https://www.reddit.com/r/Kotlin/), and ![YouTube](https://kotlinlang.org/docs/images/youtube.svg) [Youtube](https://www.youtube.com/channel/UCP7uiEZIqci43m22KDl0sNw), and don't miss any important ecosystem updates.

If you've encountered any difficulties or problems, report an issue to our [issue tracker](https://youtrack.jetbrains.com/issues/KT).

### Android app

- If you want to start using Kotlin for Android development, read [Google’s recommendation for getting started with Kotlin on Android](https://developer.android.com/kotlin/get-started).
- If you're new to Android and want to learn to create applications with Kotlin, check out [this Udacity course](https://www.udacity.com/course/developing-android-apps-with-kotlin--ud9012).

Follow Kotlin on ![Twitter](https://kotlinlang.org/docs/images/twitter.svg) [Twitter](https://twitter.com/kotlin), ![Reddit](https://kotlinlang.org/docs/images/reddit.svg) [Reddit](https://www.reddit.com/r/Kotlin/), and ![YouTube](https://kotlinlang.org/docs/images/youtube.svg) [Youtube](https://www.youtube.com/channel/UCP7uiEZIqci43m22KDl0sNw), and don't miss any important ecosystem updates.

### Multiplatform library

Support for multiplatform programming is one of Kotlin’s key benefits. It reduces time spent writing and maintaining the same code for different platforms while retaining the flexibility and benefits of native programming.

Here you'll learn how to develop and publish a multiplatform library:

1. **Install the [latest version of IntelliJ IDEA](https://www.jetbrains.com/idea/download/index.html).**

2. **Create a multiplaform library:**

   - To start from scratch, [create a basic project](https://kotlinlang.org/docs/multiplatform-create-lib.html).
   - If you prefer more robust examples, complete the [Create and publish a multiplatform library](https://kotlinlang.org/docs/multiplatform-library.html) tutorial. It shows how to create a multiplatform library for JVM, JS, and Native platforms, test it and publish to a local Maven repository.
   - Build a full stack web application using [this hands-on](https://play.kotlinlang.org/hands-on/Full Stack Web App with Kotlin Multiplatform/01_Introduction).

3. **Use libraries in your application.** Learn more about [adding dependencies on libraries](https://kotlinlang.org/docs/multiplatform-add-dependencies.html).

   | Library       | Details                                                      |
   | ------------- | ------------------------------------------------------------ |
   | Ktor          | [Docs](https://ktor.io/docs/) and [sample](https://play.kotlinlang.org/hands-on/Full Stack Web App with Kotlin Multiplatform/03_A_Simple_API_Server). |
   | Serialization | [Docs](https://kotlinlang.org/docs/serialization.html) and [sample](https://play.kotlinlang.org/hands-on/Full Stack Web App with Kotlin Multiplatform/01_Introduction). |
   | Coroutines    | [Docs](https://kotlinlang.org/docs/coroutines-overview.html). |
   | DateTime      | [Docs](https://github.com/Kotlin/kotlinx-datetime#readme).   |

   > ### 
   >
   > 
   >
   > You can also find a multiplatform library in the [community-driven list](https://libs.kmp.icerock.dev/).

4. **Learn more about Kotlin Multiplatform programming:**

   - [Introduction to Kotlin Multiplatform](https://kotlinlang.org/docs/multiplatform-get-started.html).
   - [Kotlin Multiplatform supported platforms](https://kotlinlang.org/docs/multiplatform-dsl-reference.html#targets).
   - [Kotlin Multiplatform programming benefits](https://kotlinlang.org/docs/multiplatform.html).

5. **Join the Kotlin Multiplatform community:**

   - ![Slack](https://kotlinlang.org/docs/images/slack.svg) Slack: [get an invite](https://surveys.jetbrains.com/s3/kotlin-slack-sign-up) and join the [#getting-started](https://kotlinlang.slack.com/archives/C0B8MA7FA) and [#multiplatform](https://kotlinlang.slack.com/archives/C3PQML5NU) channels.
   - ![StackOverflow](https://kotlinlang.org/docs/images/stackoverflow.svg) StackOverflow: Subscribe to the [“kotlin-multiplatform” tag](https://stackoverflow.com/questions/tagged/kotlin-multiplatform).

6. **Follow Kotlin** on ![Twitter](https://kotlinlang.org/docs/images/twitter.svg) [Twitter](https://twitter.com/kotlin), ![Reddit](https://kotlinlang.org/docs/images/reddit.svg) [Reddit](https://www.reddit.com/r/Kotlin/), and ![YouTube](https://kotlinlang.org/docs/images/youtube.svg) [Youtube](https://www.youtube.com/channel/UCP7uiEZIqci43m22KDl0sNw), and don't miss any important ecosystem updates.

If you've encountered any difficulties or problems, report an issue to our [issue tracker](https://youtrack.jetbrains.com/issues/KT).



## Is anything missing?﻿

If anything is missing or seems confusing on this page, please [share your feedback](https://surveys.hotjar.com/d82e82b0-00d9-44a7-b793-0611bf6189df).

