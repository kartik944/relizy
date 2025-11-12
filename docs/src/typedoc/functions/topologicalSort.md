[relizy](../globals.md) / topologicalSort

# Function: topologicalSort()

> **topologicalSort**(`packages`): [`PackageWithDeps`](../interfaces/PackageWithDeps.md)[]

Defined in: [src/core/dependencies.ts:137](https://github.com/LouisMazel/relizy/blob/190a723062a3fdb8a34b2254faf889a750c01d70/src/core/dependencies.ts#L137)

Topological sort of packages based on their dependencies
Ensures dependencies are processed before dependents

## Parameters

### packages

[`PackageWithDeps`](../interfaces/PackageWithDeps.md)[]

## Returns

[`PackageWithDeps`](../interfaces/PackageWithDeps.md)[]
