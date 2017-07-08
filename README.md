# Nanobox Hosting Provider Integrations

## Official Integrations

### AWS
Nanobox officially supports deploying apps to [Amazon Web Services (AWS)](https://aws.amazon.com/). You can select AWS as a provider in the Nanobox Dashboard.

- **Adapter Repo**: https://github.com/nanobox-io/nanobox-adapter-aws
- **Contributors**: [@jedgalbraith](https://github.com/jedgalbraith)

### DigitalOcean
Nanobox officially supports deploying apps to [DigitalOcean](https://www.digitalocean.com/). You can select DigitalOcean as a provider in the Nanobox Dashboard.

- **Adapter Repo**: https://github.com/nanobox-io/nanobox-adapter-digitalocean
- **Contributors**: [@tylerflint](https://github.com/tylerflint)

### Linode _(Beta)_
Nanobox is testing official support for deploying apps to [Linode](https://www.linode.com/). You can select Linode as a provider in the Nanobox Dashboard.

- **Adapter Repo**: https://github.com/nanobox-io/nanobox-adapter-linode
- **Contributors**: [@jedgalbraith](https://github.com/jedgalbraith), [@lyondhill](https://github.com/lyondhill)

## Community Integrations

### Proxmox
[Proxmox](https://www.proxmox.com/en/) is an open source cloud solution that allows you to build and manage your own virtual cloud. Proxmox can be used as a custom provider in the Nanobox dashboard.

- **Provider Endpoint**: https://adapter-proxmox.nanoapp.io/api/v1/
- **Documentation**: https://adapter-proxmox.nanoapp.io/
- **Adapter Repo**: https://github.com/danhunsaker/nanobox-adapter-proxmox
- **Contributors**: [@danhunsaker](https://github.com/danhunsaker)

### Single Server
In those cases where you have hosting with a provider that isn't listed here, but still want to deploy with Nanobox, install this adapter on that server, following the instructions in the documentation, and then connect directly to it when adding it as your provider. Single Server can be used as a custom provider in the Nanobox dashboard.

- **Provider Endpoint**: https://{your-server-ip}:8000/ _(this adapter is installed on the same server you plan to deploy to)_
- **Documentation**: https://github.com/torfs-ict/nanobox-adapter-single-server/blob/master/README.md
- **Adapter Repo**: https://github.com/torfs-ict/nanobox-adapter-single-server
- **Contributors**: [@torfs-ict](https://github.com/torfs-ict)

### Google Cloud _(In Progress)_
This integration is in the works but will allow Nanobox users to deploy to [Google Cloud](https://cloud.google.com/).

- **Provider Endpoint**: *Coming*
- **Documentation**: *Coming*
- **Adapter Repo**: https://github.com/jeffgodwyll/nanobox-googlecloud-adapter
- **Contributors**: [@jeffgodwyll](https://github.com/jeffgodwyll)
