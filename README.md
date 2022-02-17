# Box breaking

It would be nasty to disable sudo and root privileges for other people trying to get on a machine, so here is one attempt to make stuff hard for others.

## Step 1

With sudo, use ```chown (some user):(some user) /etc/sudoers``` to disable access to the sudo command. 

## Step 2

People can go into recovery mode to re-assign permissions for sudoers rather easily, so let's [disable recovery mode next](https://askubuntu.com/questions/186176/how-to-disable-recovery-mode-single-user-mode).

NOTE: This is still a WIP and just a fun project.
