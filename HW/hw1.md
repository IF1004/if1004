# Homework 1

This homework will prepare you for basic setup for the course.

## Basic course setup (20)

##### Telegram (10)

Properly setting up your Telegram profile by providing a picture will help the teaching staff learn your name. Upload a current headshot picture of you (not anyone else, not a cartoon picture of you, etc.) to your profile. Besides, make sure you have your first and last name as part of your profile.

Telegram channel: <https://t.me/regcin>

##### Github (10)

Sign into [GitHub](https://github.com/).

1. Create a *private* repo called HW1. 
2. Go to Settings, Collaborators and Teams, and add the TAs and instructor as a collaborator (using their unity id).

## Learning Git (20)

Solve the first four levels in: http://pcottle.github.io/learnGitBranching/

![example](https://cloud.githubusercontent.com/assets/742934/9494425/c4dd4b66-4bd3-11e5-9aac-04bfc8fed771.png)

* Introduction Sequence (5%)
* Ramping Up (5%)
* Moving Work Around (5%)
* A Mixed Bag (5%)

For extra credit, complete "Advanced Topics". (5%)

For submission, you only need to demonstrate completing the levels, which can be done taking a screenshot. However, you should keep track of your solutions to help you remember how to solve these types of issues in the future, or recover if your progress gets lost.

## Hooks (20)

Create a local git repository (using `git init`) in a new directory. Create a "post-commit" file in `.git/hooks/`. Inside the file, create a command that will open a web page immediately after a commit is performed to that repo.

Some hints: 
* http://stackoverflow.com/questions/8967902/why-do-you-need-to-put-bin-bash-at-the-beginning-of-a-script-file
* `chmod`
* `start` for windows, `open` for mac/linux

In your solution, provide the content of "post-commit". Finally, take a screencast (20 points), or a gif recording of the process. See details below.

## Concepts (20)

Reading 01: C. Parnin et al., "[The Top 10 Adages in Continuous Deployment](https://github.com/vinicius3w/if1004-DevOps/blob/master/lectures/if1004-2017-2-reading01.pdf)",  in IEEE Software, vol. 34, no. 3, pp. 86-95, May-Jun. 2017.
doi: 10.1109/MS.2017.86

* In your own words, explain the difference between continuous integration, continuous delivery, and continuous deployment.
* How does DevOps team model (e.g., site reliability engineer) differ than a a NoOps team model (e.g. Netflix team)? What differences in architecture allow for a NoOps model?
* Explain the principle of Every Feature is an Expertiment
* Explain the principle of Be Fast to Deploy, Slow(er) to Release.

## Submit

Submit in our Telegram channel, <https://t.me/regcin>, or send in PVT to me a MD file containing the following:

* Complete moodle and slack profiles by deadline (20).
* Screenshot of completed git tutorial (20).
* Hooks (20)
* Screencast (20)
* Concepts (20)

For your screenshot embed in the markdown file of your LOGIN-HW1.md. Include a link to your screencast video/gif. Include your concept answers in your markdown file.

**Due D+7**, 17:00.

## Screencast (20)

### Screencasts/Demo Gifs Guidelines

Here are some guidelines and links for creating good screencasts. It is good to get ready now to learn how to create demo videos for your future project milestones and career.

A general guideline: Do whatever it would do if you were teaching someone how to do something. For example, you don’t have to show people you typing and creating the whole commit, but you might want to show the contents of the hook in a text editor, before doing a commit.
 
##### Software
* camtasia
* https://github.com/justinfrankel/licecap (for simple .gif)
* screencastomatic
* Add more recommendations in Slack
 
##### Guidelines for both multimedia formats:

* Keep the content simple - A regular software engineer without knowing anything about your tool should be able to follow you

##### Guidelines for screencasts (video)

* Mention your name, unity ID and the tool/source code which you will be testing/demoing when you begin
* Use a headset microphone for good quality audio recording.
* Create a script and rehearse that script

##### Guidelines for making a screencast:

* https://wiki.duraspace.org/plugins/viewsource/viewpagesrc.action?pageId=30218666 (also good suggestions for podcasts)
* From http://www.screencast.com/help/tutorial.aspx?id=403
* Practice on screen movements as they can appear jerky when viewing but not as a user.
* Script out complex parts.
* Speak clearly and enunciate, also, have good sound quality.
* Background noise can be distracting.
* From http://diythemes.com/thesis/how-to-create-screencasts/
* Know what you want to present and present it accordingly.
* Organize your thoughts.
* Rehearse such that your casts does not faulter midway.
* Take time to edit your screencast so it does not feel rough around the edges.
 
##### More advice
http://assets.techsmith.com/Docs/pdf-camtasiaStudio/Create_Engaging_Screencasts.pdf

* Know your audience.
* Know what your goals.
* Write a script.
* Examples of good quality screencasts:
* https://peepcode.com/
* http://railscasts.com/
* http://tekpub.com/blogs/tekpub-free-bin
