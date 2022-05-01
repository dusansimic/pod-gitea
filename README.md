# Gitea pod

Ansible playbook for creating Gitea pod and required containers.

## Variables

Required variables:

| Name | Description |
| - | - |
| publish_address | Publishing address (recommended `127.0.0.1` if using reverse proxy) |
| publish_web_port | Port for publishing the web ui |
| publish_ssh_port | Port for publishing the ssh server |

Required secrets:

| Name | Description |
| - | - |
| db_password | Postgres database password |

For additional variables, check the `gitea` role.
