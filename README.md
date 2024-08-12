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
Tech Stack & Open-source Libraries
Minimum SDK Level: 21
Kotlin: Kotlin is the primary programming language used in this project.
Lifecycle: Observes Android lifecycles and handles UI states during lifecycle changes.
ViewModel: Manages UI-related data, is lifecycle-aware, and ensures data survives configuration changes like screen rotations.
DataBinding: Binds UI components in your layouts to data sources in your app using a declarative format rather than programmatically.
Room: Constructs a database by providing an abstraction layer over SQLite for fluent database access.
Hilt: Hilt is used for dependency injection.
Navigation Component: Manages navigation between fragments and activities.
Gson: Gson is a serialization/deserialization library used to convert objects into JSON and back.
DataStore: Jetpack DataStore is a data storage solution that allows you to store key-value pairs or typed objects using protocol buffers.
Retrofit2: Retrofit2 is used to construct REST APIs and manage paging network data.
Glide: Glide is used for loading images from the network or local resources.
RxJava3: RxJava3 is a library for composing asynchronous and event-based programs using observable sequences.
Junit (Unit Test): A simple framework for writing repeatable tests.
Mockito (Unit Test): A mocking framework that enables you to write clean and simple tests with an elegant API.

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
