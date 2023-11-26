# Rainfall-Predictor
<h1 class="heading-primary">Rainfall Prediction using Time-series analysis with ARIMA Model</h1>
        <div class="project-cs-hero__info">
          <p class="text-primary">
            Rainfall is the most important factor for agriculture and a prime input for various engineering 
            designs such as hydraulic structures, culverts, canals, storm water sewer and road drainage 
            system. So, it is important to predict this prime source for better usage without any wastage.
            Time series analysis and forecasting has become a major tool in different applications in 
            meteorological phenomena, such as rainfall, humidity, temperature, draught etc. and 
            environmental management fields and so it is used for forecasting the rainfall with the help 
            of one of the most effective approaches for analysing time series data, the model introduced 
            by Box and Jenkins, ARIMA (Autoregressive Integrated Moving Average) Machine 
            Learning Model. Seasonal ARIMA model is used for forecasting monthly rainfall data 
            taken for Bangladesh’ Raj Shahi station for the period of years1970-2016. In this paper, 
            ARIMA (1,0,0) (0,1,1) [12] model was found adequate and this model is used to forecasting 
            the monthly rainfall for the upcoming two - ten years to help decision makers to establish 
            priorities in terms of water demand management and also to provide useful information for 
            water resources planners, farmers and urban engineers to assess the availability of water and 
            create the storage accordingly.
          </p>
        </div>
        <div class="project-cs-hero__cta">
          <a href="https://www.dropbox.com/scl/fi/4bkboew4bk0358zb25m7s/Gesture_Gaming.exe?rlkey=earfygkfny8irf575vfhl3f5j&dl=0" class="btn btn--bg" target="_blank">Live Link</a>
        </div>
      </div>
    </section>
    <section class="project-details">
      <div class="main-container">
        <div class="project-details__content">
          <div class="project-details__showcase-img-cont">
            <img
              src="./assets/png/rainfall-arima.png"
              alt="Project Image"
              class="project-details__showcase-img"
            />
          </div>
          <div class="project-details__content-main">
            <div class="project-details__desc">
              <h3>Project Overview</h3>
              <p>
                A time series analysis performed on the historical rainfall dataset of Bangladesh from 1970 to 
                2016 using ARIMA in R-Studio provides valuable insights into rainfall patterns. Analysis focused on the Rajshahi station in 2007 includes data filtering, conversion to Time Series format and subsequent visualization of historical trends.

Decomposing time series data increases forecast accuracy by addressing underlying trends and seasonality. The ARIMA model, a powerful tool in time series analysis, is used to make the time series stationary and the fitted data is used for forecasting. The result is a robust forecast of precipitation values for the next 4 years, presented with an 85% confidence level.

Visualizations, including time-series charts and forecasts with forecast intervals, offer a comprehensive understanding of historical and expected precipitation patterns. A critical consideration involves adjusting the Y-axis limit to ensure non-negativity of precipitation values. Confidence intervals provide a different view of the uncertainty associated with predicted values.

In conclusion, this time series analysis, incorporating ARIMA modeling, not only sheds light on past rainfall trends, but also equips stakeholders with forecasts essential for effective water resource management and disaster preparedness. A comprehensive approach to data preparation, modeling and visualization contributes to a holistic understanding of climate conditions and facilitates informed decision-making for years to come.
              </p>
              <p>        
                The Time Series Analysis conducted on the Historical Rainfall dataset of Bangladesh (1970-2016)
                 using ARIMA modeling in R-Studio provides valuable insights and forecasts for future rainfall
                  patterns. </p>
                  <p>
                  Here is a breakdown of the implemented analysis and its outcomes:
                </p>
              <h3>Data Preparation:</h3>
              <p>
Filtered data for the year 2007 and the Rajshahi station.
Selected the rainfall attribute and converted values to integer datatype for consistency.</p>
<h3>Time Series Conversion:</h3>
<p>
  Transformed the data into a Time Series format using the ts() function in R.
</p>
<h3>Time Series Plot:</h3>
<p>
Visualized the Time Series plot to understand the historical rainfall patterns.
</p>
<h3>Decomposition:</h3>
<p>
Decomposed the time series data to enhance forecast accuracy, addressing trends and seasonality.
</p>
<h3>ARIMA Model Fitting:</h3>
<p>
Employed the ARIMA model using the arima() function in R to make the time series stationary.
Fitted the time series data into the ARIMA model.
</p>
<h3>Forecasting:</h3>
<p>
Utilized the ARIMA model to predict rainfall values for the next 4 years.
</p>
<h3>Visualization:</h3>
<p>
Autoplot the data fitted in the ARIMA model to showcase the Time Series plot alongside the forecasted values.
Incorporated prediction intervals, indicating the confidence level of the forecasts.
</p>
<h3>Outcome:</h3>
<p>
The forecasted rainfall values for the next 4 years are provided with an 85% confidence level.
Adjusted the Y-axis limit to ensure that rainfall values are non-negative.
</p>
<h3>Conclusion:</h3>
<p>
The Time Series Analysis with ARIMA modeling not only provides a retrospective view of historical rainfall 
patterns but also serves as a powerful tool for forecasting future trends. The confidence intervals 
allow for a nuanced understanding of the uncertainty associated with the predictions. 
This analysis aids in better preparedness for varying climatic conditions, contributing to effective
 water resource management and disaster preparedness in the region.
</p>

