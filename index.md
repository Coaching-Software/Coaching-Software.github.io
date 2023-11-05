# "Coaching App"

### Website Purpose
This site will be used to catalog links and updates on the progress of the "Coaching App" for Todd Melton.

## Team Introduction
### [Justin Lisoway](https://justinlisoway.github.io/):
I worked one internship in mobile app development as a product tester, and I had continuous communication with the development team. My background is not in CS, but I am in the MS CS program and am developing my software engineering skills. I am familiar with MongoDB, JS, Java, and Python, and I am in a mobile app development class now learning Flutter and Dart.

## Project Overview

In this project, I aim to develop a mobile application for my former swim club. This application will have two different types of users: the coach, and the swimmer.

The first client group (coach) will have a survey screen and a workouts screen. In the survey screen, they can send a new survey to every swimmer, and view past survey data. In the workouts screen, they can view past workouts with metrics (distance, intensity, and duration), view the current workout, and update the current workout for all swimmers to see.

The second group (swimmers) will have a survey screen and a workoutscreen. The survey screen either shows a new unfilled survey, or a message saying they have no new surveys. The workouts screen shows only the current workout.

My techstack will include flutter for frontend and Firebase data management for the backend. I will use the Agile methodology for development with bi-weekly sprints. Each Sprint will conclude with a version of the app that can Demo newly implemented features.

Personally, I have swam competitively for 17 years, the last 7 of which have been scraping at the highest level of competition. Due to this history, I can effectively communicate with the client about the issues he is facing, because I can understand better than other developers the exact problems he is trying to solve. This is an exciting project, because I am able to use over a decade of experience on a topic to create a software product that the vast majority of other developers would have a hard time effectively implementing.

## Sponsor Information

Sponsor: Todd Melton

Mr. Melton is my former swim coach that I will be meeting with on a regular basis to show updates on the app and get continuous feedback. He coached at the Okotoks Mavericks Swim Club for 11 years while I was there and has since started his own online coaching enterprise, which will eventually involve the technology that I am creating for him. He coaches many athletes remotely, and currently lacks a way to efficiently communicate with all of them about their recovery and workouts. Current forms of similar software do not implement “swimming” related metrics. The overarching goal of my app is to fill this need and allow Todd to efficiently send surveys and workouts to all of his swimmers.

## Success Criteria

By the end of the semester, I must deliver an MVP that:

1. Allows a coach to post a swimming workout
2. Allows a group of swimmers to view a swimming workout posted by a coach
3. Allows a coach to survey their athletes on recovery metrics

## Milestones

### Milestone 1: Define User stories, and specify priorities. (October 7)
### Milestone 2: Organize project website and github workflow with a backlog of user stories. (October 7)
### Milestone 3: Wire Framing (October 21)
### Milestone 4: Mockups of all application pages (November 4)
### Milestone 5: Create databases and integrate into mockup pages (November 18)
### Milestone 6: Define User Roles and User authentication using Firebase (November 25)
### Milestone 7: Test Success criteria. Deliver Prototype to the client to test with his athletes (December 2)
### Final Milestone: Continue improving the design of the app based on any client test feedback (End of Semester)

## Usage

When you first open the app, you are asked to sign in or register.

<img src="./screenshots/sign-in.png" width="25%">
<img src="./screenshots/register.png" width="25%">

Currently, only valid email addresses that are in the database will allow a user to signin. After signing in for the first time, the user is prompted to select their role.

<img src="./screenshots/select-role.png" width="25%">

After selection, they are taken to the respective version of the app. There is no way to change a user role in the app after its been initially selected. Upon each sign in thereafter, the user is automatically taken to their respective version of the app without asking for a user role.



Coach App:

Coaches are shown this home view with tabs for home, history, and settings.

<img src="./screenshots/coach-home.png" width="25%">

The new workout button shows a create workout screen.

<img src="./screenshots/create-workout.png" width="25%">

The new survey button shows a send survey screen.

<img src="./screenshots/send-survey.png" width="25%">

The history tab shows a page to view all historical workouts and survey data.

<img src="./screenshots/coach-history-workout.png" width="25%">

Clicking on a workout displays its details.

<img src="./screenshots/workout-preview.png" width="25%">

The survey history will show today's survey statistics and an option to see individual responses for each historical survey. This feature is not implemented yet as it requires intense integration with each database collection, and these collections are not yet complete.

<img src="./screenshots/survey-stats.png.png" width="25%">

The settings tab simply gives an option to change your name in the app and logout.

<img src="./screenshots/settings.png" width="25%">



Athlete App:

Athletes are shown this home view with tabs for workouts, survey, and settings.

<img src="./screenshots/athlete-current-workouts.png" width="25%">

Clicking on a workout shows its details, similar to a coaches preview shown above. These workouts can be dismissed by sliding them off the screen after completion. The gesture will update the user database to permanently delete the user's view of completed workouts.

<img src="./screenshots/slide-to-dismiss.png" width="25%">
<img src="./screenshots/athlete-current-workouts-2.png" width="25%">

The survey tab shows a screen to submit today's survey. If athlete's coach did not send a survey or if the athlete has already submitted the given survey, then a corresponding message will be shown instead of the option to submit.

<img src="./screenshots/athlete-current-survey.png" width="25%">

Finally, the settings page is identical for coaches and athletes at this point.


## Repository

[Newest Repository](https://github.com/Coaching-Software/app)

To run this code, clone the main branch of the repository to your local machine and invoke 'flutter run' on the app directory. You may also need to first install flutter and get dependencies (this can be done easily with intelliJ). Note: app is currently mocked-up to look best on the XCODE iOS iPhone 14 simulator.

## [Current Project Board](https://github.com/orgs/Coaching-Software/projects/1/views/1)
