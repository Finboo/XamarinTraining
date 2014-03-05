XamarinTraining
===============

xamarin android training and samples

Compiling the Google Play Services client library

To compile the Google Play Client Services library using Ant, follow these steps:

Use the Android SDK Manager to install Google Play Services.
Copy the directory located at extras/google/google_play_services/libproject/google-play-services_lib into the same directory as this README.
Build the project with ant like so:

cd google-play-services_lib
android update project -p . 1
ant debug
