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

**Apache Beam and Rust: Made for each other**

Apache Beam is an open-source, unified programming model for batch and streaming data processing pipelines that simplifies large-scale data processing dynamics.

Well known advantages of Apache Beam are:

- Can handle batch and streaming data with no need to write different logic separately;

- Portability: the code can be migrated to any supported execution engine (runner).

What happens when a specific part of our data processing pipeline hits the limit and needs to be as fast as possible?

Rust is a systems programming language that has gained significant popularity among developers thanks to its emphasis on exceptional speed, memory safety, and productivity.

Rust was initially created to solve two difficult problems:
- How do you make systems programming safe?
- How do you make concurrency painless?

Beam currently does not support Rust SDK, but it support Python among others like Java, Go, Scala.

Python is currently the go-to programming language for data scientists and engineers.

In this article I show how the fast, safe and efficient Rust language, can be used from a Beam pipeline where an improvement of processing speed is needed. I hope that this article will help others like me which start to explore how can best use Rust in data engineering.

https://medium.com/@florian.cartuta_89235/apache-beam-and-rust-made-for-each-other-2ba73eb48a66
