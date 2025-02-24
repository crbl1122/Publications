# Publications
**Multi-Step-Ahead Simultaneously Forecasting For
Multiple Time-Series, Using Truncated Singular Value
Decomposition (SVD)**

Abstract:
Purpose: Time series forecasting remains a challenging task across many application fields despite extensive work done in this domain [6–7]. The purpose of this paper is to propose a scalable and efficient method which simplifies multi-step-ahead simultaneous forecasting of large number of time-series. The method proposed here seek to improve the efficiency and
accuracy of multi-step-ahead forecasting over medium/long term forecast horizons performed simultaneously in one go, for a large number of time-series. The method proposed in this work is also exemplified for a store-item forecasting application in retail domain.
The proposed method uses Truncated Singular Value Decomposition at its core, to extract the dominant correlations of multiple time-series stored in a matrix. It is shown that a very small number of components extracted (sometime even as low as one or two right singular vectors), might be sufficient to simultaneously forecast hundreds or more time series through their dominant correlations. After the main components are extracted, the forecast is made only on truncated right singular vectors matrix which encodes the time-bound evolution of the underlying structure of the data, using a standard time-series stochastic forecasting method like Holt-Winter Triple Exponential Smoothing. In a subsequent final step, the original matrix is recomposed. The recomposed matrix will contain both the reconstructed history approximation and predicted values for each original time-series. As such by modeling only few dominant correlations of the entire set, it can be simultaneously generated forecasts for very large number of time series.
Benefits: The method is scalable, accurate, more processing time efficient than individual time-series forecasting and can be used to forecast very large number of time-series simultaneously.

https://medium.com/@florian.cartuta_89235/multi-step-ahead-simultaneously-forecasting-for-multiple-time-series-using-truncated-singular-45de71e77468
