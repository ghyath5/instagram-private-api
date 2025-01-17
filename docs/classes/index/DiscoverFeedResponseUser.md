[instagram-private-api](../../README.md) / [index](../../modules/index.md) / DiscoverFeedResponseUser

# Class: DiscoverFeedResponseUser

[index](../../modules/index.md).DiscoverFeedResponseUser

## Hierarchy

- [`ProfileEntity`](ProfileEntity.md)

  ↳ **`DiscoverFeedResponseUser`**

## Table of contents

### Constructors

- [constructor](DiscoverFeedResponseUser.md#constructor)

### Properties

- [full\_name](DiscoverFeedResponseUser.md#full_name)
- [has\_anonymous\_profile\_picture](DiscoverFeedResponseUser.md#has_anonymous_profile_picture)
- [is\_private](DiscoverFeedResponseUser.md#is_private)
- [is\_verified](DiscoverFeedResponseUser.md#is_verified)
- [pk](DiscoverFeedResponseUser.md#pk)
- [profile\_pic\_id](DiscoverFeedResponseUser.md#profile_pic_id)
- [profile\_pic\_url](DiscoverFeedResponseUser.md#profile_pic_url)
- [username](DiscoverFeedResponseUser.md#username)

### Methods

- [checkFollow](DiscoverFeedResponseUser.md#checkfollow)
- [checkUnfollow](DiscoverFeedResponseUser.md#checkunfollow)

## Constructors

### constructor

• **new DiscoverFeedResponseUser**(`client`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `client` | [`IgApiClient`](IgApiClient.md) |

#### Inherited from

[ProfileEntity](ProfileEntity.md).[constructor](ProfileEntity.md#constructor)

#### Defined in

[src/core/repository.ts:7](https://github.com/Nerixyz/instagram-private-api/blob/0e0721c/src/core/repository.ts#L7)

## Properties

### full\_name

• **full\_name**: `string`

#### Defined in

[src/responses/discover.feed.response.ts:32](https://github.com/Nerixyz/instagram-private-api/blob/0e0721c/src/responses/discover.feed.response.ts#L32)

___

### has\_anonymous\_profile\_picture

• **has\_anonymous\_profile\_picture**: `boolean`

#### Defined in

[src/responses/discover.feed.response.ts:37](https://github.com/Nerixyz/instagram-private-api/blob/0e0721c/src/responses/discover.feed.response.ts#L37)

___

### is\_private

• **is\_private**: `boolean`

#### Defined in

[src/responses/discover.feed.response.ts:33](https://github.com/Nerixyz/instagram-private-api/blob/0e0721c/src/responses/discover.feed.response.ts#L33)

___

### is\_verified

• **is\_verified**: `boolean`

#### Defined in

[src/responses/discover.feed.response.ts:36](https://github.com/Nerixyz/instagram-private-api/blob/0e0721c/src/responses/discover.feed.response.ts#L36)

___

### pk

• **pk**: `string`

#### Overrides

[ProfileEntity](ProfileEntity.md).[pk](ProfileEntity.md#pk)

#### Defined in

[src/responses/discover.feed.response.ts:30](https://github.com/Nerixyz/instagram-private-api/blob/0e0721c/src/responses/discover.feed.response.ts#L30)

___

### profile\_pic\_id

• **profile\_pic\_id**: `string`

#### Defined in

[src/responses/discover.feed.response.ts:35](https://github.com/Nerixyz/instagram-private-api/blob/0e0721c/src/responses/discover.feed.response.ts#L35)

___

### profile\_pic\_url

• **profile\_pic\_url**: `string`

#### Defined in

[src/responses/discover.feed.response.ts:34](https://github.com/Nerixyz/instagram-private-api/blob/0e0721c/src/responses/discover.feed.response.ts#L34)

___

### username

• **username**: `string`

#### Defined in

[src/responses/discover.feed.response.ts:31](https://github.com/Nerixyz/instagram-private-api/blob/0e0721c/src/responses/discover.feed.response.ts#L31)

## Methods

### checkFollow

▸ **checkFollow**(): `Promise`<[`FriendshipRepositoryChangeResponseFriendship_status`](../../interfaces/index/FriendshipRepositoryChangeResponseFriendship_status.md)\>

#### Returns

`Promise`<[`FriendshipRepositoryChangeResponseFriendship_status`](../../interfaces/index/FriendshipRepositoryChangeResponseFriendship_status.md)\>

#### Inherited from

[ProfileEntity](ProfileEntity.md).[checkFollow](ProfileEntity.md#checkfollow)

#### Defined in

[src/entities/profile.entity.ts:5](https://github.com/Nerixyz/instagram-private-api/blob/0e0721c/src/entities/profile.entity.ts#L5)

___

### checkUnfollow

▸ **checkUnfollow**(): `Promise`<[`FriendshipRepositoryChangeResponseFriendship_status`](../../interfaces/index/FriendshipRepositoryChangeResponseFriendship_status.md)\>

#### Returns

`Promise`<[`FriendshipRepositoryChangeResponseFriendship_status`](../../interfaces/index/FriendshipRepositoryChangeResponseFriendship_status.md)\>

#### Inherited from

[ProfileEntity](ProfileEntity.md).[checkUnfollow](ProfileEntity.md#checkunfollow)

#### Defined in

[src/entities/profile.entity.ts:10](https://github.com/Nerixyz/instagram-private-api/blob/0e0721c/src/entities/profile.entity.ts#L10)
