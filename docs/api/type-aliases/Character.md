# Type Alias: Character

> **Character**: `object`

## Type declaration

### id?

> `optional` **id**: [`UUID`](UUID.md)

### name

> **name**: `string`

### system?

> `optional` **system**: `string`

### modelProvider

> **modelProvider**: [`ModelProvider`](../enumerations/ModelProvider.md)

### modelEndpointOverride?

> `optional` **modelEndpointOverride**: `string`

### imageGenModel?

> `optional` **imageGenModel**: [`ImageGenModel`](../enumerations/ImageGenModel.md)

### templates?

> `optional` **templates**: `object`

#### Index Signature

 \[`key`: `string`\]: `string`

### bio

> **bio**: `string` \| `string`[]

### lore

> **lore**: `string`[]

### messageExamples

> **messageExamples**: [`MessageExample`](../interfaces/MessageExample.md)[][]

### postExamples

> **postExamples**: `string`[]

### people

> **people**: `string`[]

### topics

> **topics**: `string`[]

### adjectives

> **adjectives**: `string`[]

### knowledge?

> `optional` **knowledge**: `string`[]

### clients

> **clients**: [`Clients`](../enumerations/Clients.md)[]

### plugins

> **plugins**: [`Plugin`](Plugin.md)[]

### settings?

> `optional` **settings**: `object`

### settings.secrets?

> `optional` **secrets**: `object`

#### Index Signature

 \[`key`: `string`\]: `string`

### settings.voice?

> `optional` **voice**: `object`

### settings.voice.model?

> `optional` **model**: `string`

### settings.voice.url?

> `optional` **url**: `string`

### settings.model?

> `optional` **model**: `string`

### settings.embeddingModel?

> `optional` **embeddingModel**: `string`

### style

> **style**: `object`

### style.all

> **all**: `string`[]

### style.chat

> **chat**: `string`[]

### style.post

> **post**: `string`[]

## Defined in

[packages/core/src/core/types.ts:318](https://github.com/ai16z/eliza/blob/main/packages/core/src/core/types.ts#L318)
