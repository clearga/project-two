# <img src="https://cloud.githubusercontent.com/assets/7833470/10899314/63829980-8188-11e5-8cdd-4ded5bcb6e36.png" height="60"> Project Wayfarer

## Brief

We have been commissioned to build a web app for one of the following clients. 

## Client Contract - Wayfarer (Travel Blog)

This client has commissioned your group to build a travel community, code-named **Project Wayfarer**, for users to share tips (AKA posts) about their favorite locations around the world. The client has provided basic wireframes and user stories. In some cases, these requirements may be vague or incomplete.

- [Wireframes](./wireframes.png)
- [User Stories](./user-stories.md)

## Client Contract - The Lemon Log (Tech Reviews)

This client has commissioned your group to build a tech review site, code-named Lemon Log, where authors of the site can write a and publish posts and users of the site can comment on articles. The client has provided basic wireframes and user stories. In some cases, these requirements may be vague or incomplete.

- [Wireframes](https://git.generalassemb.ly/wc-sei-0119/django-wayfarer/tree/master/tech-review-wrieframes)
- [User Stories](./user-stories-tech-review.md)

## Client Contract - Jobber (Recruiting Events)

This client has commissioned your group to build an app where they can post and promote various recruiting events. Due to COVID-19, events will be held remotely for the time being so special consideration will need to be made for these events. The client has provided basic wireframes and user stories. In some cases, these requirements may be vague or incomplete.

- [Wireframes](https://git.generalassemb.ly/wc-sei-0119/django-wayfarer/tree/master/recruiting-events-wireframes)
- [User Stories](user-stories-recruiting-events.md)

## Process

The client contract consists of three core sprints and four bonus sprints. Each sprint contains a set of user stories. You may not complete all of the sprints within the time period, and that's ok. **The goal is to gain experience working on a development project in a group while navigating a client's feature list.**

**IMPORTANT:** You may not begin a new sprint or start on a bonus without client approval.

You will work in groups of 2-3, assigned by instructors, and we expect you to **pair program** for the majority of the time you're writing code.

During morning scrums and in smaller check-ins throughout the day, clearly communicate your current status and next steps to your teammates. Use a kanban-style scrum board such as **Trello** to organize tasks ([example Trello board](https://trello.com/b/JPdt327u/vagabond)). Update clients at least once per day on progress.

Commit changes at least once for each user story. Put effort into your **design**. Use a CSS framework (e.g. Bootstrap or Materialize), partials, and some custom CSS or Sass/Less.

Work as **git collaborators, build on developer branches, and submit pull requests for approval and merging**.

**Deploy to heroku** to get practice getting the app online. The earlier you resolve deployment, the easier it will be to fix bugs.

**Refactor** your code after each sprint, considering:

- Indentation
- Readability/clarity
- Naming
- Organization
- Commenting
- DRYness

## Questions to Ask Yourselves Each Day

1. **Are you all clear about what the client wants?** Identify vague areas. Seek clarification in any cases where you feel less confident about your interpretation of the client's vision.

2. **What will the UX/UI flow be?** Hammer out any areas of ambiguity in the wireframes

3. **Which models do you need to implement?** Create an ERD for the client to reference.

4. **What are the major milestones that you need to complete?** How can these be turned into tasks that group members can complete in pairs? Where do these milestones overlap and how will those related tasks be managed?

5. **What milestones are you and your group members interested in working on?** How can you effectively delegate the work into pairs so that each group member is interested, challenged, and productive?

## Presentation

Each group will present their project.

Each member of your group should speak for equal parts during your presentation and mention which parts of the project they worked on.

**Your presentation should include:**

- Tour (demo) of your app, ideally deployed on heroku (but not required).
- How did your group approach the requirements? (mention anything unique or creative your group chose to do)
- What was easier than you thought? What was more challenging?
- What is a lesson you will carry forward to working on your next project?
- Shout outs for fellow students!

## Evaluation

You will be evaluated on the following measures:

1. Project workflow

- frequent commits with good commit messages
- cooperative group work including majority of pair programing
- effective use of branches
- planning to avoid excessive merge conflicts
- deliberate approach - routeside-in, logical progress from skateboard to car
- the code is your original code

2. Readability

- to what degree does your app fulfill the user stories?
- code is clean
- follows good naming conventions
- code is free of obvious errors and bugs
- code demonstrates good problem solving
- code is DRY

3. Technical requirements

**Every project must have all of the following requirements met to be considered complete:**

- **Django:** Use Django as the core framework for Python.
- **PostgreSQL:** Use PostgreSQL for your database in development and production.
- **Data Models:** Include at least two data models with associations.
- **Data Validation:** Your application should validate incoming data before entering it into the database.
- **Error Handling:** Forms in your application should also validate data, handle incorrect inputs, and provide user feedback on the client side.
- **Views:** Use **partials** to follow DRY (Don???t Repeat Yourself) development in your views.
- **Home & About Pages:** Create a landing page (homepage) that clearly explains your app's value proposition and guides the user through the "get started" funnel. Create an about page that includes photos and brief bios of your team members.
- **User Experience:** Ensure a pleasing and logical user experience. Use a framework like Bootstrap to enhance and ease your CSS styling.
- **Responsive Design:** Make sure your app looks great on a phone or tablet.
- **Heroku:** Deploy your app to Heroku. Ensure no app secrets are exposed.
- **Github:** Projects must have a minimum of 60 specific commits.
