# Swift IEEE

Swift implementations of IEEE (Institute of Electrical and Electronics Engineers) specifications — a per-authority organization of [swift-standards](https://github.com/swift-standards), Layer 2 of the [Swift Institute](https://github.com/swift-institute) ecosystem.

## What this is

One package per specification, named `swift-ieee-<number>`. Each package implements its source document as literally as possible — parsing, validation, and formatting enforced by Swift's type system — and defines its own namespace (`IEEE_754`). Where several specifications govern one subject, the unifying `swift-*-standard` package lives in [swift-standards](https://github.com/swift-standards).

> Swift IEEE is an independent open-source project. It is not affiliated with, endorsed by, or sponsored by IEEE (Institute of Electrical and Electronics Engineers).

## Coverage

| Package | Specification |
|---|---|
| [swift-ieee-754](https://github.com/swift-ieee/swift-ieee-754) | IEEE Standard for Floating-Point Arithmetic |

Every repository description carries the specification's full title; the [repositories tab](https://github.com/orgs/swift-ieee/repositories) lists them all.

## Status

Public alpha. Maintained by [Coen ten Thije Boonkkamp](https://github.com/coenttb) — contributions welcome via pull request.

## License

All packages use the Apache License 2.0.
