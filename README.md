# BankSystem sample

This repository contains an ASP.NET Core sample solution with bank-account,
central API, and demo-shop components. It is maintained under the
[@Ivane120585 GitHub account](https://github.com/Ivane120585).

This is sample software, not an official bank service or a production-ready
financial system. It does not provide authorization to access any bank, customer
account, payment network, or external token. Do not connect it to live financial
systems or use real customer data.

The web applications target .NET Core 3.1, which is out of support and no longer
receives security updates. Treat the solution as legacy code; migrate to a
supported .NET release and perform a security review before any deployment.

## Build and test

From the `src` directory:

```sh
dotnet restore BankSystem.sln
dotnet build BankSystem.sln --no-restore
dotnet test BankSystem.sln --no-restore
```

The GitHub Actions workflow runs these checks on the default branch and pull
requests. See [SECURITY.md](SECURITY.md) for reporting guidance and the limits of
this sample's security support.

Retain existing third-party copyright and license notices. Repository ownership,
package metadata, and commit history do not establish authorship or legal rights
to inherited source components.
