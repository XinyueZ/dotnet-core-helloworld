First-time with [.NET Core](https://dotnet.github.io/)
====

### What

> .NET Core has two major components. It includes a small runtime that is built from the same codebase as the .NET Framework CLR. The .NET Core runtime includes the same GC and JIT (RyuJIT), but doesn’t include features like Application Domains or Code Access Security. The runtime is delivered via NuGet, as part of the ASP.NET 5 core package.

.NET Core also includes the base class libraries. These libraries are largely the same code as the .NET Framework class libraries, but have been factored (removal of dependencies) to enable us to ship a smaller set of libraries. These libraries are shipped as System.* NuGet packages on NuGet.org.

### Ready

You should have openSSL on your machine.
https://github.com/dotnet/core/issues/173

### Hello, World

- Run from source using the following commands:

```
	dotnet restore
	dotnet restore	
```

- Compile and run using the following commands:

```
	dotnet restore
	dotnet build
	dotnet bin/Debug/[framework]/[binary name]
```


