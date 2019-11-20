### Project Overview

This project aims is usage of Android Architecture Components  with clean architecture. 


##### Project Description

First of all, I would like to show how I made the packages structure of the project For achieving The separation of concerns

- Presentation layer
will include normal Activities , Fragments and ViewModels which will only handle rendering views and will follow MVVM pattern.

- Domain layer
With the Use Cases that will include all business logic and interact between Data and Presentation layer by means of interface and interactors. The objective is to make the domain layer independent of anything, so the business logic can be tested without any dependency to external components.

- Data layer
With the Repositories.

##### Libraries
- AndroidX Support Library
- AndroidX Architecture Components( ViewModels, LiveData)
- RxJava2
- Dagger2
- Retrofit

## Note
** Few file that are not using this project so please ignore all unused file**
