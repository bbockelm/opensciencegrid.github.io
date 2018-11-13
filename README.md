## Welcome to the Open Science Grid

This repository contains the source code of the Open Science Grid website; it is not the public facing site.

The real webpage for the OSG is <https://www.opensciencegrid.org>.

### What We Do

The OSG facilitates access to distributed high throughput computing for research in the US.
The resources accessible through the OSG are contributed by the community, organized by the OSG, and governed by the OSG consortium.
In the last 12 months, we have provided more than 1.2 billion CPU hours to researchers across a wide variety of projects.

To see the breadth of the OSG use, [explore our accounting portal](https://gracc.opensciencegrid.org).

### Submit Locally, Run Globally

Researchers can submit batch jobs from their home institution - or OSG-provided submit points - in order to access their local resources and expand
elastically out to the OSG, leverage the distributed nature of our consortium.

### Sharing Is Key

*Sharing is a core principle of the OSG.*  Over 100 million CPU hours delivered on the OSG in the past year were opportunistic: they would have remained on but idle
if it wasn't for the OSG. Sharing allows individual researchers to access larger computing resources and large organizations to keep their utilization high.

### Resource Providers

The Open Science Grid consists of computing and storage elements at over 100 individual sites spanning the United States.
These sites, primarily at universities and national labs, range in size from a few hundred to tens of thousands of CPU cores.

### The OSG Software Stack

The OSG provides an integrated software stack to enable high throughput computing; [visit our technical documents website for information](docs/).

### Find Us!

Are you a user wanting more computing resources?

Are you a resource provider wanting to join our collaboration?

If so, find us at the [support desk](https://support.opensciencegrid.org).

## Internal Documentation

### Adding To the Team Page

The [team page](https://opensciencegrid.org/about/team) provides an overview of those working on the OSG.  It's important to keep this updated to reflect the evolving nature of the OSG.  To add yourself to this page, [create a pull request](https://help.github.com/articles/about-pull-requests/) (using the standard GitHub workflow) with the following:

* A short config file about yourself, [following this example](https://github.com/opensciencegrid/opensciencegrid.github.io/blob/master/_data/people/Brian-Bockelman.yml).  Make sure to include your *name*, *shortname* (*Firstname-Lastname* as in `Brian-Bockelman`), *institution*, *website*, and *photo*.  If you are an area coordinator or have some other named role, you can fill in *title*.  Save the filename as *Firstname-Lastname.yml*.
* Upload a headshot of yourself into the `assets/images/team` directory.  Name it in the form `assets/images/team/Firstname-Lastname.jpg`; in this case, the corresponding value of the *photo* tag in your config file will be `/assets/images/team/Firstname-Lastname.jpg`.
* If you are a member of the executive team, then add your shortname tag to the [organization file](https://github.com/opensciencegrid/opensciencegrid.github.io/blob/master/_data/orgs/exec-team.yml), `_data/orgs/exec-team.yml`.
