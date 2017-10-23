# OpenWISP - Google Code-In Sample Tasks

## Create a new OpenWISP website theme

Many years have passed since OpenWISP was introduced, it's time to refresh our brand identity and we need help.

We need a simple HTML5+CSS theme (lightweight javascript additions are fine)
with the following features:

- responsive
- readable
- lightweight
- has a design for the homepage
- has a design for simple content pages

We would like the design to convey our commitment to helping creating new networking infrastructure in emerging economies, giving warm and friendly feeling to each new visitor as well as to impress them with our features.

With your help and creativity we can attract younger generation to our community!

- Tags: coding, design, web
- Categories: User Interface, Coding

## Re-design the OpenWISP logo

Many years have passed since OpenWISP was introduced, it's time to refresh our brand identity and we need help.

The best option would be to have a logo that works well in the following forms:

- rectangular shape (like our actual logo)
- square

This way we can use it on webpages as well as stickers and t-shirts!

We don't need a totally new logo, we would like a small variation from the actual one, but we are open for creative proposals :-).

- Tags: logo, design, graphic design, art
- Categories: Outreach / Research

## Design an OpenWISP T-Shirt

Design a T-shirt for OpenWISP users and developers.

The design should feature the OpenWISP logo and a tagline, you can use the front and the back too.

Be creative! Search the web for design inspiration before working on this, but you must submit a completely original design of your own creation that does not use 3rd party images from the web. If you create a design similar to something you found on the web, it is considered a derivative work and you should give proper attribution (i.e., credit) to that author by name with a link to their work. Failure to give credit is plagiarism and can be grounds for dismissal from GCI. When in doubt, design something unique. ;)

Submit a preview image of the t-shirt front and back in PNG format as well as your original artwork files ideally in vector format (e.g., PSD, XCF, SVG, AI, etc).

If you would like credit, please provide your name and join our mailing list to hear if we use your t-shirt design.

Be awesome, be creative, be inspired, be original. ;)

- Tags: logo, design, graphic design, art
- Categories: Outreach / Research

## [ansible-openwisp2] Automatically add the clearsessions command to crontab

The ansible role for openwisp2 (the official way to install OpenWISP 2) should automatically include the command
`./manage.py clearsessions` in a daily cronjob.

