[**talawa-api**](../../../../../README.md) • **Docs**

***

[talawa-api](../../../../../modules.md) / [helpers/event/createEventHelpers/createRecurringEventInstancesDuringQuery](../README.md) / createRecurringEventInstancesDuringQuery

# Function: createRecurringEventInstancesDuringQuery()

\> **createRecurringEventInstancesDuringQuery**(`organizationId`): `Promise`\<`void`\>

Creates instances of recurring events up to a specified date during queries.

## Parameters

• **organizationId**: `undefined` \| `null` \| `string`

The ID of the organization to which the events belong.

## Returns

`Promise`\<`void`\>

## See

Parent file:
- `resolvers/Mutation/createEvent.ts.`
- `resolvers/Query/eventsByOrganizationConnection.ts.`

## Remarks

This function follows these steps:
1. Calculates the date limit up to which recurrence rules are queried and new instances are generated.
2. Retrieves recurrence rules based on the organization ID and their latest instance dates.
3. For each recurrence rule found:
  - Finds the base recurring event to gather data for new instance generation.
  - Determines how many existing instances exist and calculates how many new instances to generate.
  - Generates new instances starting from the latest instance date recorded.
  - Updates the latest instance date for the recurrence rule.

## Defined in

[src/helpers/event/createEventHelpers/createRecurringEventInstancesDuringQuery.ts:32](https://github.com/PalisadoesFoundation/talawa-api/blob/0e711c6a6b57f55ab5776fc9c8edfc5ebc0b3d70/src/helpers/event/createEventHelpers/createRecurringEventInstancesDuringQuery.ts#L32)
