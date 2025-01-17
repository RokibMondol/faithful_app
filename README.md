# Serverless Shiny App: Faithful Geyser Data Visualization  

This project demonstrates a serverless Shiny application built using R and hosted on GitHub Pages. The app enables users to interactively tweak **ggplot2** options and visualize the impact in real-time. 

![Image](Screenshot_20250110_203952.png)

## Features  
- **Interactive Visualization**: Explore the famous Faithful Geyser dataset with customizable **ggplot2** parameters.  
- **Serverless Architecture**: No dedicated server required. The app runs directly in the browser via GitHub Pages, powered by **shinylive**.  
- **Real-Time Updates**: Changes to plot settings are reflected instantly.  

## Limitations  
Since this is a test application, it is not fully optimized. Additionally, all necessary R libraries are downloaded to the browser at runtime to support the app's serverless operation, which can lead to slower initial load times.   

## Access the App  
[Faithful Geyser Shiny App](https://rokibmondol.github.io/faithful_app/)  

## Built With  
- **Shinylive**: For running Shiny applications directly in the browser without a server.  
- **ggplot2**: For creating elegant and customizable visualizations.  
- **GitHub Pages**: For hosting the serverless app.  

Feel free to explore the app and provide feedback or suggestions for improvements!  
