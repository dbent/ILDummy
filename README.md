# ILDummy

**ILDummy** is a [MIT-licensed](LICENSE.md) utility to generate *dummies* from [Common Intermediate Language](cil)
assemblies. A *dummy* is an assembly that has the same public API as another assembly but no actual implementation. A
dummy assembly can then be used in place of a real assembly during compilation in situations where it's not possible
or advisable to have the real assembly available.

[cil]: https://en.wikipedia.org/wiki/Common_Intermediate_Language
