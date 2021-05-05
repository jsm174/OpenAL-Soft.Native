# A simple GitHub workflow that builds native binaries for OpenAL Soft.

The OpenAL Soft [website](https://openal-soft.org/) refers to a more up-to-date repo at: https://github.com/kcat/openal-soft.

The workflow currently downloads the [1.21.1](https://github.com/kcat/openal-soft/releases/tag/1.21.1) release.

The binaries are artifacts from the workflow.

## Motivation:

The hope is someday these can be offered as a package in Silk.NET. 

## Real Motivation:

I was building a cross platform .NET application, and after having it work fine on MacOS, I realized Windows does not have OpenAL binaries installed. 

As a developer, I just wanted to include Silk.NET as a dependency and have it just work. 
