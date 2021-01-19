# 15 minutes for 6 months

_For early-stage SaaS and consumer startups._

[![Memorable Milestones](https://res.cloudinary.com/m15y/image/upload/v1588977044/su/TJ5G67VHU/kmbjqinsp71vavcdth7j.svg)](https://github.com/instantish/memorable-milestones)

Take **15 minutes** to set up a basic issue tracking system (labels + milestones) you probably won’t have to think about for at least **6 months.**

## Get started

### Creating a new repository

_Want to **create a fresh repo** with these labels and milestones?_

1. Click the green "Use this template" button.

2. To trigger the GitHub Action for the first time, edit the `name` field in `.github/workflows/milestones.yml` to be `"Use weekly Memorable Milestones"`. A small commit triggers the milestone syncing.

That's it! ⚡️

### Using an existing repository

_Want to use the labels and milestones for an **existing repository?**_

1. Copy over the `.github/workflows/milestones.yml` file to your existing repository. You may have to create a `.github` or `.github/workflows` folder if you don't have one. (Files that end in `.yml` in this folder are treated as GitHub Actions).

2. To trigger the GitHub Action for the first time, edit the `name` field in `.github/workflows/milestones.yml` to be `"Use weekly Memorable Milestones"`. A small commit triggers the milestone syncing.

3. Add [the labels from this project](https://github.com/instantish/15-minutes-for-6-months/labels) to your repository manually. Unfortunately, this is currently the fastest way 🐢.

That's it! ⚡️

## What does this do?

This will trigger actions that put your labels and milestones on auto-pilot.

The **milestones** are weekly sprints, created 7-8 weeks out, and due every Thursday. The GitHub Action will create them ahead of time and close them when they're done. [Read the methodology.](https://github.com/marketplace/actions/memorable-milestones)

The **labels** are a simple set of tags meant for private projects. Colors and names are determined to be memorable, simple, and accessible. Inspired by [this research paper](https://t.co/Th3xuoC02R?amp=1) on colour theory.


![Labels](https://res.cloudinary.com/m15y/image/upload/v1591145194/su/TJ5G67VHU/d8dcsnbio3ih1xyjkmf2.png)

![Milestones](https://res.cloudinary.com/m15y/image/upload/v1598812855/su/T0SNQGHNY/he1ki7bcwqqstcgf38b3.png)

## Advanced

### Using this as the default repository template for your organization

_Want to make it easy for **members of your org** to use this template when they create a new repo?_

1. Click the "Fork" button in the top right.

![Fork](https://res.cloudinary.com/m15y/image/upload/v1611083611/su/T0SNQGHNY/u7dugahiy2nqnpnozctb.png)

2. Choose which org you'd like to fork the repo to.

3. You're done!

![Done](https://res.cloudinary.com/m15y/image/upload/v1611083612/su/T0SNQGHNY/tkoqncwowrxeln6rm6q9.png)

When someone creates a new repo, this template will come up as an option.

![Choose repo](https://res.cloudinary.com/m15y/image/upload/v1611083611/su/T0SNQGHNY/ympaehq7cowecmmg5uzn.png)


_Have questions? Email us at hi@itsinstantish.com and we'll be happy to help!_

_And if you'd like to track issues in Slack, check out [Instantish](https://itsinstantish.com)._
