# first-timers-bot

[![Build Status](https://travis-ci.org/hoodiehq/first-timers-bot.svg?branch=master)](https://travis-ci.org/hoodiehq/first-timers-bot)[![Greenkeeper badge](https://badges.greenkeeper.io/hoodiehq/first-timers-bot.svg)](https://greenkeeper.io/)

### 🐶🎯⛳ The Motivation

From our own experiences, we know the process of creating a pull request is the biggest barrier for new contributors.  We wanted to streamline the process to create very simple contributor-friendly issues to help onboard more people to become Open Source contributors for the first time.

At Hoodie, we aim to become the most [welcoming Open Source community possible](http://hood.ie/blog/welcoming-communities.html). We joined forces with initiatives like [First Timers Only](http://www.firsttimersonly.com/) and [Your First PR](http://yourfirstpr.github.io/) to actively reach out to new contributors and create an environment where they feel encouraged and supported.

Creating what we call [starter issues](http://hood.ie/blog/starter-issues.html) is one aspect of that. And it is one of the most successful. A subset of these starter issues are super simple fixes like typos, so they are perfect to onboard people and help them get familiar with GitHub and the pull request workflow. Because typos and similar issues are so trivial, we should basically be able to automatically generate the entire starter issue based on a diff.

### 💡💥❓ How things work

Say I’m a Hoodie contributor and find a typo somewhere. Instead of fixing the issue directly in the master branch or creating a pull request which is time-consuming, I can simply create a new branch that is called something like _first-timers-only-typo-in-title._ GitHub will then notify the **First Timers Bot** about the new branch using Webhooks. The bot is listening to any new branch starting with **first-timers-only** and it will create a new issue on your repo. It is currently setup to the Hoodie repo with a template and assigns the first-timers-only and up-for-grabs labels but can be modified by the developer. The commit body can be used to add some context information and if left empty, the 🤔 **What you will need to know** section of the issue will simply say "Nothing :)".


### 😮🙌👀🎉 Use Our Bot!

First-timers is built with [Probot](https://probot.github.io/).

<table>
    <tr>
        <th>Steps</th>
        <th>Example</th>
    </tr>
    <tr>
        <td>1) <a href="https://github.com/apps/first-timers-bot">Install App</a> on a repo of your choice</td>
        <td><img src="/assets/Install-App.png?raw=true"></td>
    </tr>
    <tr>
        <td>2) Click on the file you want to edit.</td>
        <td><img src="/assets/editPic.png?raw=true"></td>
    </tr>
    <tr>
        <td>3) Make the change and write your commit message under <b>Commit changes</b>.  Make sure to check <i>Create a new branch</i> at the bottom and the branch needs to start with <b>"first-timers-"</b>.</td>
        <td><img src="/assets/Committing-Branch.png?raw=true"></td>
    </tr>
    <tr>
        <td>4) Click on the <b>issues</b> tab and notice your issue was created with your change and commit message. The contributor would then follow the steps on the issue message.</td>
        <td><img src="/assets/Issue-Generated.png?raw=true"</td>
    </tr>
</table>

### 😱🙌😎 Result

[Issue Example Here](https://github.com/arlene-perez/bot-app-test/issues/1)

<p align="center"><img src="/assets/Issue-Done.png"></p>

### Contributors

Thank you to everyone who has helped with this project.
<!-- Contributors START
 Michael_McCombie michaelmccombie https://twitter.com/michaelbuilds design
 Gregor_Martynus gr2m https://twitter.com/gr2m mentor
 Contributors END -->
<!-- Contributors table START -->
| <img src="https://avatars.githubusercontent.com/michaelmccombie?s=100" width="100" alt="Michael McCombie" /><br />[<sub>Michael McCombie</sub>](https://twitter.com/michaelbuilds)<br />🎨 | <img src="https://avatars.githubusercontent.com/gr2m?s=100" width="100" alt="Gregor Martynus" /><br />[<sub>Gregor Martynus</sub>](https://twitter.com/gr2m)<br />👨🏻‍🏫 |
| :---: | :---: |
<!-- Contributors table END -->
This project follows the [all-contributors](https://github.com/kentcdodds/all-contributors) specification.

### 👩‍💻💕About Us
<!-- Contributors START
Angie_Gonzalez agonzalez0515 https://agonzalez0515.github.io
Arlene_Perez techforchange https://github.com/techforchange
Contributors END -->
<!-- Contributors table START -->
| <img src="https://avatars.githubusercontent.com/agonzalez0515?s=100" width="100" alt="Angie Gonzalez" /><br />[<sub>Angie Gonzalez</sub>](https://agonzalez0515.github.io)<br /> | <img src="https://avatars.githubusercontent.com/techforchange?s=100" width="100" alt="Arlene Perez" /><br />[<sub>Arlene Perez</sub>](https://github.com/techforchange)<br /> |
| :---: | :---: |
<!-- Contributors table END -->

Angie and Arlene are LA natives that met while attending Dev Bootcamp in San Francisco.  After bootcamp was over and they were back in LA, they wanted to once again be part of an amazing, welcoming community like DBC was. They found Hoodie through [Rails Girls Summer of Code](https://railsgirlssummerofcode.org/)! This project is extra special for them as it is their first contribution to open source.


### License

[Apache 2.0](http://www.apache.org/licenses/LICENSE-2.0)
