Ansible Playbooks Skeleton
--------------------------
Use submodules for your own roles:

``
git submodule add git@somewhere:ansible-role-name.git roles/name
```

Rather than polluting the site.yml with everything, split it out into individual
YAML files in assignments, and include those in all.yml in that directory.

This makes the whole tree a lot more readable as your project grows.
