# Crasher

A simple .NET Core 3.1 console application for testing crash handling.

To produce a crash, simply run the following commands with a .NET Core 3.1.x SDK installed:

```cmd
> git clone https://github.com/martincostello/Crasher.git
> cd Crasher
> dotnet run

Process is terminating due to StackOverflowException.

>
```

For portability on other machines, run the following commands:

```cmd
> git clone https://github.com/martincostello/Crasher.git
> cd Crasher
> dotnet publish
```

The default [runtime identifier](https://docs.microsoft.com/en-us/dotnet/core/rid-catalog) is `win-x64`. To use another RID, use the `--runtime` flag; for example:

```cmd
> git clone https://github.com/martincostello/Crasher.git
> cd Crasher
> dotnet publish --runtime linux-x64
```

## Feedback

Any feedback or issues can be added to the issues for this project in [GitHub](https://github.com/martincostello/Crasher/issues "Issues for this project on GitHub.com").

## Repository

The repository is hosted in [GitHub](https://github.com/martincostello/Crasher "This project on GitHub.com"): https://github.com/martincostello/Crasher.git

## License

This project is licensed under the [Apache 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt "The Apache 2.0 license") license.
