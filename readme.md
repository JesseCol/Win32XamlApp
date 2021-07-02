# Win32 Xaml App Samples
These samples demonstrate basic Win32 use of Xaml using DesktopWindowXamlSource, also known
as Xaml Islands.

## Minimal - 200 line .cpp file Xaml App
The app client area is all Xaml. The markup is stored as a string and parsed at runtime. 
Less that 150 lines of code with 50 of it being markup.

![Win32 Xaml App](Win32XamlApp.png)

## Multi Window App - Supports multiple top level windows
This demonstrates a mulit-window Win32 app that uses Xaml.

![Win32 Xaml App Multi Window](Win32XamlAppMultiWindow.png)

## Multi Xaml Mulit Window App - Each Window hosts 2 Islands
Multi window app that creates 2 islands in each window. Mostly a diagnostic case for testing.

## Xaml Win32 Helpers
This is a collection of things that simplify use of Xaml in Win32 style apps.
