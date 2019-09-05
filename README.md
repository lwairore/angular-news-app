# NewsApp
This application is built using two of the most powerful and popular resources, [Angular 8]() and [material design]().

To bring live news articles the application uses HTTP requests to fetch news articles from [News API](https://newsapi.org/).

By consuming the [News API](https://newsapi.org/), the application is able to get the latest live news articles from a range of [*sources*](https://newsapi.org/sources), including BBC News, CNN, TechCrunch, Huffington Post and more, along with different categories, like technology, sports, business, science and entertainment.

## Technologies used.
[Angular 8](https://angular.io/)
- The application extensively uses [Angular 8](https://angular.io/).
- Why Angular ?
    1. To communicate with back-end services over the HTTP protocol by using **HttpClient module** to easily interact with [News API](https://newsapi.org/).
    2. **The model-view-viewmodel**(MVVM). This becomes handy when it comes to binding the remote data that will be stored in objects into the application template, where the component plays the part of the controller/viewmodel and where the template represents the view (Angular template language).
    3. **Single Page Application**(SPA) technology. Loading only the part of a page that needs to be changed to help the application load and perform more quickly and smoothly.

[@Angular/Material Design]() - It's a suitable fit for Angular and to aid the visual aspect of the application and also to make the application responsive. It's also the official material design package for the Angular framework.

[@Angular/Animations](https://angular.io/guide/animations) - To provide the illusion of motion that is HTML elements changing styling over time to make the application more fun and easier to use. 

[@Angular/CDK](https://material.angular.io/cdk) - Component Dev Kit which provides high quality predefined behaviours for components.

[Progressbar](https://github.com/MurhafSousli/ngx-progressbar/blob/master/README_V3.md#installation) - To enhance the user experience by creating a visual animation in the application that convices the user something is happening, since the application is making requests to a remote server. 


This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 8.3.2.

## Development server

For a dev server, run: 
```
$ ng serve
```
Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Build

To build the project, run: 
```
$ ng build
```
The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build. That's 
```
$ ng build --prod
```
