# Obtaining Credentials
## Overview
Making API calls to the SgniFlow system requires a user account.

SigniFlow maintains 8 cloud enviroments around the globe, you can sign up for a trial account on any of these servers.

## Cloud Server List

* [Australia Cloud](https://au.signiflow.com)
* [Europe Cloud](https://eu.signiflow.com)
* [South America Cloud](https://latam.signiflow.com)
* [South Africa Cloud](https://flow.signflow.co.za)
* [United States Cloud](https://us.signiflow.com)
* [United Kingdom Cloud](https://uk.signiflow.com)

## Support Contact

Alternativly please reach out to our support desk for assistance with a API Account.

* Email : [support@signiflow.com](mailto:support@signiflow.com?subject=API%20Assistance)
* Support Portal : [Helpdesk](https://helpdesk.signiflow.com/en/support/home)
* Academy : [Online Help](https://www.signiflow.com/academy/)
* Videos : [YouTube](https://www.youtube.com/c/SigniFlow)

## API Token

All API Methods require a [APIToken](reference/SigniFlow-OpenAPI-v1.yaml/components/schemas/TokenField), the Token is retrieved by making a request to the [/Login](../../reference/SigniFlow-OpenAPI-v1.yaml/paths/~1Login/post) Method.

[APIToken](../../reference/SigniFlow-OpenAPI-v1.yaml/components/schemas/TokenField) is set to expire 15 minutes after the last API call has been made, you can test the validity of a token with the [/TokenValidate](../../reference/SigniFlow-OpenAPI-v1.yaml/paths/~1TokenValidate) Method, and Extend the token using [/TokenExtend](../../reference/SigniFlow-OpenAPI-v1.yaml/paths/~1TokenExtend)

