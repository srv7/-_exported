# @_exported

Just re-export whatever you import, or import proxy/forwarding.

`Bar` Module depends on `Foo` Module, and use `@_exported import Foo` re-export `Foo` Module.
`Baz` depends on `Bar`.
