# Push API

**The Push API is deprecated and will be removed. The [Messages](messages) endpoint should be used instead. For instructions on how to build an integration, see our [integration guide](developing-integrations).**

Use the Push API to post content to

* [Team Inbox](team-inbox)
* [Chat](chat)

## Authentication

The Push API does not require authentication as a user. In order to push content to a flow, you must know its API Token. To obtain the API Token, go to **Settings -> Team Inbox** inside a flow or open the [Tokens](/account/tokens) page for all your tokens.

## Content-Type

**The Content-Type header must always be specified.** The Push API endpoints support both `application/json` and `application/x-www-form-urlencoded`.
