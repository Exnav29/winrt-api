---
-api-id: T:Windows.Foundation.IGetActivationFactory
-api-type: winrt interface
---

<!-- Interface syntax.
public interface IGetActivationFactory : 
-->

# Windows.Foundation.IGetActivationFactory

## -description
Defines the implementation for a type that retrieves activation factories.

## -remarks
For typical apps (those that use C#, Visual Basic, C++/CX or JavaScript for programming language), this interface should be considered as an infrastructure piece that the overall Windows Runtime programming experience uses as an implementation detail. There are no common app development scenarios that rely on implementing or using the IGetActivationFactory interface directly.

The scenario that IGetActivationFactory supports is if you are defining Windows Runtime components using WRL, which are packaged as separate executables. In this case, there is no automatic activation as part of the app model, and the component is responsible for the activation of its classes prior to use (through various APIs in the [Windows.ApplicationModel.Core](../windows.applicationmodel.core/windows_applicationmodel_core.md) namespace). For a sample that illustrates how to implement this, see [Creating a  EXE component with C++ sample](http://code.msdn.microsoft.com/windowsapps/Creating-a-Windows-Runtime-ed84af9d).

### Notes to implementers

The implementation of a type that supports this interface must have a method called [GetActivationFactory](igetactivationfactory_getactivationfactory_505965722.md) that takes an Activation ID (ACID) as a parameter and returns a type that implements [IActivationFactory](https://docs.microsoft.com/windows/desktop/api/activation/nn-activation-iactivationfactory).

## -examples

## -see-also
[CoreApplication.RunWithActivationFactories](../windows.applicationmodel.core/coreapplication_runwithactivationfactories_672867736.md)
