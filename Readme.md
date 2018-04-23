# DiagramControl - How to create custom shapes with connection points using XAML markup


This example demonstrates how to describe custom shapes using the XAML markup instead of XML.<br><br><strong>Important note:</strong> The PresentationCore library used in this example affects the DPI awareness of WinForms applications (see <a href="https://www.devexpress.com/Support/Center/p/T346466">T346466 - DiagramControl disables DPI scaling for the entire application</a>). Use this approach only if your application is not DPI aware or the PresentationCore library is pre-loaded in the Program.Main method as follows:<br>


```cs
static void RegisterPackUriScheme() {
    new FlowDocument();
}
```


<p>In other cases, it is preferred to describe shapes using XML, as demonstrated in the following example: <a href="https://www.devexpress.com/Support/Center/p/T324404">T324404 - DiagramControl - How to create custom shapes with connection points</a>.</p>

<br/>


