Music Player – Android Service App

This is a simple Android application demonstrating how to use background services in Android. The app allows the user to start and stop a music service that plays the device’s default ringtone in a continuous loop. It displays a minimal UI with two buttons and shows how to work with Service, Intent, and MediaPlayer to handle background audio tasks.

Features

🎵 Start Background Music
Plays the system’s default ringtone using a foreground Service.

⏹️ Stop Background Music
Immediately stops the playing audio by stopping the service.

🔁 Looped Playback
The music loops automatically until the user stops it.

🧩 Clean and Simple UI
Includes a title and two buttons for easy interaction.

⚙️ Demonstrates Core Android Concepts

Services

Intents

MediaPlayer

Activity → Service communication


**How It Works:**

The user opens the app and sees two buttons: Start Service and Stop Service.

Clicking Start Service sends an intent to MyService.

MyService uses a MediaPlayer instance to play the system ringtone in a loop.

Clicking Stop Service sends an intent that stops the running service.

When the service stops, the MediaPlayer is released and audio ends.
