## C++20 with UE4

Slightly changed **Unreal Build Tool** files to support **C++20** standart when using UE4 with visual studio, so the code below is valid for use in **_ModuleName_.Build.cs**.
```
CppStandard = CppStandardVersion.Cpp20;
```

### Compatibility
* Tested with Unreal Engine 4.27.2 and Visual Studio 2022
