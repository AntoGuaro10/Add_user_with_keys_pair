# Add_user_with_keys_pair
This is a template of a playbook you can use to add a new user to an existing VM

I created this playbook to automate my job in creating a specific user into a lot of VMs and different environment.
I've used jinja2 templating so you can be more flexible and you can customize it in order to optimize your workflow.

## NOTE

In the final task, I'm adding the user to the *sudoers.d/waagent* because I've used Azure for provisioning the VMs. Obviously you can easily decide to grant sudo privilegies to your users or not.

Please feel free to comment this playbook and contribute to develop it, if you'll find it useful.
