# .net-maui-notes
Ejemplo Notes en .Net MAUI, básico. Modificado con fines didácticos. Original: https://learn.microsoft.com/en-us/dotnet/maui/tutorials/notes-app/
> Maneja una sola nota. 📱


## Nota:
En AboutPage.xaml.cs, se usa un link ejemplo C#.
```
    private async void LearnMore_Clicked(object sender, EventArgs e)
    {
        // Navigate to the specified URL in the system browser.
        await Launcher.Default.OpenAsync("https://www.tecnm.mx/");
    }
```
## Potencializando:
Agregando funcionalidad al presente ejemplo.
* [Paso 4](https://learn.microsoft.com/en-us/dotnet/maui/tutorials/notes-app/?tutorial-step=4): Refactorice el código existente para separar el modelo de la vista. Los siguientes pasos organizarán el código para que las vistas y los modelos se definan por separado. 
