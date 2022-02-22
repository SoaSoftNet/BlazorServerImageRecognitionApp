# Blazor Server Image Recognition App

Simple Blazor Server app which uses image recognition to identify and extract text printed in an image file uploaded by the user.  The app utilises the recognise printed text in image function in the Azure Computer Vision Cognitive service to identify and extract printed text from an uploaded image file

* GUI frontend project developed using Blazor Server/.Net 6
* Image printed text recognition engine is a class library project developed using .Net 6
   * Communicates with the Azure Computer Vision Cognitive Service 7

## Upload image file to analyse

![](BlazorServerImageRecognitionApp/wwwroot/Images/Demo1.png)

## Image file displayed and printed text from image displayed in text area

![](BlazorServerImageRecognitionApp/wwwroot/Images/Demo2.png)
