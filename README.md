# CMPE277 ORC App - Cognitive Services and The optical character recognition (OCR) Analytics

## Assignmet Learning Objective
Purpose of the assignment is to integrate Machine Learning and AI as part of the Android Application.

The CMPE277 ORC App is a cutting-edge mobile application designed to leverage optical character recognition (OCR) technology to convert images into editable and searchable data. Utilizing Google's ML Kit for OCR, the app offers a seamless and efficient way to extract text from images captured using the device's camera. It's an innovative tool for digitizing printed text, enhancing productivity, and accessibility for users.

## Authors
- [@Harshil-V](https://github.com/Harshil-V/)
- [@Chandrasekar Vuppalapati](chandrasekar.vuppalapati@sjsu.edu)

## Screenshots
TODO

## Features

- **Image Capture**: Users can capture images using the device's camera, facilitated by intuitive handling of camera permissions.
- **Text Recognition**: The app accurately recognizes and extracts text from captured images using Google ML Kit's OCR technology.
- **User-Friendly Interface**: With a simple and responsive design, users can easily navigate the app and complete text recognition tasks.
- **Progress Indication**: A progress dialog keeps users informed about the status of the text recognition process, ensuring a smooth experience.

## How It Works

1. **Permissions**: On first use, the app requests necessary permissions for camera access, crucial for capturing images for OCR processing.
2. **Capturing Images**: Users can capture images using the camera. This functionality allows for digitizing handwritten notes, printed documents, and more into editable text.
3. **Text Recognition**: After capturing an image, the app employs Google ML Kit's OCR technology for text recognition. The technology's advanced algorithms ensure high accuracy and efficiency.
4. **Displaying Recognized Text**: The app displays the recognized text, allowing users to review and use the digitized information.

## Using Google ML Kit for OCR

At the heart of the CMPE277 ORC App is Google ML Kit's OCR technology, which enables the app to offer rapid and precise text recognition. Here's how it works:

- **Image Preparation**: Upon capturing an image, it is converted into an `InputImage` object, a required format for ML Kit processing.
- **Text Recognition Process**: The `TextRecognizer` instance processes the `InputImage` asynchronously, ensuring the app remains responsive.
- **Result Handling**: Successful recognition returns a `Text` object, containing the extracted text along with additional information like text blocks and their positions.
- **Error Handling**: If recognition fails, users are notified through a toast message, maintaining a good user experience under all circumstances.

## Conclusion

The CMPE277 ORC App demonstrates the practical application of OCR technology in mobile development, offering an efficient tool for text digitization directly from the camera. Integrating Google ML Kit's robust OCR capabilities ensures the app's high accuracy and performance, making it indispensable for anyone in need of quick and reliable text recognition.
