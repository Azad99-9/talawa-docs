[talawa-api](../README.md) / [Exports](../modules.md) / resolvers/Query/helperFunctions/getSort

# Module: resolvers/Query/helperFunctions/getSort

## Table of contents

### Functions

- [getSort](resolvers_Query_helperFunctions_getSort.md#getsort)

## Functions

### getSort

▸ **getSort**(`orderBy`): `undefined` \| ``null`` \| `string` \| [`string`, `SortOrder`][] \| \{ `[key: string]`: `SortOrder` \| \{ `$meta`: `unknown`  \};  \}

#### Parameters

| Name | Type |
| :------ | :------ |
| `orderBy` | `undefined` \| [`InputMaybe`](types_generatedGraphQLTypes.md#inputmaybe)\<``"createdAt_ASC"`` \| ``"createdAt_DESC"`` \| ``"allDay_ASC"`` \| ``"allDay_DESC"`` \| ``"description_ASC"`` \| ``"description_DESC"`` \| ``"endDate_ASC"`` \| ``"endDate_DESC"`` \| ``"endTime_ASC"`` \| ``"endTime_DESC"`` \| ``"id_ASC"`` \| ``"id_DESC"`` \| ``"location_ASC"`` \| ``"location_DESC"`` \| ``"recurrance_ASC"`` \| ``"recurrance_DESC"`` \| ``"startDate_ASC"`` \| ``"startDate_DESC"`` \| ``"startTime_ASC"`` \| ``"startTime_DESC"`` \| ``"title_ASC"`` \| ``"title_DESC"`` \| ``"apiUrl_ASC"`` \| ``"apiUrl_DESC"`` \| ``"name_ASC"`` \| ``"name_DESC"`` \| ``"commentCount_ASC"`` \| ``"commentCount_DESC"`` \| ``"imageUrl_ASC"`` \| ``"imageUrl_DESC"`` \| ``"likeCount_ASC"`` \| ``"likeCount_DESC"`` \| ``"text_ASC"`` \| ``"text_DESC"`` \| ``"videoUrl_ASC"`` \| ``"videoUrl_DESC"`` \| ``"capacity_ASC"`` \| ``"capacity_DESC"`` \| ``"email_ASC"`` \| ``"email_DESC"`` \| ``"firstName_ASC"`` \| ``"firstName_DESC"`` \| ``"lastName_ASC"`` \| ``"lastName_DESC"``\> |

#### Returns

`undefined` \| ``null`` \| `string` \| [`string`, `SortOrder`][] \| \{ `[key: string]`: `SortOrder` \| \{ `$meta`: `unknown`  \};  \}

#### Defined in

[src/resolvers/Query/helperFunctions/getSort.ts:11](https://github.com/PalisadoesFoundation/talawa-api/blob/9fa6a1c/src/resolvers/Query/helperFunctions/getSort.ts#L11)
