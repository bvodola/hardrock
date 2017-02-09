---
layout: post
title:  "Create your first Meteor 1.4 Project"
date:   2017-01-18 10:50:00 -0200
categories: meteor
---

It's time to create your first Meteor Project. You need to have Meteor globally installed
on your machine before you can start. So, if you haven't done that, check out the links below:

[Meteor installation process on Windows]({% post_url 2017-01-18-installing-meteor-on-windows %})

[Meteor installation process on MAC and Linux]({% post_url 2017-01-18-installing-meteor-on-mac-and-linux %})

---

Now that we have Meteor globally installed, it's time to create our first Meteor App.

- Open the terminal (cmd on Windows).
- Navigate to the folder where you store your projects (or create one if you haven't)
- Type the following:

`meteor create app-name`

Then, Meteor will start taking care of the project creation. This can take a minute.
After that, run:

`cd app-name`
`meteor npm install`
`meteor`

The first command navigates to the project directory. The second installs
all the project dependencies using npm. The last one runs our project.

When you see the phrase `App running at: http://localhost:3000/` on your terminal, go to [](http://localhost:3000)
and you can see it running.

![First Meteor App](/assets/meteor-first-app.png)
