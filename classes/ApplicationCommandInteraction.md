[Avocord](../README.md) / [Exports](../modules.md) / ApplicationCommandInteraction

# Class: ApplicationCommandInteraction

## Hierarchy

- [`BaseInteraction`](BaseInteraction.md)

  ↳ **`ApplicationCommandInteraction`**

## Table of contents

### Constructors

- [constructor](ApplicationCommandInteraction.md#constructor)

### Properties

- [client](ApplicationCommandInteraction.md#client)
- [data](ApplicationCommandInteraction.md#data)

### Accessors

- [channelId](ApplicationCommandInteraction.md#channelid)
- [guildLocale](ApplicationCommandInteraction.md#guildlocale)
- [id](ApplicationCommandInteraction.md#id)
- [locale](ApplicationCommandInteraction.md#locale)
- [member](ApplicationCommandInteraction.md#member)
- [message](ApplicationCommandInteraction.md#message)
- [token](ApplicationCommandInteraction.md#token)
- [type](ApplicationCommandInteraction.md#type)
- [user](ApplicationCommandInteraction.md#user)
- [version](ApplicationCommandInteraction.md#version)

### Methods

- [createFollowup](ApplicationCommandInteraction.md#createfollowup)
- [defer](ApplicationCommandInteraction.md#defer)
- [deleteFollowup](ApplicationCommandInteraction.md#deletefollowup)
- [deleteOriginal](ApplicationCommandInteraction.md#deleteoriginal)
- [editFollowup](ApplicationCommandInteraction.md#editfollowup)
- [editOriginal](ApplicationCommandInteraction.md#editoriginal)
- [getFollowup](ApplicationCommandInteraction.md#getfollowup)
- [getOriginal](ApplicationCommandInteraction.md#getoriginal)
- [rawRespond](ApplicationCommandInteraction.md#rawrespond)
- [reply](ApplicationCommandInteraction.md#reply)
- [replyWithModal](ApplicationCommandInteraction.md#replywithmodal)

## Constructors

### constructor

• **new ApplicationCommandInteraction**(`data`, `client`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | [`APIInteraction`](../modules/internal_.md#apiinteraction) |
| `client` | [`Client`](Client.md) |

#### Inherited from

[BaseInteraction](BaseInteraction.md).[constructor](BaseInteraction.md#constructor)

#### Defined in

[src/structures/BaseInteraction.ts:9](https://github.com/avocord/disonejs/blob/0170c9a/src/structures/BaseInteraction.ts#L9)

## Properties

### client

• **client**: [`Client`](Client.md)

#### Inherited from

[BaseInteraction](BaseInteraction.md).[client](BaseInteraction.md#client)

#### Defined in

[src/structures/BaseInteraction.ts:7](https://github.com/avocord/disonejs/blob/0170c9a/src/structures/BaseInteraction.ts#L7)

___

### data

• **data**: [`APIApplicationCommandInteraction`](../modules/internal_.md#apiapplicationcommandinteraction)

#### Overrides

[BaseInteraction](BaseInteraction.md).[data](BaseInteraction.md#data)

#### Defined in

[src/structures/interactions/ApplicationCommandInteraction.ts:8](https://github.com/avocord/disonejs/blob/0170c9a/src/structures/interactions/ApplicationCommandInteraction.ts#L8)

## Accessors

### channelId

• `get` **channelId**(): `undefined` \| `string`

#### Returns

`undefined` \| `string`

#### Inherited from

BaseInteraction.channelId

#### Defined in

[src/structures/BaseInteraction.ts:34](https://github.com/avocord/disonejs/blob/0170c9a/src/structures/BaseInteraction.ts#L34)

___

### guildLocale

• `get` **guildLocale**(): `undefined` \| ``"en-US"`` \| ``"en-GB"`` \| ``"bg"`` \| ``"zh-CN"`` \| ``"zh-TW"`` \| ``"hr"`` \| ``"cs"`` \| ``"da"`` \| ``"nl"`` \| ``"fi"`` \| ``"fr"`` \| ``"de"`` \| ``"el"`` \| ``"hi"`` \| ``"hu"`` \| ``"it"`` \| ``"ja"`` \| ``"ko"`` \| ``"lt"`` \| ``"no"`` \| ``"pl"`` \| ``"pt-BR"`` \| ``"ro"`` \| ``"ru"`` \| ``"es-ES"`` \| ``"sv-SE"`` \| ``"th"`` \| ``"tr"`` \| ``"uk"`` \| ``"vi"``

#### Returns

`undefined` \| ``"en-US"`` \| ``"en-GB"`` \| ``"bg"`` \| ``"zh-CN"`` \| ``"zh-TW"`` \| ``"hr"`` \| ``"cs"`` \| ``"da"`` \| ``"nl"`` \| ``"fi"`` \| ``"fr"`` \| ``"de"`` \| ``"el"`` \| ``"hi"`` \| ``"hu"`` \| ``"it"`` \| ``"ja"`` \| ``"ko"`` \| ``"lt"`` \| ``"no"`` \| ``"pl"`` \| ``"pt-BR"`` \| ``"ro"`` \| ``"ru"`` \| ``"es-ES"`` \| ``"sv-SE"`` \| ``"th"`` \| ``"tr"`` \| ``"uk"`` \| ``"vi"``

#### Inherited from

BaseInteraction.guildLocale

#### Defined in

[src/structures/BaseInteraction.ts:50](https://github.com/avocord/disonejs/blob/0170c9a/src/structures/BaseInteraction.ts#L50)

___

### id

• `get` **id**(): `string`

#### Returns

`string`

#### Inherited from

BaseInteraction.id

#### Defined in

[src/structures/BaseInteraction.ts:14](https://github.com/avocord/disonejs/blob/0170c9a/src/structures/BaseInteraction.ts#L14)

___

### locale

• `get` **locale**(): ``"en-US"`` \| ``"en-GB"`` \| ``"bg"`` \| ``"zh-CN"`` \| ``"zh-TW"`` \| ``"hr"`` \| ``"cs"`` \| ``"da"`` \| ``"nl"`` \| ``"fi"`` \| ``"fr"`` \| ``"de"`` \| ``"el"`` \| ``"hi"`` \| ``"hu"`` \| ``"it"`` \| ``"ja"`` \| ``"ko"`` \| ``"lt"`` \| ``"no"`` \| ``"pl"`` \| ``"pt-BR"`` \| ``"ro"`` \| ``"ru"`` \| ``"es-ES"`` \| ``"sv-SE"`` \| ``"th"`` \| ``"tr"`` \| ``"uk"`` \| ``"vi"``

#### Returns

``"en-US"`` \| ``"en-GB"`` \| ``"bg"`` \| ``"zh-CN"`` \| ``"zh-TW"`` \| ``"hr"`` \| ``"cs"`` \| ``"da"`` \| ``"nl"`` \| ``"fi"`` \| ``"fr"`` \| ``"de"`` \| ``"el"`` \| ``"hi"`` \| ``"hu"`` \| ``"it"`` \| ``"ja"`` \| ``"ko"`` \| ``"lt"`` \| ``"no"`` \| ``"pl"`` \| ``"pt-BR"`` \| ``"ro"`` \| ``"ru"`` \| ``"es-ES"`` \| ``"sv-SE"`` \| ``"th"`` \| ``"tr"`` \| ``"uk"`` \| ``"vi"``

#### Defined in

[src/structures/interactions/ApplicationCommandInteraction.ts:10](https://github.com/avocord/disonejs/blob/0170c9a/src/structures/interactions/ApplicationCommandInteraction.ts#L10)

___

### member

• `get` **member**(): `undefined` \| [`APIInteractionGuildMember`](../interfaces/internal_.APIInteractionGuildMember.md)

#### Returns

`undefined` \| [`APIInteractionGuildMember`](../interfaces/internal_.APIInteractionGuildMember.md)

#### Inherited from

BaseInteraction.member

#### Defined in

[src/structures/BaseInteraction.ts:42](https://github.com/avocord/disonejs/blob/0170c9a/src/structures/BaseInteraction.ts#L42)

___

### message

• `get` **message**(): `undefined` \| [`APIMessage`](../interfaces/internal_.APIMessage.md)

#### Returns

`undefined` \| [`APIMessage`](../interfaces/internal_.APIMessage.md)

#### Inherited from

BaseInteraction.message

#### Defined in

[src/structures/BaseInteraction.ts:38](https://github.com/avocord/disonejs/blob/0170c9a/src/structures/BaseInteraction.ts#L38)

___

### token

• `get` **token**(): `string`

#### Returns

`string`

#### Inherited from

BaseInteraction.token

#### Defined in

[src/structures/BaseInteraction.ts:18](https://github.com/avocord/disonejs/blob/0170c9a/src/structures/BaseInteraction.ts#L18)

___

### type

• `get` **type**(): `InteractionType`

#### Returns

`InteractionType`

#### Inherited from

BaseInteraction.type

#### Defined in

[src/structures/BaseInteraction.ts:26](https://github.com/avocord/disonejs/blob/0170c9a/src/structures/BaseInteraction.ts#L26)

___

### user

• `get` **user**(): `undefined` \| [`APIUser`](../interfaces/internal_.APIUser.md)

#### Returns

`undefined` \| [`APIUser`](../interfaces/internal_.APIUser.md)

#### Inherited from

BaseInteraction.user

#### Defined in

[src/structures/BaseInteraction.ts:30](https://github.com/avocord/disonejs/blob/0170c9a/src/structures/BaseInteraction.ts#L30)

___

### version

• `get` **version**(): ``1``

#### Returns

``1``

#### Inherited from

BaseInteraction.version

#### Defined in

[src/structures/BaseInteraction.ts:22](https://github.com/avocord/disonejs/blob/0170c9a/src/structures/BaseInteraction.ts#L22)

## Methods

### createFollowup

▸ **createFollowup**(`data`): [`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<[`Message`](../modules/internal_.md#message)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | [`WebhookCreateMessageData`](../interfaces/internal_.WebhookCreateMessageData.md) & { `flags?`: `number`  } |

#### Returns

[`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<[`Message`](../modules/internal_.md#message)\>

#### Defined in

[src/structures/interactions/ApplicationCommandInteraction.ts:51](https://github.com/avocord/disonejs/blob/0170c9a/src/structures/interactions/ApplicationCommandInteraction.ts#L51)

___

### defer

▸ **defer**(`data`): [`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<`void`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `undefined` \| [`InteractionCallbackData`](../modules/internal_.md#interactioncallbackdata) |

#### Returns

[`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<`void`\>

#### Defined in

[src/structures/interactions/ApplicationCommandInteraction.ts:32](https://github.com/avocord/disonejs/blob/0170c9a/src/structures/interactions/ApplicationCommandInteraction.ts#L32)

___

### deleteFollowup

▸ **deleteFollowup**(`messageId`): [`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<`void`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `messageId` | `string` |

#### Returns

[`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<`void`\>

#### Defined in

[src/structures/interactions/ApplicationCommandInteraction.ts:65](https://github.com/avocord/disonejs/blob/0170c9a/src/structures/interactions/ApplicationCommandInteraction.ts#L65)

___

### deleteOriginal

▸ **deleteOriginal**(): [`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<`void`\>

#### Returns

[`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<`void`\>

#### Defined in

[src/structures/interactions/ApplicationCommandInteraction.ts:47](https://github.com/avocord/disonejs/blob/0170c9a/src/structures/interactions/ApplicationCommandInteraction.ts#L47)

___

### editFollowup

▸ **editFollowup**(`messageId`, `data`): [`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<[`Message`](../modules/internal_.md#message)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `messageId` | `string` |
| `data` | [`WebhookEditMessageData`](../interfaces/internal_.WebhookEditMessageData.md) |

#### Returns

[`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<[`Message`](../modules/internal_.md#message)\>

#### Defined in

[src/structures/interactions/ApplicationCommandInteraction.ts:61](https://github.com/avocord/disonejs/blob/0170c9a/src/structures/interactions/ApplicationCommandInteraction.ts#L61)

___

### editOriginal

▸ **editOriginal**(`data`): [`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<[`Message`](../modules/internal_.md#message)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | [`WebhookEditMessageData`](../interfaces/internal_.WebhookEditMessageData.md) |

#### Returns

[`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<[`Message`](../modules/internal_.md#message)\>

#### Defined in

[src/structures/interactions/ApplicationCommandInteraction.ts:43](https://github.com/avocord/disonejs/blob/0170c9a/src/structures/interactions/ApplicationCommandInteraction.ts#L43)

___

### getFollowup

▸ **getFollowup**(`messageId`): [`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<[`Message`](../modules/internal_.md#message)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `messageId` | `string` |

#### Returns

[`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<[`Message`](../modules/internal_.md#message)\>

#### Defined in

[src/structures/interactions/ApplicationCommandInteraction.ts:57](https://github.com/avocord/disonejs/blob/0170c9a/src/structures/interactions/ApplicationCommandInteraction.ts#L57)

___

### getOriginal

▸ **getOriginal**(): [`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<[`Message`](../modules/internal_.md#message)\>

#### Returns

[`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<[`Message`](../modules/internal_.md#message)\>

#### Defined in

[src/structures/interactions/ApplicationCommandInteraction.ts:39](https://github.com/avocord/disonejs/blob/0170c9a/src/structures/interactions/ApplicationCommandInteraction.ts#L39)

___

### rawRespond

▸ **rawRespond**(`data`): [`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<`void`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | [`InteractionResponse`](../modules/internal_.md#interactionresponse) |

#### Returns

[`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<`void`\>

#### Inherited from

[BaseInteraction](BaseInteraction.md).[rawRespond](BaseInteraction.md#rawrespond)

#### Defined in

[src/structures/BaseInteraction.ts:46](https://github.com/avocord/disonejs/blob/0170c9a/src/structures/BaseInteraction.ts#L46)

___

### reply

▸ **reply**(`data`): [`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<`void`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `undefined` \| [`InteractionCallbackData`](../modules/internal_.md#interactioncallbackdata) |

#### Returns

[`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<`void`\>

#### Defined in

[src/structures/interactions/ApplicationCommandInteraction.ts:14](https://github.com/avocord/disonejs/blob/0170c9a/src/structures/interactions/ApplicationCommandInteraction.ts#L14)

___

### replyWithModal

▸ **replyWithModal**(`data`): [`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<`void`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `undefined` \| [`InteractionCallbackData`](../modules/internal_.md#interactioncallbackdata) |

#### Returns

[`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<`void`\>

#### Defined in

[src/structures/interactions/ApplicationCommandInteraction.ts:21](https://github.com/avocord/disonejs/blob/0170c9a/src/structures/interactions/ApplicationCommandInteraction.ts#L21)