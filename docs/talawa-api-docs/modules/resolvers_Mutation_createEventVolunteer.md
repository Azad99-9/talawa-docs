[talawa-api](../README.md) / [Exports](../modules.md) / resolvers/Mutation/createEventVolunteer

# Module: resolvers/Mutation/createEventVolunteer

## Table of contents

### Variables

- [createEventVolunteer](resolvers_Mutation_createEventVolunteer.md#createeventvolunteer)

## Variables

### createEventVolunteer

• `Const` **createEventVolunteer**: [`MutationResolvers`](types_generatedGraphQLTypes.md#mutationresolvers)[``"createEventVolunteer"``]

This function enables to create an event volunteer.

**`Param`**

parent of current request

**`Param`**

payload provided with the request

**`Param`**

context of entire application

**`Remarks`**

The following checks are done:
1. If the current user exists
2. if the volunteer user exists
3. If the event exists
4. If the group exists
5. If the current user is leader of the group

#### Defined in

[src/resolvers/Mutation/createEventVolunteer.ts:30](https://github.com/PalisadoesFoundation/talawa-api/blob/9fa6a1c/src/resolvers/Mutation/createEventVolunteer.ts#L30)
