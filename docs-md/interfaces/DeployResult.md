[alchemy-sdk](../README.md) / [Exports](../modules.md) / DeployResult

# Interface: DeployResult

The response object for the [findContractDeployer](../classes/CoreNamespace.md#findcontractdeployer) function.

## Table of contents

### Properties

- [blockNumber](DeployResult.md#blocknumber)
- [deployerAddress](DeployResult.md#deployeraddress)

## Properties

### blockNumber

• `Readonly` **blockNumber**: `number`

The block number the contract was deployed in.

#### Defined in

[src/types/types.ts:1464](https://github.com/alchemyplatform/alchemy-sdk-js/blob/0c05b32/src/types/types.ts#L1464)

___

### deployerAddress

• `Optional` `Readonly` **deployerAddress**: `string`

The address of the contract deployer, if it is available.

#### Defined in

[src/types/types.ts:1461](https://github.com/alchemyplatform/alchemy-sdk-js/blob/0c05b32/src/types/types.ts#L1461)
