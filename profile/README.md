# Swift IEEE

Swift implementations of IEEE (Institute of Electrical and Electronics Engineers) specifications — a per-authority organization of [swift-standards](https://github.com/swift-standards), Layer 2 of the [Swift Institute](https://github.com/swift-institute) ecosystem.

## What this is

One package per specification, named `swift-ieee-<number>`. Each package implements its source document as literally as possible — parsing, validation, and formatting enforced by Swift's type system — and defines its own namespace (`IEEE_754`). Where several specifications govern one subject, the unifying `swift-*-standard` package lives in [swift-standards](https://github.com/swift-standards).

> Swift IEEE is an independent open-source project. It is not affiliated with, endorsed by, or sponsored by IEEE (Institute of Electrical and Electronics Engineers).

## Where to find implementations

The [repositories tab](https://github.com/orgs/swift-ieee/repositories) is the complete,
current list of implementations. Packages follow the `swift-ieee-<number>` naming
convention; [filter by that prefix](https://github.com/orgs/swift-ieee/repositories?q=swift-ieee-)
to browse the specifications represented here. Each repository description carries its
specification's full title.

For a starting point, see the [IEEE 754 implementation](https://github.com/swift-ieee/swift-ieee-754).

## Status

Public alpha. Maintained by [Coen ten Thije Boonkkamp](https://github.com/coenttb) — contributions welcome via pull request.

## License

All packages use the Apache License 2.0.
