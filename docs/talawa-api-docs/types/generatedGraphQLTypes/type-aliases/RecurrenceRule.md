[**talawa-api**](../../../README.md) • **Docs**

***

[talawa-api](../../../modules.md) / [types/generatedGraphQLTypes](../README.md) / RecurrenceRule

# Type Alias: RecurrenceRule

\> **RecurrenceRule**: `object`

## Type declaration

### \_\_typename?

\> `optional` **\_\_typename**: `"RecurrenceRule"`

### baseRecurringEvent?

\> `optional` **baseRecurringEvent**: [`Maybe`](Maybe.md)\<[`Event`](Event.md)\>

### count?

\> `optional` **count**: [`Maybe`](Maybe.md)\<[`Scalars`](Scalars.md)\[`"PositiveInt"`\]\[`"output"`\]\>

### frequency

\> **frequency**: [`Frequency`](Frequency.md)

### interval

\> **interval**: [`Scalars`](Scalars.md)\[`"PositiveInt"`\]\[`"output"`\]

### latestInstanceDate?

\> `optional` **latestInstanceDate**: [`Maybe`](Maybe.md)\<[`Scalars`](Scalars.md)\[`"Date"`\]\[`"output"`\]\>

### organization?

\> `optional` **organization**: [`Maybe`](Maybe.md)\<[`Organization`](Organization.md)\>

### recurrenceEndDate?

\> `optional` **recurrenceEndDate**: [`Maybe`](Maybe.md)\<[`Scalars`](Scalars.md)\[`"Date"`\]\[`"output"`\]\>

### recurrenceRuleString

\> **recurrenceRuleString**: [`Scalars`](Scalars.md)\[`"String"`\]\[`"output"`\]

### recurrenceStartDate

\> **recurrenceStartDate**: [`Scalars`](Scalars.md)\[`"Date"`\]\[`"output"`\]

### weekDayOccurenceInMonth?

\> `optional` **weekDayOccurenceInMonth**: [`Maybe`](Maybe.md)\<[`Scalars`](Scalars.md)\[`"Int"`\]\[`"output"`\]\>

### weekDays?

\> `optional` **weekDays**: [`Maybe`](Maybe.md)\<[`Maybe`](Maybe.md)\<[`WeekDays`](WeekDays.md)\>[]\>

## Defined in

[src/types/generatedGraphQLTypes.ts:2671](https://github.com/PalisadoesFoundation/talawa-api/blob/0e711c6a6b57f55ab5776fc9c8edfc5ebc0b3d70/src/types/generatedGraphQLTypes.ts#L2671)
