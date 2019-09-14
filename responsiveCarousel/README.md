# ResponsiveCarousel

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 8.3.4


## Development server
To Run locally follow below steps
1. Git Clone or download the App 
2. run npm install (under CarouselAppRepo\responsiveCarousel folder)
3. run ng serve 
4. browse http://localhost:4200/


##Details about app
  This is Content Carousel with light dark background.
    Functional Description:
       1.This app is responsive carousel with below specifications:
           Breakpoints with Mobile First Approach
           Mobile: 320px-768px
           Tablet: 768-1024px
           Desktop:1024px.
       2.Conditions:
         1.For Mobile View Carousel Image Container and Data Content will be in single column  and will be displayed only in light theme.
         2.For Tablet and Desktop viewport, background will toggle between dark and light theme.
         3.Background will toggle automatically after every 15 seconds.
         4.Used CSS FlexBox So that Items can be placed vertically for mobile view 
         and side by side for tablet & Desktop View.
         6.Indicators are not clickable on mobile view.
         
  
     Technical Approach:

        1.I have selected CSS Flexbox to implement with mobile first approach
         to overcome below technical challenges :-
           a.Display all componets in single column for mobile view 
           b.Display TextContentPanel and Carousel Panel side by side for tablet and desktop view with tricky position Indicator which I have achieved by changing order of components.             
           c. ContentPanel needs to grow to extent of Carousel Panel height dynamically.
           e.Toggle between light and dark background with Light background with No Header and Dark with Header Text.
           d.Used onPush Change Detection for Indicator and Content Components.
  
## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).


## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