See also the [issue #24 in the ansible-openwisp2 repository](https://github.com/openwisp/ansible-openwisp2/issues/24).

- Tags: django, linux, ansible
- Categories: Coding

## [ansible-openwisp2] Add a way to specify a different source for each openwisp2 module

In ansible role for openwisp2 (the official way to install OpenWISP 2), it would be very useful to add a way to specify a different branch or repository for each openwisp2 module installed via **pip** (the **python** package manager) in order to test new features that are being developed in separate branches or in other repositories.

See also the [issue #25 in the ansible-openwisp2 repository](https://github.com/openwisp/ansible-openwisp2/issues/25).

- Tags: python, ansible
- Categories: Coding

## Create an OpenWISP templates repository

OpenWISP 2 has a cool concept called "Templates", you can understand everything about this feature at the following two links:

- [Introduction to OpenWISP 2](https://www.youtube.com/watch?v=MY097Y2cPQ0)
- [Basic Concepts: Templates (netjsonconfig documentation)](http://netjsonconfig.openwisp.org/en/stable/general/basics.html#template)

A templates repository on github would be useful for common configurations like [Eduroam](https://en.wikipedia.org/wiki/Eduroam), Mesh, Roaming and other complex configurations.

A lot of different templates can then be shared by the community and easily imported in OpenWISP using its advanced mode with a simple copy/paste of the [NetJSON](http://netjson.org/) configuration.

Proceed as follows:

- Join the OpenWISP Mailing List and ask us to create the new repository for you
- We will give you write access so you can start working on it
- Create a directory which will contain the templates
- Write instructions in the README containing information like what's the purpose of the repository and how to contribute to the template repository

- Tags: git, github, templates, netjson
- Categories: Coding, Outreach / Research

## Make a video tutorial of how to prepare configurations in OpenWISP 2 from scratch

A videotutorial about the first configuration of a device in Access Point mode could be useful to help the users on the first use of OpenWISP 2.

Proceed as follows:

- show how to create a template with the necessary configuration, flag the template as default
- show how the device automatically registers to OpenWISP 2 and how it will automatically configure itself using the default template prepared earlier
- show how to override the configuration of the template
- show how to use the advanced mode by editing [NetJSON](http://netjson.org) directly

- Tags: video, community, tutorial, netjson
- Categories: Outreach / Research

## Write a blog post about the history and main features of OpenWISP 2

Starting from the currently available online material on OpenWISP 2, write a blog post that introduces the history of OpenWISP 2, its purpose and its main features.

The text has to be in English and at least 1000 words long, and should include links to the documentation, support channels and may embed one existing OpenWISP 2 video from youtube.

- Tags: blogging, documentation, communication
- Categories: Outreach / Research, Documentation

## Install the openwisp-controller module and propose improvements to its README

Star and fork the [openwisp-controller](https://github.com/openwisp/openwisp-controller#installing-for-development) repository, then proceed as follows:

- setup the project on your local machine
- document the challenges faced during installation
- run the development server and check the user interface
- suggest any changes that can be made to user interface in one or more github issues
- send a pull request for each issue with your proposed fix

Don't forget to ask questions via the gitter chat.

- Tags: python, django, git, github
- Categories: Outreach / Research, Documentation, Quality Assurance

## Increase test coverage of django-x509 to at least 95%

Follow the instruction to [install django-x509 and run tests](https://github.com/openwisp/django-x509#installing-for-development), star and fork the repo.

Now run tests using this command: `coverage run --source=django_x509 runtests.py`.

Note down the test coverage score. Find out what that is. You can ask your mentor for guidance!

Now start working on the test suite to increase that score to at least 95% (it's 93% now).

Don't cheat ;-)!

When you are done, send a pull request.

- Tags: python, django, git, testing
- Categories: Quality Assurance, Coding

## Improve OpenWISP 2 installation tutorial

Follow the [OpenWISP 2 Installtion Tutorial](https://github.com/openwisp/ansible-openwisp2#usage-tutorial) (you can install on a virtual box VM, or local linux container) and learn about [ansible](https://www.ansible.com/) basics (what is ansible and what is needed for?) in the process.

Note down at least 2 passages that you find obscure, open an issue and then send a pull request to fix the issues.

Don't forget to star and fork the repository!

Ask your mentors for guidance on how to perform the install process.

- Tags: documentation, ansible
- Categories: Training/Documentation

## Fix django-netjsonconfig issue #62

Fix [django-netjsonconfig issue #62](https://github.com/openwisp/django-netjsonconfig/issues/62)

**Add hostname validator to Device.name**:

**How to reproduce the issue**: try to save a new device with name test device.

**Result**: netjsonconfig validation complains test device is not a valid hostname and the validation error is shown in the configuration section.

**Fix**: it would be better to show this validation error relating directly to the name field.

- Tags: django, python, git
- Categories: Coding

## Create your first pull request

This issue is more about getting familiar with Git and Github. You are required to try out this tutorial at https://try.github.io/levels/1/challenges/1. After doing this exercise locally, create a repository and push code to github. Fork this repo and add your Github link to `/gci/your_name/README.md`

- Tags: easy, Git, Github
- Categories: Coding, Documentation/ Training

## Create your own GPG key, authenticate to GitHub and sign commits

Read about GPG keys and the modern crypto authentication from links like [this](https://www.gnupg.org/)
[Generate your GPG key](https://help.github.com/articles/generating-a-new-gpg-key/) and authenticate it with GitHub. [Tell GitHub](https://help.github.com/articles/telling-git-about-your-gpg-key/) about your key.
Send a basic pull request to this repo at `/your_name/README.md` by signing the commit. Learn about signing [commits](https://git-scm.com/book/en/v2/Git-Tools-Signing-Your-Work)

- Tags: Git, Modern Cryptography, Authentication
- Categories: Coding, Documentation/ Training

## PEP8 guidelines of Python

Learn about [PEP8 guidelines]((https://www.python.org/dev/peps/pep-0008/)) of Python.
Star and clone the repositories of [OpenWISP](https://github.com/openwisp).
Open as many issues as possible and note the issue ids.

- Tags: Python, Codestyle
- Categories: Quality Assurance, Outreach/ Research

## Propose new frontend for django-netjsongraph

[django-netjsongraph](https://github.com/netjson/django-netjsongraph) is a Django package to collect and visualize network topology data. It is being used a lot in openwisp-network-topology.
Star the repository and fork it.
Install it locally by following the setup guide.
Make some test nodes and links and view the network-topology.
Propose one meaningful change in the frontend by opening issues.

- Tags: HTML, CSS, Design, Frontend
- Categories: Coding, Outreach/ Research, User interface

## Make a video showing the features of openwisp-network-topology

[openwisp-network-topology](https://github.com/openwisp/openwisp-network-topology) is the network topology module of OpenWISP2.
Star the repo and install it following the setup guidelines.
You can install it using the [ansible role](https://github.com/openwisp/ansible-openwisp2).
Now, make a video showing all the notable features of openwisp-network-topology.

- Tags: Video, Network topology, Ansible
- Categories: Research/ Outreach, Documentation

## Use Vagrant for OpenWISP modules

Vagrant is used for easing the development process. The documentation can be found from the [official website](https://www.vagrantup.com/)
Read about it and setup vagrant in the following modules:
  * openwisp-controller
  * openwisp-network-topology
  
- Tags: Vagrant, virtual environments
- Categories: Coding, Outreach/ Research

## Screenshots of 2-3 important functionalities

Take screenshots of any 2(preferrably more) functionalities of [django-netjsongraph](https://github.com/netjson/django-netjsongraph) or [openwisp-network-topology](https://github.com/openwisp/openwisp-network-topology) and research on the use cases of these packages.
Add screenshots at relevant places in the README as suggested by your mentor and get them merged.

- Tags: functionality, screenshots
- Categories: Documentation/ Training, Outreach/ Research

## Wireless network communities in your country

Research about the various wireless communities of your country and list them up with their details. Write a small blog of around 700 words in English. Include at least one image of each community and write the story of their success/ failure.

- Tags: Networking, study, communities, case study
- Categories: Outreach/ Research

## Blog about GCI with OpenWISP

Write a blog on your experiences in GCI with OpenWISP, both technical and asthetic. Host it on your blogging platform.

- Tags: marketing, blog
- Categories: Documentation/ Training, Outreach/ Research

## Open design flaws in the OpenWISP website

Check out the OpenWISP [website](http://openwisp.org/). Point out the issues where the design could change or be improved. Open issues at the [issue tracker](https://github.com/openwisp/OpenWISP-Website) of the website.

- Tags: design, analysis, debug
- Categories: Quality Assurance, Documentation/ Training

## Write a user guide to multitenancy in OpenWISP2

Study about multi tenancy. Write a user guide(in English) to multitenancy in OpenWISP2 in about 400 words. Explore all the features and help people know more. You can add images and videos to improve understanding.

- Tags: blog, research, features
- Categories: Outreach/ Research, Documentation/ Training

