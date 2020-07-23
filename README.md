# Build

Build with Visual Studio 2019 IDE or using Visual Studio x64 command prompt as follows:

```
nuget.exe restore stress\stress.sln
msbuild /p:Configuration=Debug,Platform=x64 stress\stress.sln
```

Build time will be reported across c1xx.dll (frontend) and c2.dll (backend) - combine the two to determine how long it takes.
