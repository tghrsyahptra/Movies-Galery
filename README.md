<h1 align="center">Movie Gallery</h1>
<p align="center">  
 Movie Gallery demonstrates modern Android development with Hilt, RxJava3, Jetpack (Room, ViewModel, LiveData, etc.), and Material Design based on MVVM clean architecture.
</p>

<p align="center">
<img src="/previews/screenshots.png"/>
</p>

<p align="center">
<img src="/previews/preview.gif" align="right" width="320" />
</p>

## Tech stack & Open-source libraries
- Minimum SDK level 21
- [Kotlin](https://kotlinlang.org/)
- <b>Lifecycle</b>: Observe Android lifecycles and handle UI states upon the lifecycle changes.
- <b>ViewModel</b>: Manages UI-related data holder and lifecycle aware. Allows data to survive configuration changes such as screen rotations.
- <b>DataBinding</b>: Binds UI components in your layouts to data sources in your app using a declarative format rather than programmatically.
- <b>Room</b>: Constructs Database by providing an abstraction layer over SQLite to allow fluent database access.
- [Hilt](https://dagger.dev/hilt/): for dependency injection.
- Navigation Component.
- [Gson](https://github.com/google/gson) is a serialization/deserialization library to convert objects into JSON and back.
- <b>DataStore</b>: Jetpack DataStore is a data storage solution that allows you to store key-value pairs or typed objects with [protocol buffers](https://developers.google.com/protocol-buffers)
- [Retrofit2](https://github.com/square/retrofit): Construct the REST APIs and paging network data.
- [Glide](https://github.com/bumptech/glide): Loading images from network/resource.
- [Rxjava3](https://github.com/ReactiveX/RxJava): A library for composing asynchronous and event-based programs by using observable sequences.
- <b>Junit</b>(Unit Test) : A simple framework to write repeatable tests.
- <b>Mockito</b>(Unit Test) : A mocking framework that lets you write beautiful tests with a clean & simple API.

<br/>

## Architecture
This app uses MVVM clean Architecture.
<p align="center">
<img src="/previews/architecture.png"/>
</p>

<br/>

## Testing
Local Tests are done using `Junit` & `Mockito`.

<br/>

## How To Run The App
Add your [TMDB](https://www.themoviedb.org/) API key in the `local.properties` file:
