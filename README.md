[![](https://img.shields.io/nuget/v/soenneker.extensions.requestdataoptions.svg?style=for-the-badge)](https://www.nuget.org/packages/soenneker.extensions.requestdataoptions/)
[![](https://img.shields.io/github/actions/workflow/status/soenneker/soenneker.extensions.requestdataoptions/publish-package.yml?style=for-the-badge)](https://github.com/soenneker/soenneker.extensions.requestdataoptions/actions/workflows/publish-package.yml)
[![](https://img.shields.io/nuget/dt/soenneker.extensions.requestdataoptions.svg?style=for-the-badge)](https://www.nuget.org/packages/soenneker.extensions.requestdataoptions/)
[![](https://img.shields.io/github/actions/workflow/status/soenneker/soenneker.extensions.requestdataoptions/codeql.yml?label=CodeQL&style=for-the-badge)](https://github.com/soenneker/soenneker.extensions.requestdataoptions/actions/workflows/codeql.yml)

# ![](https://user-images.githubusercontent.com/4441470/224455560-91ed3ee7-f510-4041-a8d2-3fc093025112.png) Soenneker.Extensions.RequestDataOptions
An empty extension namespace reserved for `RequestDataOptions` APIs.

## Installation

```bash
dotnet add package Soenneker.Extensions.RequestDataOptions
```

## API surface

This package contains the empty static type `RequestDataOptionsExtension`. It defines no extension methods, configuration, or runtime behavior. Do not add it when the application only needs the DTO; reference [`Soenneker.Dtos.RequestDataOptions`](https://www.nuget.org/packages/Soenneker.Dtos.RequestDataOptions/) directly.

To apply exact filters, ranges, search fields, and ordering from `RequestDataOptions` to an `IQueryable<T>`, use [`Soenneker.Extensions.IQueryables`](https://www.nuget.org/packages/Soenneker.Extensions.IQueryables/).
