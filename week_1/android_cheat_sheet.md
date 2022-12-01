# Android App Cheat Sheet

## Top Level Component

The ability to connect to the internet, make calls, take pictures and much more is made possible in Android apps with the help of four top-level component classes:

- BroadcastReceiver
- ContentProvider
- Service and Activity
  These are all accessible in the Android software development kit (SDK).

## Activity Components

Activities present the content users can interact with on the screen. These are the only components that deliver interactive content to the user. An Activity represents something an application can do. Although an application can provide more than one Activity, many developers are following a Single-Activity architecture pattern when creating their apps. This implies that only one Activity or a relatively small number of Activities are used for an entire application.

## Android Views

In Android, Views occupy a rectangular area on the screen and are responsible for drawing and event handling. They can display images, text and more. A combination of all of these Views forms a design interface.

## Android Layout Files

In Android, each layout is represented by an XML file. These plain text files serve as blueprints for the interface that your application presents to the user. In addition to the XML approach, there are other ways to create a user interface. For example, interfaces can be created with Android Views entirely in code using Kotlin or Java. Also, Google has created a completely new way of creating Android user interfaces - Jetpack Compose. With this library, interfaces are created entirely in Kotlin code, without XML.

## Project Files

Android Project Files belong to one of three main categories: configuration, code and resource. Configuration files define the project structure, code files provide the logic and resource files provide essentially everything else.
