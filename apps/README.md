# About
I am slowly transitioning my docker containers to using Git as the source of truth for all my Compose files.
This allows for easy integration with Portainer (or similar platforms with GitOps if I decide to switch), so updating
the Compose files in here will automatically trigger a redeployment without any other intervention from me.

You'll notice my path mappings in my containers tend to have ``/mnt/user/`` in them. This is because I'm currently hosting most my stuff on unRaid to make use of their drive/share management features.
Eventually I'll move this info out of the Compose files and into a .env so my compose configurations are more portable.
