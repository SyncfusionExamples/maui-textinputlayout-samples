# maui-textinputlayout-samples
Contains samples for .NET MAUI TextInputLayout control

# Getting Started with the .NET MAUI TextInputLayout Control
The text input layout adds decorative elements like floating labels, icons, and assistive labels on top of input views such as Entry and Editor, SfAutocomplete, SfComboBox controls.

Documentation: https://help.syncfusion.com/maui/textinputlayout/getting-started

### Adding the .NET MAUI TextInputLayout control

Step 1: Add the NuGet to the project and add the namespace as shown in the following code sample:

**[XAML]**
```
    xmlns:inputLayout="clr-namespace:Syncfusion.Maui.Core;assembly=Syncfusion.Maui.Core"
```	

**[C#]**
```
    using Syncfusion.Maui.Core;
```

Step 2: Set the TextInputLayout control to content in `ContentPage.`

**[XAML]**
```
<inputLayout:SfTextInputLayout>
   <Entry />
</inputLayout:SfTextInputLayout>
```	

**[C#]**
```
          
var inputLayout = new SfTextInputLayout();
inputLayout.Content = new Entry();  
```

## Project pre-requisites

Make sure that you have the compatible versions of Visual Studio with .NET MAUI workloads and .NET SDK version in your machine before starting to work on this project. Refer to [System Requirements for .NET MAUI](https://help.syncfusion.com/maui/system-requirements).

## How to run this application?

To run this application, you need to first clone the getting-started-with-the-dotnet-maui-combobox-controls repository and then open it in Visual Studio 2022. Now, simply build and run your project to view the output.

## <a name="troubleshooting"></a>Troubleshooting ##
### Path too long exception
If you are facing path too long exception when building this example project, close Visual Studio and rename the repository to short and build the project.

## License

Syncfusion has no liability for any damage or consequence that may arise by using or viewing the samples. The samples are for demonstrative purposes, and if you choose to use or access the samples, you agree to not hold Syncfusion liable, in any form, for any damage that is related to use, for accessing, or viewing the samples. By accessing, viewing, or seeing the samples, you acknowledge and agree Syncfusion’s samples will not allow you seek injunctive relief in any form for any claim related to the sample. If you do not agree to this, do not view, access, utilize, or otherwise do anything with Syncfusion’s samples.