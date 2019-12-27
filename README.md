## To Patch a group of hosts

Run the [patch](https://github.com/geomidas/debian_patch/blob/master/ansible/patch.yml) ansible playbook

## To gather patching status info in Confluence
Run the [confluence_patching_status](https://github.com/geomidas/debian_patch/blob/master/ansible/cunfluence_patching_status.yml) playbook

## Or publish patching status in a web page
Run the [patching_status_page](https://github.com/geomidas/debian_patch/blob/master/ansible/patching_status_pages.yml) playbook 

_This (re)creates a container with a webserver written in go and serves all the patching status info for all your host groups._

Visit the patching status page:

![patching_status_page](https://github.com/geomidas/debian_patch/blob/master/patching_stat.png?raw=true)
