# @_exported

Just re-export whatever you import, or import proxy/forwarding.

`Bar` Module depends on `Foo` Module, and use `@_exported import Foo` re-export `Foo` Module.

`Baz` depends on `Bar`.

https://forums.swift.org/t/what-does-exported-import-do/35869/3
https://stackoverflow.com/questions/41000256/what-is-import-func-struct-class-and-exported-in-swift
