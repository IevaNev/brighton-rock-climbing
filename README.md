# [brighton-rock-climbing](https://ievanev.github.io/brighton-rock-climbing)

Developer: Ieva Zdaneviciute ([IevaNev](https://www.github.com/IevaNev))

[![GitHub commit activity](https://img.shields.io/github/commit-activity/t/IevaNev/brighton-rock-climbing)](https://www.github.com/IevaNev/brighton-rock-climbing/commits/main)
[![GitHub last commit](https://img.shields.io/github/last-commit/IevaNev/brighton-rock-climbing)](https://www.github.com/IevaNev/brighton-rock-climbing/commits/main)
[![GitHub repo size](https://img.shields.io/github/repo-size/IevaNev/brighton-rock-climbing)](https://www.github.com/IevaNev/brighton-rock-climbing)

This website was developed to serve as the digital front for a fictional indoor climbing gym "Brighton Rock Climbing" providing user friendly platform to showcase the services, contact information and a booking form to book a climbing session. The goal is to deliver a responsive, accessible and informative experience for visitors, with an emphasis on usability and clear navigation. This README outlines the website's purpose, core features and the technical stack.

## UX

### The 5 Planes of UX

#### 1. Strategy

**Purpose**
- Encourage users to join the climbing gym.
- Provide a seamless user experience to keep users informed and engaged.

**Primary User Needs**
- Learn about gym's purpose and events.
- Join the gym and stay updated.
- Access responsive, user-friendly content.

**Business Goals**
- Increase gym's membership.
- Boost participation in events and social media engagement.

#### 2. Scope

**[Features](#features)** (see below)

**Content Requirements**
- Clear, motivational text about the gym's mission.
- Photos showcasing the community.
- Forms for booking session/sign-up.

#### 3. Structure

**Information Architecture**
- **Navigation Menu**:
  - Accessible links in the navbar.
- **Hierarchy**:
  - Clear call-to-action buttons.
  - Prominent placement of social media links in the footer.

**User Flow**
1. User lands on the home page → learns about the gym's mission and services.
2. Navigates to the timetable, contacts and map → sees location and contact info.
3. Call to action buttons on navbar and header → booking form.
4. Signs up via the booking page.

#### 4. Skeleton

**[Wireframes](#wireframes)** (see below)

#### 5. Surface

**Visual Design Elements**
- **[Colours](#colour-scheme)** (see below)
- **[Typography](#typography)** (see below)

### Colour Scheme

I used https://imagecolorpicker.com/ to pick colors from one of climbing images used on website. Then added variables in CSS for ease of use troughout developing process.

--primary-color: #154c79; /* blue */
--secondary-color: #cde8f6; /* light blue */


### Typography


- [Inter] (https://fonts.google.com/?query=inter)was used for the primary headers and titles.
- [Noto](https://fonts.google.com/?query=noto) was used for all other secondary text.
- [Font Awesome](https://fontawesome.com) icons were used throughout the site, such as the social media icons in the footer.

## Wireframes

To follow best practice, wireframes were developed for mobile, tablet, and desktop sizes.
I've used [Balsamiq](https://balsamiq.com/wireframes) to design my site wireframes.
Screenshots included in documentation/wireframes.

## User Stories

⚠️ INSTRUCTIONS ⚠️

In this section, list all of your possible user stories for the project. Samples have been provided below using the example walkthrough project for your inspiration. Make sure to adjust to match your own project features!

⚠️ --- END --- ⚠️

| Target | Expectation | Outcome |
| --- | --- | --- |
| As a user | I would like to learn more about the gym (location, hours and amenities) | So that I can decide if I want to visit or sign up. |
| As a user | I would like to book a session. | So that I can make sure there's space available when I visit. |
| As a user | I would like to register my child for a youth prohram. | So that I can plan and prepare accordingly. |
| As an user | I would like to view a gallery of past events | So that I can see photos from previous events. |
| As a user | I would like to see the route updates | So that I can plan my session and challenge myself. |
| As a user | I would like the website to be fully responsive | so that I can easily navigate and access information from my phone, tablet, or desktop. |
| As a user | I would like to see a 404 error page if I get lost | so that it's obvious that I've stumbled upon a page that doesn't exist. |

## Features

⚠️ INSTRUCTIONS ⚠️

In this section, you should go over the different parts of your project, and describe each feature. You should explain what value each of the features provides for the user, focusing on your target audience, what they want to achieve, and how your project can help them achieve these things.

**IMPORTANT**: Remember to always include a screenshot of each individual feature!

⚠️ --- END --- ⚠️

### Existing Features

| Feature | Notes | Screenshot |
| --- | --- | --- |
| Navbar | Featured on all three pages, the full responsive navigation bar includes links to the Logo, Home page, Gallery, and Signup page, and is identical in each page to allow for easy navigation. On the smallest screens, a burger icon is used to toggle the navbar so it doesn't take up too much space. This section will allow the user to easily navigate from page to page across all devices without having to revert back to the previous page via the "back" button. The navbar is also `fixed`, so it stays in view even if the user has scrolled to the bottom of the page. | ![screenshot](documentation/features/navbar.png) |
| Hero Image | The landing includes a photo with text-overlay to allow the user to see exactly which location this site would be applicable to. This section introduces the user to *Love Running* with an eye-catching animation to grab their attention. | ![screenshot](documentation/features/hero-image.png) |
| Club Ethos | The club ethos section will allow the user to see the benefits of joining the *Love Running* meetups, as well as the benefits of running overall. The user will see the value of signing up for the *Love Running* meetups. This should encourage the user to consider running as their form of exercise. | ![screenshot](documentation/features/gym's-ethos.png) |
| Opening times | This section will allow the user to see exactly when the meetups will happen, where they will be located, and how long the run will be (in kilometers). The type of run (trail or road) is also shown, to help runners choose the meetups that best match their preference. This section will be updated as these times change to keep the user up to date. | ![screenshot](documentation/features/schedule.png) |
| Footer | The footer includes links to the relevant social media sites for *Love Running*. The links will open in a new tab to allow easy navigation for the user. The footer is valuable to the user, as it encourages them to keep connected via social media. | ![screenshot](documentation/features/footer.png) |

| Booking page | This page will allow the user to sign up to *Love Running* and start their running journey with the community. The user will be able specify if they would like to take part in road, trail, or both types of running. The user will be asked to submit their full name and email address. | ![screenshot](documentation/features/booking-page.png) |
| Confirmation | The confirmation page will give the illusion that the signup form was submitted successfully to the *Love Running* club. Due to the lack of a database or email system so far, this is a fake confirmation page, and will automatically redirect the user back to the home page after 10 seconds. | ![screenshot](documentation/features/confirmation.png) |
| 404 | The 404 error page will indicate when a user has somehow navigated to a page that doesn't exist. This replaces the default GitHub Pages 404 page, and ties-in with the look and feel of the *Love Running* site by using the standard navbar and footer. | ![screenshot](documentation/features/404.png) |

### Future Features



- **Personalized User Profiles**: Allow users to create accounts where they can track their climbing progress, view personal stats, share their achievements and see their membersip info.
- **Training Plans**: Offer customizable training plans for climbers of all levels (beginner, intermediate, advanced) with notifications and reminders.
- **Event Registration & Payment**: Integrate an option for climbers to register and pay for upcoming events or races directly through the site.
- **Achievements & Badges**: Introduce a gamification system where users earn badges or achievements for reaching milestones (e.g., number of climbs, personal grade achievements, attending events).
- **Interactive Maps**: Display interactive maps where climbers can add their climbs from other locations (e.g. other gyms, bouldering or climbing in nature setting).
- **Live Event Tracking**: Provide real-time tracking for major club events so users can follow along or support friends climbing in real-time.
- **Runner's Blog**: Include a blog section for members to share their climbing experiences, tips, and stories, fostering community engagement.
- **Leaderboards**: Add a feature where users can compare their climbing stats with others in the gym via leaderboards (e.g., hardest route climbed, session times).
- **Weekly Challenges**: Implement monthly climbing challenges or group challenges to keep users motivated and engaged.
- **Social Sharing**: Enable users to share their climbs, achievements, or event participation directly on social media from the site.
- **Club Merchandise Store**: Introduce an online store where users can purchase branded climbing gear like t-shirts, climbing accesories, water bottles.
- **Push Notifications**: Allow users to opt-in for mobile push notifications for schedule updates, new events, or motivational reminders.
- **Member Forums or Groups**: Introduce discussion boards or group chats for climbers to connect, discuss upcoming events, or share training tips.
