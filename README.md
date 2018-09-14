# We're ready for new opportunities.

Our project is going to be closed but we well-established team with great processes and we're ready to work on together on new projects.

Who we are:

* Fully remote team (6 frontend, 2 backend, 1 designer, 1 QA)
* We're doing React and React Native better than most teams
* We're not only doing React Native, but we have people with appropriate mobile backgrounds
* We have fully automated CI/CD pipelines
* We know how to write e2e tests that will run on all platforms (web, ios, android)
* We know how to do backend things with python and have 10+ years experience in it
* We're doing monitoring. We have distributed tracing for microservices


## Linkedin profiles

Name, profile, possbile roles

* Igor Kozlovsky: https://www.linkedin.com/in/igor-kozlovsky-9017a1b3/ React/React Native/Team Lead/Tech Lead
* Anton Kuznetsov: https://www.linkedin.com/in/isnifer/ React/React Native/Tech Lead/Team Lead
* Denis Sedura: https://www.linkedin.com/in/d3n5a/ IOS/React Native/React
* Sergey Zhukov: https://www.linkedin.com/in/sergeyzhukov89/  IOS/React Native/React
* Dmitry Lesnoy: https://www.linkedin.com/in/dmitry-lesnoy-699bbabb/ React/React Native
* Nick Goryachev: TBD Android/React/React Native
* Uladzislau Zankevich: https://www.linkedin.com/in/uladzislau-zankevich-142066157/ QA
* Denis Zanakinsky: https://www.linkedin.com/in/deniszakalinsky/ Design/UI/UX/BA
* Artsiom Kaval: https://www.linkedin.com/in/artyomkoval/ Backend/Python/Team Lead/Tech Lead
* Kirill Pinchuk: https://www.linkedin.com/in/cybergrind/ Backend/Python/React/Team Lead/Tech Lead


You may have question why so many `Team Leads` here, that's because we all know how good team should be built and what is important to organize work.


# Our project setup

We used to develop and support 7 applications for IOS and Android, admin site and backend with **weekly** sprints and releases. We're able to do this only because of processes and testing everything.

## Mobile apps

You can only think about it: 7 apps * 2 platforms * 2 active OS versions = at least 28 fully working applications were required to deliver on every week.

RN isn't particularly mature or stable thing and we couldn't afford hordes of QA specialists. So we did all kind of tests (unit, integration, e2e) to make sure that everything is ok.

All this was built on top of amusing GitlabCI with on-commit and scheduled builds. And uploading to Appstore was just a CI job.

## Backend

We did kanban here. Because kanban is excellent for tiny teams (2 ppl in our case). It is easy to manage priorities, no hustle about sprint's ends/planning, you always know where you have a bottleneck.

We deployed a project on AWS in docker containers with docker-compose.

We are in the absolute love-love relationship with pytest and did all testing for the backend with it.

We had all kind of tests here, unit, integration, e2e, and, obviously, CI for everything. And because of testing, we had several fearless migrations (without breaking production):

* bare metal => docker
* mysql => postgresql
* python2 => python3
* and we always had most recent django and python versions!
