# IntentService

An intent service is designed to run tasks in the background and is well suited to longer running tasks. 
Unlike AsyncTask or AsyncTaskLoader, an intent service is completely detached from the user interface. 
It runs in its own thread and doesn't have access to the main thread. It isn't contained within an activity, 
and it can't call the activity's methods, but it can communicate back to the app's visual tier using broadcast 
messages, and because it's using broadcast messages, it can send information to any component in the application, 
not just a single activity.
