# Nissan Connect Client Library

[![CI](https://github.com/hagronnestad/nissan-connect-dotnet/workflows/Nuget%20Release/badge.svg)](https://github.com/hagronnestad/nissan-connect-dotnet/actions/workflows/main.yml) [![Nuget](https://img.shields.io/nuget/v/NissanConnectLib)](https://www.nuget.org/packages/NissanConnectLib)

This repository contains an ***unofficial*** C# .NET client library for the Nissan Connect API. This library is based on the great [dartnissanconnect](https://gitlab.com/tobiaswkjeldsen/dartnissanconnect)-library by [@Tobiaswk](https://github.com/Tobiaswk).

⚠️ This library supports the EU-region only. (I think?)

---

**Table of Contents**

- [Nissan Connect Client Library](#nissan-connect-client-library)
  - [Example Program](#example-program)
  - [Nuget](#nuget)
    - [Publish Nuget Package](#publish-nuget-package)
  - [Disclaimer](#disclaimer)


## Example Program

[An example program can be found here.](NissanConnect/NissanConnectLib.Example/)

*Output preview of the example program:*

![](Screenshots/02-example-output-2.png)


## Nuget

This library is available as a Nuget [here](https://www.nuget.org/packages/NissanConnectLib).

[![Nuget](https://img.shields.io/nuget/v/NissanConnectLib)](https://www.nuget.org/packages/NissanConnectLib)

*Nuget package installation commands:*
```
dotnet add package NissanConnectLib 

PM> NuGet\Install-Package NissanConnectLib

<PackageReference Include="NissanConnectLib" Version="" />
```


### Publish Nuget Package
Create a new GitHub Release with a tag to trigger the `Nuget Release`-action.


## Disclaimer
This library is not endorsed by, directly affiliated with, maintained, authorized, or sponsored by Nissan Motor Corporation. All product and company names are the registered trademarks of their original owners. The use of any trade name or trademark is for identification and reference purposes only and does not imply any association with the trademark holder of their product brand.
