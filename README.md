# nuget-longpath-test

https://github.com/dotnet/sdk/blob/19f2c34241be811a58ed51f74065e9592487c9b8/src/Tasks/Microsoft.NET.Build.Tasks/targets/Microsoft.NET.Sdk.targets#L424


C:\Program Files\dotnet\sdk\3.1.300\Sdks\Microsoft.NET.Sdk\targets\Microsoft.NET.Sdk.targets(424,5): error MSB4018: The "CreateAppHost" task failed unexpectedly. 
C:\Program Files\dotnet\sdk\3.1.300\Sdks\Microsoft.NET.Sdk\targets\Microsoft.NET.Sdk.targets(424,5): error MSB4018: Microsoft.NET.HostModel.HResultException: 8007007A 
C:\Program Files\dotnet\sdk\3.1.300\Sdks\Microsoft.NET.Sdk\targets\Microsoft.NET.Sdk.targets(424,5): error MSB4018:    at Microsoft.NET.HostModel.ResourceUpdater.ThrowExceptionForLastWin32Error()
C:\Program Files\dotnet\sdk\3.1.300\Sdks\Microsoft.NET.Sdk\targets\Microsoft.NET.Sdk.targets(424,5): error MSB4018:    at Microsoft.NET.HostModel.ResourceUpdater.Update() 
C:\Program Files\dotnet\sdk\3.1.300\Sdks\Microsoft.NET.Sdk\targets\Microsoft.NET.Sdk.targets(424,5): error MSB4018:    at Microsoft.NET.HostModel.RetryUtil.RetryOnWin32Error(Action func) 
.HostModel.AppHost.HostWriter.CreateAppHost(String appHostSourceFilePath, String appHostDestinationFilePath, String appBinaryFilePath, Boolean windowsGraphicalUserInterface, String assemblyToCopyResorcesFrom) 
C:\Program Files\dotnet\sdk\3.1.300\Sdks\Microsoft.NET.Sdk\targets\Microsoft.NET.Sdk.targets(424,5): error MSB4018:    at Microsoft.NET.Build.Tasks.CreateAppHost.ExecuteCore() 
C:\Program Files\dotnet\sdk\3.1.300\Sdks\Microsoft.NET.Sdk\targets\Microsoft.NET.Sdk.targets(424,5): error MSB4018:    at Microsoft.NET.Build.Tasks.TaskBase.Execute() 
C:\Program Files\dotnet\sdk\3.1.300\Sdks\Microsoft.NET.Sdk\targets\Microsoft.NET.Sdk.targets(424,5): error MSB4018:    at Microsoft.Build.BackEnd.TaskExecutionHost.Microsoft.Build.BackEnd.ITaskExecutionHost.Execute() C:\Program Files\dotnet\sdk\3.1.300\Sdks\Microsoft.NET.Sdk\targets\Microsoft.NET.Sdk.targets(424,5): error MSB4018:    at Microsoft.Build.BackEnd.TaskBuilder.ExecuteInstantiatedTask(ITaskExecutionHost taskExecutionHost, TaskLoggingContext taskLoggingContext, TaskHost taskHost, ItemBucket bucket, TaskExecutionMode howToExecuteTask) 
