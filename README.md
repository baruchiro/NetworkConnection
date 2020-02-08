# NetworkConnection

Represents a network connection along with authentication to a network share.

![Nuget](https://badgen.net/nuget/v/NetworkConnection)
![Publish](https://github.com/baruchiro/NetworkConnection/workflows/Publish/badge.svg?branch=master&event=push)

Based on [Daniel Hilgarth](https://stackoverflow.com/users/572644/daniel-hilgarth)'s [answer](https://stackoverflow.com/a/5433640/839513) from Stack Overflow.

## Usage

```cs
using(new NetworkConnection(_directoryPath, new NetworkCredential(_userName, _password)))
{
    File.Copy(localPath, _directoryPath);
}
```
