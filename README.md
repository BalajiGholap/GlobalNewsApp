# GlobalNewsApp
Project - NewsApp
Objective:
Created a NewsApp Android Application with the following:
MVVM architecture
Kotlin
OkHttp and Retrofit for networking
Coroutines, LiveData
Jetpack Compose
Best practices
Used News API:
Gone through the News API website: https://newsapi.org
API docs:
https://newsapi.org/docs
https://newsapi.org/docs/authentication
https://newsapi.org/docs/endpoints
https://newsapi.org/docs/endpoints/everything
https://newsapi.org/docs/endpoints/top-headlines
https://newsapi.org/docs/endpoints/sources
https://newsapi.org/docs/errors
Gone through all the links in detail to know everything about the API.

Created API Key which is required for your project.

Feature implemented and app screen navigation flow:
Main Activity screen: Buttons to access these 5 screens

1. Top Headlines Screen: Show all the top headlines in list, By Clicking on a headline items then it opens the link in the custom tabs Intent browser.
API:https://newsapi.org/v2/top-headlines?country=us&apiKey=9f6482a58480437687 4b848980b7a044

2.News Source Screen: Shows all the available News Sources in List, And By clicking on a news source items then it opens the News List Screen with the list of news corresponding to that source.
API: https://newsapi.org/v2/top-headlines/sources?apiKey=9f6482a584804376874b84 8980b7a044

3.Countries Screen: Shows the list of countries, It's static data stored in app

4.Languages Screen: Shows the list of languages  - static data

5.Search Button: nothing to show - It's work under progress.

