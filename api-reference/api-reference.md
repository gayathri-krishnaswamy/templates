# Endpoint name

Method | syntax
----- | ----------
GET | base_url/endpoint/etc.
POST | base_url/endpoint/etc.
DELETE | base_url/endpoint/etc.
PUT | base_url/endpoint/etc.
PATCH | base_url/endpoint/etc.

<!-- Delete this comment after you have replaced the method and syntax above. -->

## Description

<!-- Enter a short description. What is it for, and what can it do? -->

## Parameters

<!-- There are several types of parameters: header parameters, path parameters, and query string parameters. The different parameters are documented separately on the same page and not all endpoints contain each type of parameter -->

### Header Parameters

<!-- Parameters included in the request header usually related to authorization that are common across all endpoints. They are not usually documented for each endpoint. However, if your endpoint requires unique parameters to be passed in the header, they are documented in this section -->

Header Name | Req. | Description | Values
----------- |------|---------------- |------------
Bearer | Y | Access Token | Token values the customer name
Accept | N | Response Format | application/xml or application/json




### Query Parameters


### Body Parameters

Name | type | Req. | Description
---- | ----- | ----- | --------------------
Parameter_one | string | Y |  Stores the customer name
Parameter_two | int  | N | Stores a postal code, like the U.S. ZIP code.

<!-- Replace the two example rows and include rows for all your parameters. -->
<!-- If one of the parameters has a set of sub-parameters, create a table or bulleted list for that, but proceed with caution. If the API is complex, there might be an easier way to do your reference section than writing markup by hand. -->

## Examples

### Request

```HTTP
<!--  A copy-and-paste working request, if possible. Not one with values replaced by their names, such as "ID." -->

```

<!-- Follow with comments to explain what each part of the request is doing -->

### Response

```HTTP
<!--  An actual response returned by this endpoint for the request above.  -->

```

<!-- Write a comment explaining the response, if it would be helpful. For a response with a complicated schema, create a table like the one used above for the request.  -->