# PitchPerfect
An iOS app that allows users to record their voice and will then modulate the recorded audio to sound like a Chipmunk or Darth Vader. It will also let the user speed up or slow down the rate of playback, and experience fun echo and reverb effects.

This app builds to showcase the use of swift and implement *AVFoundation* that uses a phone's microphone to record audio and then apply audio effects on the recording.

## Implementations
The app has two view controller scenes:

* **RecordSoundsViewController** - consists of a record button with a microphone image. Tapping this microphone button starts an audio recording session and present a stop button. When the stop button is clicked, the app completes the recording and then show the PlaySound controller.

* **PlaySoundsViewController** - contains six buttons to play the recorded sound file with different effects and a button to stop the playback.

The application uses code from *AVFoundation* to record sounds from the microphone *(AVAudioRecorder)* and play recorded audio with effects *(AVAudioPlayer, AVAudioEngine)*.

## Screenshots
| Home  | Recording Sound | Playing Sound |
| ------------- | ------------- | ------------- |
| ![alt text](https://github.com/ariashary/PitchPerfect/blob/master/screenshots/home.png)  | ![alt text](https://github.com/ariashary/PitchPerfect/blob/master/screenshots/recording.png)  | ![alt text](https://github.com/ariashary/PitchPerfect/blob/master/screenshots/play-sound.png)  |

## Source
The Pitch Perfect app is result of [*Intro to iOS App Development with Swift*](https://www.udacity.com/course/intro-to-ios-app-development-with-swift--ud585) lesson of Udacity's [*Become an iOS Developer*](https://www.udacity.com/course/ios-developer-nanodegree--nd003) Nanodegree.
