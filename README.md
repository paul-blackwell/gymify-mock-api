# gymify-mock-api
This is a mock API for the gymify app (CI360-CI560 - Mobile Application Development).

As the Gymify app has a hybrid file storage system, it relies on storing files locally on 
the device for custom workouts and user progress however it also needs to a base set of workouts 
for all users. This base set of workouts will not be stored on the user’s device but will instead 
come from an API. This is because if this base set of workouts changes the user would have to update 
the app. We don’t want to do this so hence the use of this API. As the Gymify app is part of a university 
module (CI360-CI560 - Mobile Application Development) the primary focuses on the APP not backend services, 
this is why this code is a mock API, as we just need to get data from it to show how the APP consumes it.
