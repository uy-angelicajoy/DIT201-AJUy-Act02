## What did you observe about the app lifecycle when switching between screens or minimizing the app?
- I noticed that when I switch screens in Android Studio, the first activity pauses and ends while the new one is created and continued.  Unless the system requires memory, 
  the activity pauses and stops when the app is minimized, but it is not destroyed.  Reopening the application causes it to restart and resume, enabling seamless operation. 
  This demonstrates how Android effectively controls operations without sacrificing user experience.

## What you learn about activity management in Android?
- It handles activity management through a clearly defined lifecycle that regulates the creation, pause, stop, and destruction of activities.
  Hidden activities can sometimes stay in memory and be restarted when necessary, rather than being completely erased.
  This improves user experiences, increases app efficiency, and enables the system to efficiently manage memory when several apps are open at once.
