# ExecuteQuery

[Official API](https://api-docs.pipefy.com/reference/overview/Card/)  
[Implemented Class](../Capgemini.Pipefy/ExecuteQuery.cs)

Executes a custom query.

> If you want to better understand how to build custom queries, you can check [our example](custom-query.md), [the official documentation](https://api-docs.pipefy.com/reference/overview/Card/) and try them out in [GraphiQL](https://app.pipefy.com/graphiql).

## Arguments

### &lt;In&gt; Query : string

The query to be executed.

### &lt;Out&gt; Response : JObject

The response from the query.

## Inherited Arguments

### &lt;In&gt; Bearer : string

The Bearer authorization token generated by Pipefy.

### &lt;In&gt; Timeout : int

The timeout limit (in ms) for the request to be completed.

### &lt;Out&gt; Status : string

A brief status message of the result of the action.

### &lt;Out&gt; Success : boolean

True if the action was successful.

---

[All actions](../README.md)