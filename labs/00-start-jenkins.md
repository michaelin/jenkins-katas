# Initial setup

In order for you to work on the Jenkins katas, you
need to have
- a fork of this git repository on your
own Github account.
- a Jenkins server.

Jenkins listens to changes in your repository, so
to avoid being disturbed by other users of the
Jenksins katas all your work will be made in your
personal fork.


## Tasks

- Fork the repository to your own Github account.
- Clone the forked repository on your own machine.

Now you are able to push new changes to your
repository and have Jenkins build them.

> Note: If you do not have a Jenkins server
> provided by the trainer, head over and read
> [how to set Jenkins up](./setup-on-your-own.md)


## Navigate to jenkins, is it working?

You should now be able to navigate to your Jenkins
instance! Go to `http://<your-hostname>:8080` and
you will be presented with a screen like the one
below. If you're trying this on you own computer
using docker, you'll use `localhost` as
`<your-hostname>` otherwise for the purpose of
this excercise, use the provided public
hostname/ip.

![Welcome page](../img/welcome2.png)

Click login, and use the username `admin` and your
password.
