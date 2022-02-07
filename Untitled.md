name: String
number: Float!
The overall progress of the cycle. This is the (completed estimate points + 0.25 * in progress estimate points) / total estimate points.

progress: Float!

"""

The total number of estimation points after each day.

"""

scopeHistory: [Float!]!

"""

The start time of the cycle.

"""

startsAt: DateTime!

"""

The team that the cycle is associated with.

"""

team: Team!

"""

Issues that weren't completed when the cycle was closed.

"""

uncompletedIssuesUponClose(

"""

A cursor to be used with first for forward pagination

"""

after: String

"""

A cursor to be used with last for backward pagination.

"""

before: String

"""

[Alpha] Filter returned issues.

"""

filter: IssueFilter

"""

The number of items to forward paginate (used with after). Defaults to 50.

"""

first: Int

"""

Should archived resources be included (default: false)

"""

includeArchived: Boolean

"""

The number of items to backward paginate (used with before). Defaults to 50.

"""

last: Int

"""

By which field should the pagination order by. Available options are createdAt (default) and updatedAt.

"""

orderBy: PaginationOrderBy

): IssueConnection!

"""

The last time at which the entity was updated. This is the same as the creation time if the

entity hasn't been update after creation.

"""

updatedAt: DateTime!

}