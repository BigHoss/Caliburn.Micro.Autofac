# Caliburn.Micro.AutofacBootstrap

Home of the [Caliburn.Micro.AutofacBootstrap](http://nuget.org/List/Packages/Caliburn.Micro.AutofacBootstrap) nuget package.
Integrates [Caliburn.Micro](https://github.com/Caliburn-Micro/Caliburn.Micro) bootstrapping phase with [Autofac](https://github.com/autofac/Autofac) IoC container,
so that you can register dependencies at application starts up and make them available to view-models and other components.

## Building from Source

Minimum requirements:

* Visual Studio Community 2013
* Windows Phone SDK 8.0, available [here](https://www.microsoft.com/en-us/download/details.aspx?id=35471)

### Troubleshooting

**Could not find SDK "BehaviorsXamlSDKManaged, version=12.0"**

Make sure that Behaviors SDK is installed under Universal App Platform location.

If not already there, copy extension SDKs from the Windows 8.1 SDK location to the Windows 10 Universal App Platform location
(see Release Notes [here](https://go.microsoft.com/fwlink/p/?LinkId=526491)). That is, from:

```
%ProgramFiles(x86)%\Microsoft SDKs\Windows\v8.1\ExtensionSDKs
```

to:

```
%ProgramFiles(x86)%\Microsoft SDKs\UAP\v0.8.0.0\ExtensionSDKs
```

## Acknowledgments

The Caliburn.Micro.Autofac project is making use of the following OSS projects:

* [Autofac](http://autofac.org/) - under the [MIT license](https://github.com/autofac/Autofac/blob/develop/LICENSE)
* [Caliburn.Micro](http://caliburnmicro.com/) - under the [MIT license](https://github.com/Caliburn-Micro/Caliburn.Micro/blob/master/License.txt)

## License

This project is licensed under the [MIT license](./License.txt).
