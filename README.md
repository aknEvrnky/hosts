# Hosts

User contributed notes on various web host that play well or don't play with with Statamic. Send your pull requests, no affiliate links!

## PHP Versions by Host
<http://phpversions.info/shared-hosting/>

## Hosts that play nice

These guys work well with Statamic right out of the box.

- [A Small Orange](http://asmallorange.com)
- [ArcusTech](http://arcustech.com)
- [AWS](https://aws.amazon.com/)
- [Azure](https://azure.microsoft.com/)
- [Cyon](https://www.cyon.ch/) - Switzerland
- [Digital Ocean](https://www.digitalocean.com/) ([One-Click LAMP Stack](https://www.digitalocean.com/features/one-click-apps/))
- [Digital Ocean App Platform](https://www.digitalocean.com/products/app-platform/)
- [Digital Pacific](http://www.digitalpacific.com.au/hosting/) - Sydney, Australia
- [DreamHost](https://www.dreamhost.com/) - [server tweaks needed](https://github.com/statamic/hosts/wiki/Dreamhost-tweaks)
- [Exigo](https://www.exigo.ch/) - Switzerland
- [fortrabbit](https://www.fortrabbit.com/) - US Virgina & EU Ireland, with [install guide for Statamic 3](https://help.fortrabbit.com/install-statamic-3)
- [Google Cloud Platform](https://cloud.google.com/)
- [Hetzner Cloud](https://www.hetzner.com/cloud)
- [HostGator](http://www.hostgator.com/)
- [Internethelden](https://internethelden.io/) - Germany
- [Laravel Forge](https://forge.laravel.com/) + [Linode](http://linode.com)
- [Laravel Forge](https://forge.laravel.com/) + [Digital Ocean](https://www.digitalocean.com)
- [Media Temple (dv)](http://mediatemple.net)
- [Media Temple (grid)](http://mediatemple.net)
- [Metanet](http://www.metanet.ch) - Switzerland
- [MyHost](https://myhost.nz/) – New Zealand & Australia
- [OVH](https://www.ovh.com/fr/index.xml) is a nice web host with 3 main data centers in northeastern France and one near Montreal (Quebec, Canada). It offers PHP 5.5 and 5.4.
- [Panthur](http://www.panthur.com.au/) - Sydney, Australia
- [Ploi](https://ploi.io) + [Linode](http://linode.com)
- [Ploi](https://ploi.io) + [Digital Ocean](https://www.digitalocean.com)
- [Ploi](https://ploi.io) + [Hetzner Cloud](https://www.hetzner.com/cloud)
- [ServInt](https://www.servint.net/)
- [Site5](http://www.site5.com/)
- [SiteHost](https://sitehost.nz/) – New Zealand & Australia
- [Vultr](https://www.vultr.com/) - Worldwide
- [WebFaction](https://www.webfaction.com/)

## Hosts that don't play nice

You should probably avoid these. It doesn't mean it's not possible, but will likely require support tickets to enabled PHP modules like `mcrypt`, `mbstring`, and so on.

- [Go Daddy](http://godaddy.com) - doesn't meet server requirements
- [NameCheap](http://namecheap.com)
- [Rackspace Cloud](http://www.rackspace.com/cloud/) - issues with out-of-sync file timestamps and permissions
- [1and1.com](http://1and1.com) - please see [issue raised](https://github.com/statamic/hosts/issues/12) for more details.

## Standard Dev Environments

Wide-spread dev environments that work well (e.g. MAMP)

- [MAMP 3](http://www.mamp.info/en/) (*MAMP 2 works as well*)
- [Laravel Valet](https://laravel.com/docs/master/valet)
- [Laravel Homestead](https://laravel.com/docs/homestead) - Works well for Windows
- A [Vagrant for Statamic](https://github.com/bradleyflood/vagrant-statamic) setup
- [Scotch Box](https://github.com/scotch-io/scotch-box) - 'A Vagrant LAMP Stack That Just Works'
- Jack's iMac
