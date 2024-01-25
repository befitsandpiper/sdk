**@gala-chain/api** ∙ [API](../exports.md)

***

[API](../exports.md) > FetchTokenSupplyDto

# Class: FetchTokenSupplyDto

## Contents

- [Extends](FetchTokenSupplyDto.md#extends)
- [Constructors](FetchTokenSupplyDto.md#constructors)
  - [new FetchTokenSupplyDto()](FetchTokenSupplyDto.md#new-fetchtokensupplydto)
- [Properties](FetchTokenSupplyDto.md#properties)
  - [additionalKey](FetchTokenSupplyDto.md#additionalkey)
  - [category](FetchTokenSupplyDto.md#category)
  - [collection](FetchTokenSupplyDto.md#collection)
  - [signature](FetchTokenSupplyDto.md#signature)
  - [signerPublicKey](FetchTokenSupplyDto.md#signerpublickey)
  - [trace](FetchTokenSupplyDto.md#trace)
  - [type](FetchTokenSupplyDto.md#type)
  - [uniqueKey](FetchTokenSupplyDto.md#uniquekey)
  - [ENCODING](FetchTokenSupplyDto.md#encoding)
- [Methods](FetchTokenSupplyDto.md#methods)
  - [isSignatureValid()](FetchTokenSupplyDto.md#issignaturevalid)
  - [serialize()](FetchTokenSupplyDto.md#serialize)
  - [sign()](FetchTokenSupplyDto.md#sign)
  - [signed()](FetchTokenSupplyDto.md#signed)
  - [validate()](FetchTokenSupplyDto.md#validate)
  - [validateOrReject()](FetchTokenSupplyDto.md#validateorreject)
  - [deserialize()](FetchTokenSupplyDto.md#deserialize)

## Extends

- [`ChainCallDTO`](ChainCallDTO.md)

## Constructors

### new FetchTokenSupplyDto()

> **new FetchTokenSupplyDto**(): [`FetchTokenSupplyDto`](FetchTokenSupplyDto.md)

#### Inherited from

[`ChainCallDTO`](ChainCallDTO.md).[`constructor`](ChainCallDTO.md#constructors)

## Properties

### additionalKey

> **additionalKey**: `string`

#### Source

[chain-api/src/types/mint.ts:243](https://github.com/GalaChain/sdk/blob/bcbbb18/chain-api/src/types/mint.ts#L243)

***

### category

> **category**: `string`

#### Source

[chain-api/src/types/mint.ts:231](https://github.com/GalaChain/sdk/blob/bcbbb18/chain-api/src/types/mint.ts#L231)

***

### collection

> **collection**: `string`

#### Source

[chain-api/src/types/mint.ts:225](https://github.com/GalaChain/sdk/blob/bcbbb18/chain-api/src/types/mint.ts#L225)

***

### signature

> **signature**?: `string`

#### Inherited from

[`ChainCallDTO`](ChainCallDTO.md).[`signature`](ChainCallDTO.md#signature)

#### Source

[chain-api/src/types/dtos.ts:134](https://github.com/GalaChain/sdk/blob/bcbbb18/chain-api/src/types/dtos.ts#L134)

***

### signerPublicKey

> **signerPublicKey**?: `string`

#### Inherited from

[`ChainCallDTO`](ChainCallDTO.md).[`signerPublicKey`](ChainCallDTO.md#signerpublickey)

#### Source

[chain-api/src/types/dtos.ts:143](https://github.com/GalaChain/sdk/blob/bcbbb18/chain-api/src/types/dtos.ts#L143)

***

### trace

> **trace**?: [`TraceContext`](../interfaces/TraceContext.md)

#### Inherited from

[`ChainCallDTO`](ChainCallDTO.md).[`trace`](ChainCallDTO.md#trace)

#### Source

[chain-api/src/types/dtos.ts:99](https://github.com/GalaChain/sdk/blob/bcbbb18/chain-api/src/types/dtos.ts#L99)

***

### type

> **type**: `string`

#### Source

[chain-api/src/types/mint.ts:237](https://github.com/GalaChain/sdk/blob/bcbbb18/chain-api/src/types/mint.ts#L237)

***

### uniqueKey

> **uniqueKey**?: `string`

#### Inherited from

[`ChainCallDTO`](ChainCallDTO.md).[`uniqueKey`](ChainCallDTO.md#uniquekey)

#### Source

[chain-api/src/types/dtos.ts:114](https://github.com/GalaChain/sdk/blob/bcbbb18/chain-api/src/types/dtos.ts#L114)

***

### ENCODING

> **`static`** **`readonly`** **ENCODING**: `"base64"` = `"base64"`

#### Inherited from

[`ChainCallDTO`](ChainCallDTO.md).[`ENCODING`](ChainCallDTO.md#encoding)

#### Source

[chain-api/src/types/dtos.ts:100](https://github.com/GalaChain/sdk/blob/bcbbb18/chain-api/src/types/dtos.ts#L100)

## Methods

### isSignatureValid()

> **isSignatureValid**(`publicKey`): `boolean`

#### Parameters

▪ **publicKey**: `string`

#### Inherited from

[`ChainCallDTO`](ChainCallDTO.md).[`isSignatureValid`](ChainCallDTO.md#issignaturevalid)

#### Source

[chain-api/src/types/dtos.ts:185](https://github.com/GalaChain/sdk/blob/bcbbb18/chain-api/src/types/dtos.ts#L185)

***

### serialize()

> **serialize**(): `string`

#### Inherited from

[`ChainCallDTO`](ChainCallDTO.md).[`serialize`](ChainCallDTO.md#serialize)

#### Source

[chain-api/src/types/dtos.ts:157](https://github.com/GalaChain/sdk/blob/bcbbb18/chain-api/src/types/dtos.ts#L157)

***

### sign()

> **sign**(`privateKey`, `useDer`): `void`

#### Parameters

▪ **privateKey**: `string`

▪ **useDer**: `boolean`= `false`

#### Inherited from

[`ChainCallDTO`](ChainCallDTO.md).[`sign`](ChainCallDTO.md#sign)

#### Source

[chain-api/src/types/dtos.ts:168](https://github.com/GalaChain/sdk/blob/bcbbb18/chain-api/src/types/dtos.ts#L168)

***

### signed()

> **signed**(`privateKey`, `useDer`): [`FetchTokenSupplyDto`](FetchTokenSupplyDto.md)

Creates a signed copy of current object.

#### Parameters

▪ **privateKey**: `string`

▪ **useDer**: `boolean`= `false`

#### Inherited from

[`ChainCallDTO`](ChainCallDTO.md).[`signed`](ChainCallDTO.md#signed)

#### Source

[chain-api/src/types/dtos.ts:179](https://github.com/GalaChain/sdk/blob/bcbbb18/chain-api/src/types/dtos.ts#L179)

***

### validate()

> **validate**(): `Promise`\<`ValidationError`[]\>

#### Inherited from

[`ChainCallDTO`](ChainCallDTO.md).[`validate`](ChainCallDTO.md#validate)

#### Source

[chain-api/src/types/dtos.ts:145](https://github.com/GalaChain/sdk/blob/bcbbb18/chain-api/src/types/dtos.ts#L145)

***

### validateOrReject()

> **validateOrReject**(): `Promise`\<`void`\>

#### Inherited from

[`ChainCallDTO`](ChainCallDTO.md).[`validateOrReject`](ChainCallDTO.md#validateorreject)

#### Source

[chain-api/src/types/dtos.ts:149](https://github.com/GalaChain/sdk/blob/bcbbb18/chain-api/src/types/dtos.ts#L149)

***

### deserialize()

> **`static`** **deserialize**\<`T`\>(`constructor`, `object`): `T`

#### Type parameters

▪ **T**

#### Parameters

▪ **constructor**: [`ClassConstructor`](../interfaces/ClassConstructor.md)\<[`Inferred`](../type-aliases/Inferred.md)\<`T`, [`ChainCallDTO`](ChainCallDTO.md)\>\>

▪ **object**: `string` \| `Record`\<`string`, `unknown`\> \| `Record`\<`string`, `unknown`\>[]

#### Inherited from

[`ChainCallDTO`](ChainCallDTO.md).[`deserialize`](ChainCallDTO.md#deserialize)

#### Source

[chain-api/src/types/dtos.ts:161](https://github.com/GalaChain/sdk/blob/bcbbb18/chain-api/src/types/dtos.ts#L161)