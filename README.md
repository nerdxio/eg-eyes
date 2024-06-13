# Egyptian Currency Image Classifier App

This project is a Kotlin-based application that uses the MediaPipe framework for image classification. It is designed to classify images from a video file and return the results along with the inference time.

## Features

- Classify images from a video file.
- Calculate the inference time for each frame.
- Classify images from the gallery.

## Technologies Used

- Kotlin
- Java
- Gradle
- Python
- MediaPipe

## How to Run

1. Clone the repository.
2. Open the project in Android Studio Iguana | 2023.2.1 Patch 1 or any other IDE that supports Kotlin.
3. Build and run the project.

## Code Structure

The main class `ImageClassifierHelper.kt` contains the logic for image classification. It uses the MediaPipe framework to classify images from a video file. The results of the classification and the inference time are wrapped in a `ResultBundle` object and returned to the caller.

## Future Work

This project is a starting point for more complex image classification tasks. Future work could include improving the classification accuracy, adding support for different video formats, and optimizing the inference time.