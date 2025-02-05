[**talawa-api**](../../../README.md) • **Docs**

***

[talawa-api](../../../modules.md) / [types/generatedGraphQLTypes](../README.md) / ActionItem

# Type Alias: ActionItem

\> **ActionItem**: `object`

## Type declaration

### \_\_typename?

\> `optional` **\_\_typename**: `"ActionItem"`

### \_id

\> **\_id**: [`Scalars`](Scalars.md)\[`"ID"`\]\[`"output"`\]

### actionItemCategory?

\> `optional` **actionItemCategory**: [`Maybe`](Maybe.md)\<[`ActionItemCategory`](ActionItemCategory.md)\>

### allotedHours?

\> `optional` **allotedHours**: [`Maybe`](Maybe.md)\<[`Scalars`](Scalars.md)\[`"Float"`\]\[`"output"`\]\>

### assignee?

\> `optional` **assignee**: [`Maybe`](Maybe.md)\<[`User`](User.md)\>

### assigner?

\> `optional` **assigner**: [`Maybe`](Maybe.md)\<[`User`](User.md)\>

### assignmentDate

\> **assignmentDate**: [`Scalars`](Scalars.md)\[`"Date"`\]\[`"output"`\]

### completionDate

\> **completionDate**: [`Scalars`](Scalars.md)\[`"Date"`\]\[`"output"`\]

### createdAt

\> **createdAt**: [`Scalars`](Scalars.md)\[`"Date"`\]\[`"output"`\]

### creator?

\> `optional` **creator**: [`Maybe`](Maybe.md)\<[`User`](User.md)\>

### dueDate

\> **dueDate**: [`Scalars`](Scalars.md)\[`"Date"`\]\[`"output"`\]

### event?

\> `optional` **event**: [`Maybe`](Maybe.md)\<[`Event`](Event.md)\>

### isCompleted

\> **isCompleted**: [`Scalars`](Scalars.md)\[`"Boolean"`\]\[`"output"`\]

### postCompletionNotes?

\> `optional` **postCompletionNotes**: [`Maybe`](Maybe.md)\<[`Scalars`](Scalars.md)\[`"String"`\]\[`"output"`\]\>

### preCompletionNotes?

\> `optional` **preCompletionNotes**: [`Maybe`](Maybe.md)\<[`Scalars`](Scalars.md)\[`"String"`\]\[`"output"`\]\>

### updatedAt

\> **updatedAt**: [`Scalars`](Scalars.md)\[`"Date"`\]\[`"output"`\]

## Defined in

[src/types/generatedGraphQLTypes.ts:71](https://github.com/PalisadoesFoundation/talawa-api/blob/0e711c6a6b57f55ab5776fc9c8edfc5ebc0b3d70/src/types/generatedGraphQLTypes.ts#L71)
