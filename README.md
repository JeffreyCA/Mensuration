# Mensuration
A simple android app to calculate area, perimeter, volume, etc. of plain &amp; solid objects.

[![Build Status](https://travis-ci.org/idealadarsh/Mensuration.svg?branch=development)](https://travis-ci.org/idealadarsh/Mensuration)

## Description
Mensuration can calculate area, perimeter, circumference and diagonal of different shapes like: square, rectangle, circle, rhombus, trapezium, triangle and parallelogram. Also Curved Surface Area, Total Surface Area, Lateral Surface Area, Volume and diagonal of different solids.

### Features
- Calculate area, perimeter, circumference and diagonal of plain figures.
- Calculate CSA, TSA, LSA, volume and diagonal of solid objects.
- Calculate many more things.



### Branch Policy

 * **development** All development goes on in this branch. If you're making a contribution, you are supposed to make a pull request to _development_. PRs must pass a build check and a unit-test check on Travis.
 
### Code practices

Please help us follow the best practice to make it easy for the reviewer as well as the contributor. We want to focus on the code quality more than on managing pull request ethics.

 * Single commit per pull request
 * Follow uniform design practices. The design language must be consistent throughout the app.
 * The pull request will not get merged until and unless the commits are squashed. In case there are multiple commits on the PR, the commit author needs to squash them and not the maintainers cherrypicking and merging squashes.
 * If the PR is related to any front end change, please attach relevant screenshots in the pull request description.
 
### Join the development

* Before you join development, please set up the project on your local machine, run it and go through the application completely. Press on any button you can find and see where it leads to. Explore. (Don't worry ... Nothing will happen to the app or to you due to the exploring :wink: Only thing that will happen is, you'll be more familiar with what is where and might even get some cool ideas on how to improve various aspects of the app.)
* If you would like to work on an issue, drop in a comment at the issue. If it is already assigned to someone, but there is no sign of any work being done, please feel free to drop in a comment so that the issue can be assigned to you if the previous assignee has dropped it entirely.

## Android App Setup

### Development Setup

Before you begin, you should already have the Android Studio SDK downloaded and set up correctly. You can find a guide on how to do this here: [Setting up Android Studio](http://developer.android.com/sdk/installing/index.html?pkg=studio)

### Setting up the Android Project

1. Download the _mensuration_ project source. You can do this either by forking and cloning the repository (recommended if you plan on pushing changes) or by downloading it as a ZIP file and extracting it.

2. Open Android Studio, you will see a **Welcome to Android** window. Under Quick Start, select _Import Project (Eclipse ADT, Gradle, etc.)_

3. Navigate to the directory where you saved the mensuration project, select the root folder of the project (the folder named "mensuration"), and hit OK. Android Studio should now begin building the project with Gradle.

4. Once this process is complete and Android Studio opens, check the Console for any build errors.

  - _Note:_ If you receive a Gradle sync error titled, "failed to find ...", you should click on the link below the error message (if avaliable) that says _Install missing platform(s) and sync project_ and allow Android studio to fetch you what is missing.

5. Once all build errors have been resolved, you should be all set to build the app and test it.

6. To Build the app, go to _Build>Make Project_ (or alternatively press the Make Project icon in the toolbar).

7. If the app was built successfully, you can test it by running it on either a real device or an emulated one by going to _Run>Run 'app'_ or pressing the Run icon in the toolbar.

## Commit Style Guidelines for Mensuration

### Message Structure
Commit messages consist of three distinct parts, separated by a blank line: the title, an optional body/content, and an optional footer/metadata. The layout looks like this:

type: subject

body

footer

***

### Title
The title consists of the subject and type of the commit message. 

### Type
The type is contained within the title and can be one of the following types:

* **feat:** a new feature
* **fix:** a bug fix
* **docs:** changes to documentation
* **style:** formatting, missing semi-colons, etc; no code change
* **refactor:** refactoring production code
* **test:** adding tests, refactoring test; no production code change
* **chore:** updating build tasks, package manager configs, etc; no production code change

### Subject
The subject is a single short line summarising the change. It should be no greater than 50 characters, should begin with a capital letter and do not end with a period.

Use an imperative tone to describe what a commit does, rather than what it did. For example, use fix; not fixed or fixes or fixing.

For example: 
- fix: Typo in Commit Style guidelines 
- feat: Update UI of SessionDetailsActivity
- fix: Remove deprecated methods
- refactor: API endpoints and JSON assets
instead of writing the following: 
- Fixed bug with Y
- Changing behaviour of X

### Body
The body includes the kind of information commit message (if any) should contain. 

Not every commit requires both a subject and a body. Sometimes a single line is fine, especially when the change is self-explanatory and no further context is necessary, therefore it is optional. The body is used to explain the what and why of a commit, not the how.

When writing a body, the blank line between the title and the body is required and we should try to limit the length of each line to no more than 72 characters.

### The Footer
The footer is optional and is used to reference issue tracker IDs.

## License

This project is currently licensed under the MIT License. A copy of [LICENSE](https://github.com/idealadarsh/mensuration/blob/master/LICENSE) should be present along with the source code.
