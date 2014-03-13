milk
====

ETC cloud API framework project

The Entertainment Technology Center @ the University of Southern California (ETC)
 http://www.etcenter.org/ formally launched “Production in the Cloud,” a new
 project that brings together a core group of key media and cloud-resource leaders
 to develop guidelines and accelerate innovation and adoption of next-gen cloud-based
 content creation, production, and distribution tools and processes. Senior executives
  from the six major studios in coordination with Rackspace, EMC, EVault,
  Front Porch Digital, Google and other cloud companies convened recently to serve
  as governing body to collectively guide this process. The project is looking at the
  life cycle of film and media production, from pre-production collaboration, production,
  post production and through to archiving.

This specific part of the effort is around

* Bringing together various competitive organizations to work on a common goal
* Goal of developing an interoperable cloud framework
* First steps of socializing well underway
* Next important step of creating a prototype was discussed in October
* Now we need to execute on design and implementation

More information go to https://wiki.openstack.org/wiki/Milk

--- 

# Contributing 

## Current Requirements

[git](http://git-scm.com)
[Python3](http://www.python.org)
[pip](https://pypi.python.org/pypi/pip)
[git-review](http://www.mediawiki.org/wiki/Gerrit/git-review)
[Django](https://www.djangoproject.com)
[virtualenv](http://www.virtualenv.org)
[freshen](https://github.com/rlisagor/freshen)

## Links

[GitHub](https://github.com/stackforge/milk)
[Wiki](https://wiki.openstack.org/wiki/Milk)

## To Contribute

1. Create a Launchpad account
 https://login.launchpad.net/+new_account

2. Join the OpenStack Foundation free
 https://www.openstack.org/join
 (Use the email address you plan to use with git for code contributions)

3.  Agree to the the Individual Contributor License agreement:
 https://review.openstack.org/#/settings/
 Look under "Agreements" on the left menu.

4.  Add an SSH public key to your launchpad account
 https://help.launchpad.net/YourAccount/CreatingAnSSHKeyPair

5.  Add the same SSH key to your OpenStack Foundation / Gerrit Identity as well
 https://review.openstack.org/#/settings/
 Look under "SSH Public Keys" on the left menu.

6.  Add the same SSH keys to your GitHub account
 Be sure to configure git on your development machine as well if you haven't already.

    $ git config --global user.name "Firstname Lastname"
    $ git config --global user.email "your_email@youremail.com"

7.  Install git-review. (In addition to python3, and pip3 )

    $ sudo pip install git-review

8. Clone the GitHub project

    $ git clone https://github.com/stackforge/milk

9. Create a branch with a descriptive branch name to make your changes. 

    $ git co -b add_tests

10. Without merging your branch with master, submit it for review with git-review.

    $ git review 

11. Track your contributions
 https://review.openstack.org/#/

12. If necessary manually add a reviewer
 Click on your patch listed from #10 above enter one of the following names or emails in the "Add Reviewer" field, and click add.
 "Sean Robers" <seanrob@yahoo-inc.com>
 "Joshua Kolden" <joshua@studiopyxis.com>


## Development Spin Up...

###Tasks

- [X] Initialize the project in OpenStack and Gerrit.
- [X] Create a git project on GitHub.
- [X] Create first draft Apiary blueprint for ETC ID system API.
- [ ] Establish BDD system, and create initial acceptance tests.
- [ ] Build basic Django server to implement blueprint.
- [ ] Create command line tool to generate asset ID, and publish to server, via API.
 
###How to Get Involved

The basic goals and timeline:
[Milk Wiki](https://wiki.openstack.org/wiki/Milk)

Creating a user ID in the OpenStack review system Gerrit, to submit changes for review _(do not use github pull requests)_:
[Getting Started Lab](http://docs.openstack.org/training-guides/content/operator-getting-started-lab.html) 

