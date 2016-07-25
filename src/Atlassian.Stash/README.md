# .Net Core support

Initial implementation to support .Net Core.
**Currently this project does NOT compile. Unload it to avoid compilation errors.**

## Issues

 - HttpClient does not support generic PostAsync<T>
 - Missing JsonMediaTypeFormatter(). In other words missing support for 'System.Net.Http.Formatting'
 - .Net Core projects currently can't use Visual Studio Shared Projects, that's why all the code is duplicated
 - Missing test project for .Net Core support