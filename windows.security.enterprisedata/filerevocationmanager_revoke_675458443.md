---
-api-id: M:Windows.Security.EnterpriseData.FileRevocationManager.Revoke(System.String)
-api-type: winrt method
---

<!-- Method syntax
public void Revoke(System.String enterpriseIdentity)
-->

# Windows.Security.EnterpriseData.FileRevocationManager.Revoke

## -description
> [!NOTE]
> [FileRevocationManager](filerevocationmanager.md) may be unavailable for releases after Windows 10. Instead, use [FileProtectionManager](fileprotectionmanager.md).



> [!NOTE]
> Windows Information Protection (WIP) policy cannot be applied on Windows 10, version 1511 (build 10586) or earlier.

Revokes all files and folders protected for selective wipe for a specified enterprise id.

## -parameters
### -param enterpriseIdentity
Revoke all files and folders protected by selective wipe for this enterprise id. The *enterpriseIdentity* value must be formatted as an Internationalized Domain Name (IDN) and cannot contain spaces. For example, **contoso.com**.

## -remarks
When your app determines that a user is no longer valid, you can quickly revoke access to all of the files and folders protected for an enterprise identity using the Revoke method, as shown in the following example. The file is not deleted by the Revoke method. The Revoke method puts the file into state where it cannot be accessed. You can add code to your app to delete a file that is inaccessible and has been revoked.

## -examples

## -see-also
[FileRevocationManager sample](http://code.msdn.microsoft.com/windowsapps/File-Revocation-Manager-0d529428), [How to protect files with Selective Wipe  (C#/VB/C++)](https://docs.microsoft.com/previous-versions/windows/apps/dn456782(v=win.10)), [How to protect files with Selective Wipe (JavaScript)](https://docs.microsoft.com/previous-versions/windows/apps/dn456781(v=win.10))
