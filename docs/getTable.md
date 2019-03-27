# GetTable

[Official API](https://api-docs.pipefy.com/reference/mutations/getTable/)  
[Implemented Class](../Capgemini.Pipefy/TableRecord/GetTable.cs)

Gets detailed information about a Table in Pipefy.

## Arguments

### &lt;In&gt; TableID : string

ID of the Table to be obtained.

You can find this info from the link when accessing it through the web

### &lt;Out&gt; Table : JObject

Table obtained (JObject).

## Inherited Arguments

### &lt;In&gt; Bearer : string

The Bearer authorization token generated by Pipefy.

### &lt;In&gt; Timeout : int

The timeout limit (in ms) for the request to be completed.

### &lt;Out&gt; Status : string

A brief status message of the result of the action.

### &lt;Out&gt; Success : boolean

True if the action was successful.