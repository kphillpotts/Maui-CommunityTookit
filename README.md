<!--<img src="https://user-images.githubusercontent.com/13558917/137551073-ac8958bf-83e3-4ae3-8623-4db6dce49d02.png" alt="..NET Bot" width=125>  [<img src="https://raw.githubusercontent.com/dotnet-foundation/swag/master/logo/dotnetfoundation_v4.svg" alt=".NET Foundation" width=100>](https://dotnetfoundation.org) -->

 

# 🧰 .NET MAUI Community Toolkit

The .NET MAUI Community Toolkit is a collection of common elements for development with .NET MAUI that developers tend to replicate across multiple apps. It simplifies and demonstrates common developer tasks when building apps with .NET MAUI. 

All features are contributed by you, our amazing .NET community, and maintained by a core set of maintainers.

And – the best part – the features you add to the .NET MAUI Toolkit may one day be included into the official .NET MAUI library! We leverage the Community Toolkits to debut new features and work closely with the .NET MAUI engineering team to nominate features for promotion.

| Package | Status | Package Status |
| ------- | ------------ | -------------- |
| CommunityToolkit.Maui | [![Build Status](https://dev.azure.com/dotnet/CommunityToolkit/_apis/build/status/CommunityToolkit.Maui?branchName=main)](https://dev.azure.com/dotnet/CommunityToolkit/_build/latest?definitionId=169&branchName=main) | [![NuGet](https://buildstats.info/nuget/CommunityToolkit.Maui?includePreReleases=true)](https://www.nuget.org/packages/CommunityToolkit.Maui/) |

## 🙌 Getting Started

In order to use the .NET MAUI Community Toolkit you need to call the extension method in your `MauiProgram.cs` file as follows:

```csharp
using CommunityToolkit.Maui;

public static class MauiProgram
{
	public static MauiApp CreateMauiApp()
	{
		var builder = MauiApp.CreateBuilder();
		
		// Initialise the toolkit
		builder.UseMauiApp<App>().UseMauiCommunityToolkit();

		// the rest of your logic...
	}
}
```

### XAML usage

In order to make use of the toolkit within XAML you can use this namespace:

```xml
xmlns:toolkit="http://schemas.microsoft.com/dotnet/2022/maui/toolkit"
```

For further information please read the [Get Started](https://docs.microsoft.com/en-us/dotnet/communitytoolkit/maui/get-started) page in the documenation.

## 📃 Documentation

All documentation for the toolkit is hosted on [Microsoft Docs](https://docs.microsoft.com/dotnet/communitytoolkit/maui/).

## 🚀 Contribution

Do you want to contribute?

Check out our [Contribution Guidelines](/CONTRIBUTING.md) page to learn more about contribution and guidelines!

## 🌍 Roadmap

Read what we [plan for next iterations](https://github.com/CommunityToolkit/maui/milestones), and feel free to ask questions.

## 📄 Code of Conduct

As a part of the .NET Foundation, we have adopted the [.NET Foundation Code of Conduct](https://dotnetfoundation.org/code-of-conduct). Please familiarize yourself with that before participating with this repository. Thanks!


## 🏢 .NET Foundation

This project is supported by the [.NET Foundation](http://dotnetfoundation.org).


## 🏆 Contributors

[![Toolkit Contributors](https://contrib.rocks/image?repo=CommunityToolkit/Maui)](https://github.com/CommunityToolkit/Maui/graphs/contributors)

Made with [contrib.rocks](https://contrib.rocks).