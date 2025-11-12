[relizy](../globals.md) / bumpPackageIndependently

# Function: bumpPackageIndependently()

> **bumpPackageIndependently**(`__namedParameters`): \{ `bumped`: `true`; `newVersion`: `string`; `oldVersion`: `string`; \} \| \{ `bumped`: `false`; \}

Defined in: [src/core/version.ts:391](https://github.com/LouisMazel/relizy/blob/190a723062a3fdb8a34b2254faf889a750c01d70/src/core/version.ts#L391)

## Parameters

### \_\_namedParameters

#### dryRun

`boolean`

#### pkg

[`PackageToBump`](../interfaces/PackageToBump.md) & [`PackageInfo`](../interfaces/PackageInfo.md)

## Returns

\{ `bumped`: `true`; `newVersion`: `string`; `oldVersion`: `string`; \} \| \{ `bumped`: `false`; \}
