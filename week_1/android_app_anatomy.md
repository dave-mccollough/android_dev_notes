# Anatomy of an Android App

Android apps are made up of 4 major components

## Activities

- Represents a single screen
- Window or frame in Kotlin
- Allows you to place all your UI components on one screen
- Each activity is independent of the others

## Services

- Services run in the background
- Updates data sources and activities with the latest changes

## Broadcast Receivers

- Responds to applications or messages in real-time
  - Notification on low battery power

## Content Providors

- Shares data betwen one or more applications

## Android Manifest

- XML file that specifies each component and how they interact with each other
- Defines major components of the application
