| S.No. | Task                                                        | **Verification**    | Results                                                      |
| ----- | ----------------------------------------------------------- | ------------------- | ------------------------------------------------------------ |
| 1     | Create Postman scripts for 5 Get Requests                   | Response Code       | Status code is 200 for 4 of the requests except one where mistake is injected |
| 2     | Inject an intentional mistake in Get Requests               | Error Response Code | AssertionError: expected response to have status code 200 but got 404 |
| 3     | Create at least one Post request with applicable parameters | Response Code       | Status code is 201. API specifies a 201 response should be returned when a user is created |



See screen shot below for additional results:

![](https://i.imgur.com/5t5aReY.png)