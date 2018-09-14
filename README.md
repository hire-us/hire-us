# We're ready for new opportunities.

Our project is going to be closed but we are well-established team with great processes and we're ready to work on all together on new projects.

Who we are:

* Fully remote team (6 frontend, 2 backend, 1 designer, 1 QA, 1 BA)
* We're doing React and React Native better than most teams
* We're not only doing React Native, but we have people with appropriate mobile backgrounds
* We have fully automated CI/CD pipelines
* We know how to write e2e tests that will run on all platforms (web, ios, android)
* We know how to do backend things with python and have 10+ years experience in it
* We're doing monitoring. We have distributed tracing for microservices


What do we want:

* Ideally we want to survive as a team. Distributed and remote
* We're ready to join other company that might be interested in it
* We can work as contractors
* If you're interested in some particular member - feel free to contact them directly. Everyone has no obligations and is available for hiring.


## Our team details

Office - is person ready to work from office. If no - remote only

Relocate - is person ready to relocate.


| Name | Linkedin | Github | Possible Roles | English level | Office / Relocate | Home Location |
| - | - | - | - | - | - | - |
| ![Igor Kozlovsky](img/Igor.png)<br>Igor Kozlovsky | [Go to profile](https://www.linkedin.com/in/igor-kozlovsky-9017a1b3/) | [Github](https://github.com/igor-lemon) | React<br>React-Native<br>Team Lead<br>Tech Lead | Fluent | ✅/❌ | Minsk, Belarus |
| ![Anton Kuznetsov](img/Anton.png)<br>Anton Kuznetsov | [Go to profile](https://www.linkedin.com/in/isnifer/) | [Github](https://github.com/isnifer) | React<br>React-Native<br>Team Lead<br>Tech Lead  | Fluent | ✅/✅ | Moscow, Russia |
| ![Denis Sedura](img/Denis_S.png)<br>Denis Sedura | [Go to profile](https://www.linkedin.com/in/d3n5a/) | [Github](https://github.com/densa) | iOS<br>React-Native<br>React | Fluent | ✅/❌ | Dnepr, Ukraine |
| ![Sergey Zhukov](img/Sergey.png)<br>Sergey Zhukov | [Go to profile](https://www.linkedin.com/in/sergeyzhukov89/) | [Github](https://github.com/sergeyzhukov) | iOS<br>React-Native<br>React | Fluent | ❌/❌ | Samara, Russia |
| ![Dmitry Lesnoy](img/Dmitry.png)<br>Dmitry Lesnoy | [Go to profile](https://www.linkedin.com/in/dmitry-lesnoy-699bbabb/) | [Github](https://github.com/dimok87) | React<br>React-Native | Fluent | ❌/❌ | Minsk, Belarus |
| ![Nick Goryachev](img/Nickolay.png)<br>Nick Goryachev | [Go to profile](https://www.linkedin.com/in/nick-goriachev-92b56964/) | [Github](https://github.com/ngoryachev) | Android<br>React<br>React-Native | Fluent | ❌/❌ | St. Petersburg, Russia |
| ![Ekaterina Kirvel](img/Kate.png)<br>Ekaterina Kirvel | [Linkedin](https://www.linkedin.com/in/ekaterina-kirvel-380756a1/) | N/A |Business Analyst<br>BA Team Lead | Fluent | ❌/❌ | Minsk, Belarus |
| ![Uladzislau Zankevich](img/Uladzislau.png)<br>Uladzislau Zankevich | [Go to profile](https://www.linkedin.com/in/uladzislau-zankevich-142066157/) | N/A | QA | Beginner English | ✅/✅ | Zhitkovichi, Belarus |
| ![Denis Zanakinsky](img/Denis_Z.png)<br>Denis Zanakinsky | [Go to profile](https://www.linkedin.com/in/deniszakalinsky/) | N/A | Design<br>UI<br>UX<br>BA | Fluent | ✅/✅ | Minsk, Belarus |
| ![Artsiom Kaval](img/Artsiom.png)<br>Artsiom Kaval | [Go to profile](https://www.linkedin.com/in/artyomkoval/) | [Github](https://github.com/lezeroq) | Backend<br>Python<br>Team Lead<br>Tech Lead | Fluent | ✅/✅ | Minsk, Belarus |
| ![Kirill Pinchuk](img/Kirill.png)<br>Kirill Pinchuk | [Go to profile](https://www.linkedin.com/in/cybergrind/) | [Github](https://github.com/cybergrind/) | Backend<br>Python<br>React<br>Team Lead<br>Tech Lead<br>Solutions Architect | Fluent | ✅/✅ | Minsk, Belarus |

You may have question why so many `Team Leads` here, that's because we all know how good team should be built and what is important to organize work.

### Language situation

We intentionally built a team with all Russian speakers to eliminate communication barriers.

But most of the team have daily experience in writing and verbal communications in English. All our documents in English, code comments, apparently, too.


# About processes

## What you can expect from us

We have a full development cycle, only business requirements and acceptance criteria needed from you.

1. You have some business requirement
2. Our BA will start gathering requirements and assemble everything in the document
3. A designer will prepare and provide all visual artifacts
4. You will approve document/media if you want
5. Backend team will develop and fill all API endpoints into the document
6. Frontend team will add required components and connect it to the backend
7. QA will test and prepare release version
8. Changes will be deployed to test and then production environments

After that we run retrospective and make changes in processes if required.

When we decide to change something, we can implement changes. About it subsection below.

## Automation

We love to automate things. Especially management and communications routine!

We're quite good at tracking time. Most of team worked via upwork and we have custom project to collect everything together via jira/gitlab/upwork APIs. So you can get details for each task, each member time report or daily team report. Everything you might need to understand current state.

Also we have review cycle that is fully automated and bot-driven, so there is no lag in code review.


# Our project setup

We used to develop and support 7 applications for IOS and Android, admin site and backend with **weekly** sprints and releases. We're able to do this only because of processes and testing everything.

## Mobile apps

Links may die in future but still alive:

[Appstore](https://itunes.apple.com/us/app/calvert-woodley/id1325616215mt=8)

[Google Play](https://play.google.com/store/apps/detailsid=com.tipsi.cw&hl=en)


Just think about it: 7 apps * 2 platforms * 2 active OS versions = at least 14 fully working applications were required to deliver on every week and 28 to test.

RN isn't particularly mature or stable library and we couldn't afford hordes of QA specialists. So we did all kind of tests (unit, integration, e2e) to make sure that everything is ok.

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


## Infrastructure

Everything was deployed to AWS. Nothing special here: ec2, rds (postgresql), s3. Host setup with ansible.

Some compute intensive things was hosted on hetzner: ELK stack, OSX VM's, Android emulators. We were able to keep our bills sane due to this segregation.

We know how to run e2e tests on OSX in KVM. It gives us the ability to run tests for Android and IOS on the same machine.

GitlabCI was our main CI server. But we have experience with TravisCI for public repos (including mobile e2e tests). And almost every task that can be automated was automated: running test, running integration tests, building documentation, automated deployments.

For example if you need an single page application, you will get not only designs and page itself. But full pipeline: commit -> docker container -> tests -> (optionally) deployment to production.
