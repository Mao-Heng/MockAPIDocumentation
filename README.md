# WeatherReport
This endpoint provides the weather forecast for the next hour of a specific city in the US.

### Endpoint
weatherreport/{cityname}

### Parameters
| Parameter name  | Required/Optional | Description                         |
| --- | --- | --- |
| {cityname} | Required | The name of the city you want to look up | 
| temperature   | Optional  | If you include temperature, the response will include the predicted temperature (in Fahrenheit). |
| precipitation | Optional  | If you include precipitation, the response will include the chance for precipitation. |

### Response
| Response name  | Description                         | Type |
| --- | --- | --- |
| forecast | The predicted weather forecast of the chosen city for the next hour. | String  |
| temperature | The predicted temperature (in Fahrenheit) of the chosen city for the next hour. | Integer | 
| precipitation | The predicted chance of precipitation in the chosen city for the next hour. | Integer |

### Example Request


### Example Response
