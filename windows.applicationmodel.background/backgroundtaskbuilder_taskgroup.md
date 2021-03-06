---
-api-id: P:Windows.ApplicationModel.Background.BackgroundTaskBuilder.TaskGroup
-api-type: winrt property
---

<!-- Property syntax.
public BackgroundTaskRegistrationGroup TaskGroup { get;  set; }
-->

# Windows.ApplicationModel.Background.BackgroundTaskBuilder.TaskGroup

## -description
Gets and sets the group identifier.

## -property-value
The group identifier.

## -remarks
To reduce collisions with other group identifiers, consider including your domain name in the group identifier. For example: `"com.contoso.appname.tasks"`. Or use the string form of a GUID.

## -see-also
[Launching, resuming, and background tasks](https://msdn.microsoft.com/windows/uwp/launch-resume/index)


## -examples
