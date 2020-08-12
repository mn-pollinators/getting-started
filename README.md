# Getting Started

This is a guide to setting up a development environment for the Minnesota Pollinators projects, aimed at new students. You may already have some of the necessary programs installed&mdash;if so, you can just skip those steps!

This document draws from prior writeups by [Paul Friederichsen][] and [Prof. Nic McPhee][].

**Table of Contents**

- [Creating a GitHub Account](#creating-a-github-account)
- [Installing Visual Studio Code](#installing-visual-studio-code)
- [Installing `git`](#installing-git)
  - [On Windows](#on-windows)
  - [On a Mac](#on-a-mac)
- [Installing GitKraken](#installing-gitkraken)
- [Installing Node.js](#installing-nodejs)

## Creating a GitHub Account

All of the code for Minnesota Pollinators&mdash;along with its revision history&mdash;is stored on [GitHub][], a website for hosting software projects. To work on Minnesota Pollinators, you'll need to sign up for a GitHub account [here][Sign up for GitHub].

![GitHub's "sign up" page][i:Signing up for GitHub]

You'll want to join the [Minnesota Pollinators][] organization ([Prof. KK Lamberty][] can invite you).

If you're a student at Morris, be sure to sign up for the [GitHub Student Developer Pack][Student developer pack] as well!

## Installing Visual Studio Code

Next, in order to read and write the code, you're going to need a text editor. There are a lot of good options, but the one that we've been using is [Visual Studio Code][], particularly because of its [Live Share][Live share] feature.

![Visual Studio Code][i:VS Code]

## Installing `git`

`git` is a version-control system: it keeps track of all of the changes made to the project, and lets several people work on the same code in parallel.

### On Windows

If you're on Windows, you can go [here][Install git for Windows] to download `git`.

When the installer asks you to choose the default editor, you may want to select Visual Studio Code. Other than that, the default options should be just fine.

![The git installer program on Windows, asking what the default editor should be, with "Visual Studio Code" selected][i:Windows, installing git]

### On a Mac

If you're on a Mac, you can get `git` as part of the Xcode command-line developer tools. Open up Terminal and type `git --version`:

<img width="638" alt="Terminal with the command &quot;git --version&quot; typed" src="https://user-images.githubusercontent.com/56209343/89746736-f0de7000-da80-11ea-9ab5-cf48acd6b5f7.png">

You'll get a pop-up asking you to install the developer tools:

<img width="573" alt="The pop-up window asking if you'd like to install the tools" src="https://user-images.githubusercontent.com/56209343/89746735-f0de7000-da80-11ea-9075-abcefdc23124.png">

If you don't get a pop-up, but instead get a version number like this, that means `git` is already installed.

<img width="682" alt="Terminal showing the command &quot;git --version&quot; and the output &quot;git version 2.24.3 (Apple Git-128)&quot;" src="https://user-images.githubusercontent.com/56209343/89746734-f045d980-da80-11ea-8944-f2b0de3b2ecb.png">

## Installing GitKraken

`git` by itself is very spare, so we've been using it through a program called [GitKraken][]. (This program has a nice chart showing all of the revisions over time.) You can use GitKraken for free, but if you're a Morris student, you have access to the pro version through GitHub's student developer pack.

![The screen GitKraken shows when it first launches][i:GitKraken splash page]

Once you've installed GitKraken, you're going to want to download the Minnesota Pollinators code onto your computer. To do this, click the "Clone a repo" button on the left side of GitKraken, and type in the `git` URL for the project.

(You can find the `git` URL of any repository by going to that repository's page on GitHub and looking under the "Code" dropdown. Here's the `git` URL for Buzz About:)

![The GitHub page for Buzz About, with the "Code" dropdown menu open, showing the title "Clone with HTTPS" and the start of the URL][i:Cloning from GitHUb]

Now, you should be able to see the whole history of the project!

![The screen that GitKraken shows when you've opened a repo][i:GitKraken graph view]

## Installing Node.js

At this point, you should have all of the code for a repository on your computer, but you still don't have a way to compile and run it. For that, you'll need to install Node.js, a JavaScript runtime.

You can download Node.js, along with its associated command-line tools, [here][Node.js]. The LTS (long-term support) version should be fine.

On Windows, you'll be asked if you want to install tools for native modules. We don't have any native modules in this project, but you'll probably want to check that box anyway, in case you want to install any in the future. (Installing tools for native modules may take a while.)

![The Node.js installer asking whether you'd like tools for native modules, with the checkbox checked][i:Windows, installing Node.js]

<!-- Links: -->
[Paul Friederichsen]: https://github.com/floogulinc
[Prof. Nic McPhee]: https://github.com/nicmcphee
[Prof. KK Lamberty]: https://github.com/kklamberty
[GitHub]: https://github.com
[Minnesota Pollinators]: https://github.com/mn-pollinators
[Student developer pack]: https://education.github.com/pack
[Sign up for GitHub]: https://github.com/join
[Visual Studio Code]: https://code.visualstudio.com/
[Live share]: https://docs.microsoft.com/en-us/visualstudio/liveshare/
[Install git for Windows]: https://git-scm.com/download
[GitKraken]: https://www.gitkraken.com/git-client
[Node.js]: https://nodejs.org/

<!-- Images: -->
[i:Signing up for GitHub]:https://user-images.githubusercontent.com/56209343/89746895-bb865200-da81-11ea-9dbc-1779b40768d6.PNG
[i:VS Code]: https://user-images.githubusercontent.com/56209343/89746720-e15f2700-da80-11ea-920e-7219d47b4a83.PNG
[i:Windows, installing git]: https://user-images.githubusercontent.com/56209343/89847231-1040d000-db49-11ea-898b-4ae52f19326c.PNG
[i:GitKraken splash page]: https://user-images.githubusercontent.com/56209343/89746747-ff2c8c00-da80-11ea-9065-4c7b3dbb9f6a.PNG
[i:Cloning from GitHub]: https://user-images.githubusercontent.com/56209343/89918462-aadbf600-dbbf-11ea-9e3a-7abe5fbd3d37.PNG
[i:GitKraken graph view]: https://user-images.githubusercontent.com/56209343/89746748-00f64f80-da81-11ea-85dc-6a7334f18252.PNG
[i:Windows, installing NOde.js]: https://user-images.githubusercontent.com/56209343/89849965-4bde9880-db4f-11ea-8208-d64811844f57.PNG
