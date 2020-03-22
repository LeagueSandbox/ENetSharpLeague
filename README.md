# ENetSharpLeague
League Compatible Version of ENet


## Compiling

Note: It seems that the SLN is old and should not be used. Rather the cmake should be used.
On mac had to: 
`brew install automake`
`brew install libtool`
`autoreconf -vfi`
`sudo chmod -R 755 ./`
`./configure && make && make install`

A dylib will be generated in a hidden folder at `.libs`.


## Generating a NuGet package

Generating a NuGet package can be done by running `nuget.exe` (not included in this repo, find it yourself) at the project root
with `nuget pack Package.nuspec`
