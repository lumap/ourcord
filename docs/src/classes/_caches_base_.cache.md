# Class: Cache

## Hierarchy

* **Cache**

## Index

### Constructors

* [constructor](_caches_base_.cache.md#constructor)

### Properties

* [channels](_caches_base_.cache.md#channels)
* [guilds](_caches_base_.cache.md#guilds)
* [members](_caches_base_.cache.md#members)
* [options](_caches_base_.cache.md#options)
* [users](_caches_base_.cache.md#users)

### Methods

* [\_bind](_caches_base_.cache.md#_bind)

## Constructors

### constructor

\+ **new Cache**(`client`: [Client](_websocket_.client.md), `options?`: [ClientOptions](../interfaces/_websocket_.clientoptions.md)): [Cache](_caches_base_.cache.md)

*Defined in [src/caches/base.ts:13](https://github.com/ourcord/ourcord/blob/175a597/src/caches/base.ts#L13)*

#### Parameters:

Name | Type |
------ | ------ |
`client` | [Client](_websocket_.client.md) |
`options?` | [ClientOptions](../interfaces/_websocket_.clientoptions.md) |

**Returns:** [Cache](_caches_base_.cache.md)

## Properties

### channels

•  **channels**: [Channel](../interfaces/_structures_types_.channel.md)

*Defined in [src/caches/base.ts:10](https://github.com/ourcord/ourcord/blob/175a597/src/caches/base.ts#L10)*

___

### guilds

•  **guilds**: [Guild](../interfaces/_structures_types_.guild.md)

*Defined in [src/caches/base.ts:11](https://github.com/ourcord/ourcord/blob/175a597/src/caches/base.ts#L11)*

___

### members

•  **members**: [Member](../interfaces/_structures_types_.member.md)

*Defined in [src/caches/base.ts:13](https://github.com/ourcord/ourcord/blob/175a597/src/caches/base.ts#L13)*

___

### options

•  **options**: [ClientOptions](../interfaces/_websocket_.clientoptions.md)

*Defined in [src/caches/base.ts:9](https://github.com/ourcord/ourcord/blob/175a597/src/caches/base.ts#L9)*

___

### users

•  **users**: [User](../interfaces/_structures_types_.user.md)

*Defined in [src/caches/base.ts:12](https://github.com/ourcord/ourcord/blob/175a597/src/caches/base.ts#L12)*

## Methods

### \_bind

▸ **_bind**(`client`: [Client](_websocket_.client.md)): void

*Defined in [src/caches/base.ts:23](https://github.com/ourcord/ourcord/blob/175a597/src/caches/base.ts#L23)*

#### Parameters:

Name | Type |
------ | ------ |
`client` | [Client](_websocket_.client.md) |

**Returns:** void
