---
-api-id: T:Windows.UI.Xaml.Input.ManipulationStartingEventHandler
-api-type: winrt delegate
---
<!-- Delegate syntax.
public delegate void ManipulationStartingEventHandler(System.Object sender, Windows.UI.Xaml.Input.ManipulationStartingRoutedEventArgs e)
-->
# Windows.UI.Xaml.Input.ManipulationStartingEventHandler

## -description
Represents the method that will handle the [ManipulationStarting](../windows.ui.xaml/uielement_manipulationstarting.md) event.

## -parameters
### -param sender
The object where the event handler is attached.

### -param e
Event data for the event.


## -remarks

## -examples
The following code example shows scenario 4 from the [Input sample](http://code.msdn.microsoft.com/windowsapps/Input-3dff271b). This code shows some usage patterns for direct manipulation using the [ManipulationStarting](../windows.ui.xaml/uielement_manipulationstarting.md), [ManipulationStarted](../windows.ui.xaml/uielement_manipulationstarted.md), [ManipulationDelta](../windows.ui.xaml/uielement_manipulationdelta.md), [ManipulationInertiaStarting](../windows.ui.xaml/uielement_manipulationinertiastarting.md), and [ManipulationCompleted](../windows.ui.xaml/uielement_manipulationcompleted.md) events.



[!code-csharp[Scenario4Code](../windows.ui.xaml/code/input/csharp/Scenario4.xaml.cs#SnippetScenario4Code)]

[!code-vb[Scenario4Code](../windows.ui.xaml/code/input/vbnet/Scenario4.xaml.vb#SnippetScenario4Code)]


## -see-also
