# Technical interview - ASP.NET Core with React
A repository to help with technical interviews using a ASP.NET Core backend with React frontend.

## Getting Started
1. Clone this repository
2. Open the solution in Visual Studio or your IDE of choice 
3. Make sure the `Interview` project is set as the startup project
4. Run the application, dependcies will be installed automatically


## About the application 

### Backend 
The backend is setup with .net6. The main point on interest is the `WeatherForecastController.cs` which has an endpoint to provide data to the frontend. 

There is a test project, `InterviewTest` which has a default test in it. 

### Frontend
The frontend application is containted with the `ClientApp` folder. In `ClientApp/src/components` is where you will find what is rendered to the browser when you start the application. 
E.g. `Home.js`, `Counter.js` and `FetchData.js`. 

