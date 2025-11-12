[relizy](../globals.md) / BumpResult

# Type Alias: BumpResult

> **BumpResult** = \{ `bumped`: `true`; `bumpedPackages`: [`PackageInfo`](../interfaces/PackageInfo.md)[]; `fromTag?`: `string`; `newVersion?`: `string`; `oldVersion?`: `string`; \} \| \{ `bumped`: `false`; \}

Defined in: [src/types.ts:43](https://github.com/LouisMazel/relizy/blob/190a723062a3fdb8a34b2254faf889a750c01d70/src/types.ts#L43)

## Type Declaration

\{ `bumped`: `true`; `bumpedPackages`: [`PackageInfo`](../interfaces/PackageInfo.md)[]; `fromTag?`: `string`; `newVersion?`: `string`; `oldVersion?`: `string`; \}

### bumped

> **bumped**: `true`

Bumped

### bumpedPackages

> **bumpedPackages**: [`PackageInfo`](../interfaces/PackageInfo.md)[]

Bumped packages

### fromTag?

> `optional` **fromTag**: `string`

Tag name

### newVersion?

> `optional` **newVersion**: `string`

New version

### oldVersion?

> `optional` **oldVersion**: `string`

Old version

\{ `bumped`: `false`; \}

### bumped

> **bumped**: `false`

Bumped
