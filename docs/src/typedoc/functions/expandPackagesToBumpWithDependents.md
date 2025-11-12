[relizy](../globals.md) / expandPackagesToBumpWithDependents

# Function: expandPackagesToBumpWithDependents()

> **expandPackagesToBumpWithDependents**(`__namedParameters`): [`PackageToBump`](../interfaces/PackageToBump.md)[]

Defined in: [src/core/dependencies.ts:70](https://github.com/LouisMazel/relizy/blob/190a723062a3fdb8a34b2254faf889a750c01d70/src/core/dependencies.ts#L70)

Recursively expand packages to bump with all their dependents (transitive)
Returns packages with reason for bumping and dependency chain for traceability

## Parameters

### \_\_namedParameters

#### allPackages

[`PackageInfo`](../interfaces/PackageInfo.md)[]

#### dependencyTypes

(`"dependencies"` \| `"peerDependencies"` \| `"devDependencies"`)[] \| `undefined`

#### packagesWithCommits

[`PackageWithCommits`](../interfaces/PackageWithCommits.md)[]

## Returns

[`PackageToBump`](../interfaces/PackageToBump.md)[]
