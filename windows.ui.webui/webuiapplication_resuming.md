---
-api-id: E:Windows.UI.WebUI.WebUIApplication.Resuming
-api-type: winrt event
---

<!-- Event syntax
static public event Windows.UI.WebUI.ResumingEventHandler Resuming
-->

# Windows.UI.WebUI.WebUIApplication.Resuming

## -description
Occurs when the app is resuming.

## -remarks
The system suspends your app whenever the user switches to another app or to the desktop. The system resumes your app whenever the user switches back to it. When the system resumes your app, the content of your variables and data structures is the same as it was before the system suspended the app. The system restores the app exactly where it left off, so that it appears to the user as if it's been running in the background. However, the app may have been suspended for a significant amount of time, so it should refresh any displayed content that might have changed while the app was suspended, such as news feeds or the user's location. If your app doesn't have any displayed content to refresh, there's no need for it to handle the resuming event.

## -examples

## -see-also
[App lifecycle](https://docs.microsoft.com/windows/uwp/launch-resume/app-lifecycle), [App activated, resume, and suspend using the WRL sample](http://code.msdn.microsoft.com/windowsapps/App-activating-and-ec15b168)
