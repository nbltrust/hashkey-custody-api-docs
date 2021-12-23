# Errors

The Hashkey Prime API uses the following error codes:


Error Code | Meaning
---------- | -------
10001 | Bad Key -- Your API key is wrong.
10002 | Bad Sign -- Your API signature is wrong.
10003 | Bad Timestamp -- Your API timestamp is wrong.
10004 | Repeated Nonce -- Your API nonce was given before.
10005 | Bad Params -- Your request parameters is invalid.
10006 | Internal Server Error -- We had a problem with our server. Try again later.
10007 | API Closed -- We don't provide the API anymore.
10008 | API Suspended -- The function has been suspended currently.
10009 | Request Timeout -- Request the 3rd platform timeout.
20001 | Not Found -- The specified resource could not be found.
20002 | Not Enough -- The wallet balance isn't enough.
20003 | Repeated Request -- The specified resource has existed.
20005 | Too Small -- The amount is too small.
20007 | Forbidden -- The API is hidden for the user.
20008 | In Blacklist -- The request address in the blacklist.
20009 | Not In Whitelist -- The request address not in the whitelist.
20010 | Not In Package -- The package don't support this feature. Please upgrade the package.
20011 | Hour Limit -- The request hit the hour limit of order.
20012 | Day Limit -- The request hit the day limit of order.
20013 | Transaction Limit -- The request hit the transaction limit of order.
20014 | AML Closed -- The AML service had been closed.
20015 | Not In AML Asset List -- The asset isn't supported by AML service.
20016 | Not Authorization -- The user not authorization.
20017 | Token expired -- The user token expired. Please refresh.