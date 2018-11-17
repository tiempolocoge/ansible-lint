# Ansible Lint for GitHub Action
This action allows you to run `ansible-lint` with no additional options.

![](./screenshot.png)


## Usage
To use the action simply add the following lines to your `.github/main.workflow`.

```hcl
action "Lint Ansible Playbook" {
  uses = "stoe/actions/ansible-lint@master"
}
```


### Environment Variables
- **ACTION_PLAYBOOK_NAME**: (optional) defaults to `playbook.yml`


## License
The Dockerfile and associated scripts and documentation in this project are released under the [MIT](license).
