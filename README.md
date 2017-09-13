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

### Linode
Nanobox officially supports deploying apps to [Linode](https://www.linode.com/). You can select Linode as a provider in the Nanobox Dashboard.

- **Adapter Repo**: https://github.com/nanobox-io/nanobox-adapter-linode
- **Contributors**: [@jedgalbraith](https://github.com/jedgalbraith), [@lyondhill](https://github.com/lyondhill)

### Google Compute Engine (GCE) _(Beta)_
Nanobox is testing official support for deploying apps to [Google Compute Engine](https://cloud.google.com/compute/). You can select Google Compute Engine as a provider in the Nanobox Dashboard.

- **Adapter Repo**: https://github.com/nanobox-io/nanobox-adapter-libcloud
- **Contributors**: [@danhunsaker](https://github.com/danhunsaker), [@jjkester](https://github.com/jjkester), [@tylerflint](https://github.com/tylerflint)

### Vultr _(Beta)_
Nanobox is testing official support for deploying apps to [Vultr](https://www.vultr.com/). You can select Vultr as a provider in the Nanobox Dashboard.

- **Adapter Repo**: https://github.com/nanobox-io/nanobox-adapter-libcloud
- **Contributors**: [@danhunsaker](https://github.com/danhunsaker), [@jjkester](https://github.com/jjkester), [@tylerflint](https://github.com/tylerflint)


## Community Integrations

### Proxmox
[Proxmox](https://www.proxmox.com/en/) is an open source cloud solution that allows you to build and manage your own virtual cloud. Proxmox can be used as a custom provider in the Nanobox dashboard.

- **Provider Endpoint**: https://adapter-proxmox.nanoapp.io/api/v1/
- **Documentation**: https://adapter-proxmox.nanoapp.io/
- **Adapter Repo**: https://github.com/danhunsaker/nanobox-adapter-proxmox
- **Contributors**: [@danhunsaker](https://github.com/danhunsaker)

### Ubuntu Server (Single/Standalone)
In those cases where you have hosting with a provider that isn't listed here, but still want to deploy with Nanobox, install this adapter on that server, following the instructions in the documentation, and then connect directly to it when adding it as your provider. The Ubuntu Server provider can be used as a custom provider in the Nanobox dashboard.

- **Provider Endpoint**: https://{your-server-ip}:8000/ _(this adapter is installed on the same server you plan to deploy to)_
- **Documentation**: https://github.com/torfs-ict/nanobox-adapter-ubuntu/blob/master/README.md
- **Adapter Repo**: https://github.com/torfs-ict/nanobox-adapter-ubuntu
- **Contributors**: [@torfs-ict](https://github.com/torfs-ict)

### Google Cloud _(Deprecated)_
This integration is in the works but will allow Nanobox users to deploy to [Google Cloud](https://cloud.google.com/).

- **Provider Endpoint**: *Coming*
- **Documentation**: *Coming*
- **Adapter Repo**: https://github.com/jeffgodwyll/nanobox-googlecloud-adapter
- **Contributors**: [@jeffgodwyll](https://github.com/jeffgodwyll)
