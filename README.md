Xunit.StaFact
======================

[![Build status](https://ci.appveyor.com/api/projects/status/oxq7bw2gxyksaji9/branch/master?svg=true)](https://ci.appveyor.com/project/AArnott/xunit-stafact/branch/master)
[![NuGet package](https://img.shields.io/nuget/v/xunit.stafact.svg)](https://nuget.org/packages/xunit.stafact)

This project allows for Xunit tests to run on an STA thread instead of
the default MTA. It also offers attributes that apply the WPF or
Windows Forms SynchronizationContexts to that thread to more fully
emulate a windowed application and to ensure that async tests resume
execution on the same thread as they would in a real app.

## Installation

This project is available as a [NuGet package][NuPkg]

See [samples](src/Xunit.StaFact.Tests/Samples.cs)

[NuPkg]: https://www.nuget.org/packages/Xunit.StaFact
