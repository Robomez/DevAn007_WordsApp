# Words App

При нажатии кнопки с буквой отображаются слова из ресурса с масивом строк. По пять случайных слов, начинающихся с этой буквы, в алфавитном порядке.

Макет с кнопками букв - recyclerView линейный или решётка по нажатию на кнопку.

При нажатии слова в фрагменте со словами ищет значение слова в гугле.

Navigation component, view binding, recyclerView с изменяемым макетом, fragments, uri parse.

<img src="Screenshot_20230609_001850.png" width=80%>

This folder contains the source code for the Words app codelab.


# Introduction
Words app allows you to select a letter and use Intents to navigate to an Activity that
presents a number of words starting with that letter. Each word can be looked up via a web search.

Words app contains a scrollable list of 26 letters A to Z in a RecyclerView. The orientation
of the RecyclerView can be changed between a vertical list or a grid of items.

The app demonstrates the use of Intents in two ways:
* to navigate inside an app by specifying an explicit destination, and,
* allowing Android to service the Intent using the apps and resources present on the device.

# Pre-requisites
* Experience with Kotlin syntax.
* Able to create an Activity.
* Able to create a RecyclerView and supply it with data.

# Getting Started
1. Install Android Studio, if you don't already have it.
2. Download the sample.
3. Import the sample into Android Studio.
4. Build and run the sample.
