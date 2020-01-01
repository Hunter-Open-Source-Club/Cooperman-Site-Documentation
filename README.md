# cooperman-site-documentation
Documentation regarding the deployment and maintenance of Hunter College's Cooperman Site.

The HOSC Cooperman Site, hosted at http://cooperman.hunterosc.org , is a deployed instance of Wordpress under AWS.

## contributors 

Ralph Vente @rvente (Backend Administator and Frontend Web Developer)
* configured and deployed the the server instance
* registered and forwarded the domain
* adjusted the navbar and footer
* migrated content and added consistency to page layout
* ensured fluent document layout across pages

Joshua Natis @joshnatis (Frontend Web Developer)
* migrated content and added consistency to page layout
* ensured fluent document layout across pages

Kevin Wong @Darktwine (Quality Assurance)
* revised the site for broken links
* ensured consistent document style

## Guide

1. Purchase a domain name. We used https://domains.google.com/

2. Deploy an AWS compute instance with Wordpress
   * https://docs.bitnami.com/aws/how-to/get-started-wordpress-aws-marketplace-beginner/
   * https://aws.amazon.com/getting-started/tutorials/launch-a-wordpress-website/
   
   At this point, you will be able to sign in to your Wordpress site, but it will not be on your domain yet. Do not upload additional media to your site. When you update your domain on this Wordpress site, it will not update the links of the media, so you would have to update the links or reupload your media. 

3. Map your domain. This has two steps (1) tell your Google Domains to point to your site (2) tell your Wordpress site to present that domain name.
   * https://wpengine.com/support/configure-google-domains-dns/
   
4. Finishing touches
   * https://docs.bitnami.com/aws/how-to/bitnami-remove-banner/
