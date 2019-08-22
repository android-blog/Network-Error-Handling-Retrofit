# Network-Error-Handling-Retrofit
Centralized Network Error Handling Retrofit

Welcome guys, In this post I’ll tell you how manage network error handling in single place in Android. Before moving ahead first we need to understand, Why we need to it a Centralised?.

Why — In general you mostly put a network check before each doing api call. Suppose In app you are calling different APIs. each api call you check is internet available or not. It’s not a good coding practice and unnecessary increase bipolerate code.
Now i will tell you how manage Network Error Handling Retrofit in Single place
## Steps
- Create RxBus for listing ConnectionListener
- Create ConnectionInterceptor
- Add this ConnectionInterceptor on Retrofit
- Listen ConnectionListener inside the activity.

Read our full article on https://androidwave.com/centralized-network-error-handling-retrofit/

