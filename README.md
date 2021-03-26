This is the code for a workshop at RailsConf 2021, see the other workshops on
the program at https://railsconf.com/program/workshops.

# Upgrading Rails: The Dual-Boot Way

Upgrading Rails is easy, right? Sure, as long as you are upgrading your patch
version. A Rails upgrade project for a majestic monolith is not a trivial
project. While upgrades have become easier with every new Rails version, your
application has only become more complicated with every new dependency.

In this workshop you will learn a proven Rails upgrade process which relies
on "dual booting" to quickly iterate and upgrade! You will leave this workshop
with a new set of tools that will make your next upgrade project less daunting.

You can find more details about this workshop over here:
[https://railsconf.com/program/workshops#session-1108](https://railsconf.com/program/workshops#session-1108)

For RailsConf 2021, you'll want to link to the Discord channels that will be used, URLs to come.

## Prerequisites

When participating in this workshop, you will have two options:

- Upgrade your own Ruby on Rails application, or...
- Upgrade our sample Ruby on Rails application

### Prerequisites: Upgrading Your Own Ruby on Rails Application

You should be able to run this commands successfully:

```
bundle install
bundle exec rake test
```

Bonus points:

```
gem install next_rails
```

### Prerequisites: Upgrading our sample Ruby on Rails application

You will need these applications to upgrade our sample application:

- Docker ([Installation Steps on Mac](https://docs.docker.com/docker-for-mac/install/))
- Docker Compose ([Installation Steps](https://docs.docker.com/compose/install/))

After installing Docker and docker-compose, you should be able to run these
commands successfully:

```
git clone git@github.com:fastruby/pecas.git
cd pecas
docker-compose up
```

## Getting Ready

Go to [https://fastruby.io/rails-conf-2021-upgrade-workshop](https://fastruby.io/rails-conf-2021-upgrade-workshop)
and follow the prerequisites section.

If you joined late, you should be able to see the section we are in by reading
the footer in the slides. Hopefully you can catch up with the rest of us!
