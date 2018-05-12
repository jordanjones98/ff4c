# Ff4c

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 6.0.1.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).

# About Project
Firefighters 4 Charity (FF4C) is to let people register, and possibly pay for events.
They want an about page with what they stand for, who they donate to etc, but they also want
a place to sign up for these events that they hold.

## Signup
The best way to sign up would most likely be Facebook, most of these people would
already be coming off of Facebook (where they found the event). We may also be able
to leverge the facebook API to share the event if they want too.

## Events
Events can be individual, or teams teams can consist of 2-x amount of people. This
does pose a difficulty, but with Angular can be easily taken care of. Events also
have basic information like Name, About, Date etc. If someone registers for a team
event, they will have to be logged in, but they can fill in everyone elses name seperately.

## Admin & Reporting
Reporting is going to be a very important part of this application. Admins are going
to need to easily see if people paid, and who registered quickly. This will include
a search to search for users as they come up and look to view their registration.

## Technologies
Angular for the front end
All backend stuff handled in Firebase.
