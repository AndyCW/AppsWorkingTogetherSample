# Ignite2016-ExtensibilitySample
This repo contains the sample shown in the Apps working together session at Ignite 2016. It is an updated version of the sample originally shown during the App Extensibility Session during Build 2016. This new sample has been updated to target the 14393 SDK.

After cloning the sample, open the solution in Visual Studio. Make sure you're on the Windows 10 Anniversary Update (Build 14393) and you have the associated SDK. This sample is a complete App Extension Host and also shows cropping via LaunchURIForResultsAsync, and includes the Cortana App Service. 

To use actual app extensions, open the following projects in the Extensions subfolder and deploy them from Visual Studio. They should automatically appear in the Extensions tab of the main application.

Grayscale:
/Extensions/GrayscaleExtension

Invert: 
/Extensions/InvertImageExtension

Rotate:
/Extensions/RotateExtension



