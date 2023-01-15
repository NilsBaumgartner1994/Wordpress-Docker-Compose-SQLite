# Wordpress-Docker-Compose-SQLite

## Installation:

1. Download Project
2. Setup Nginx-Proxy: (https://github.com/nginx-proxy/nginx-proxy)
   - topDomainProxy is the network
3. Configure `.env` file

## Informations

- Wordpress 6.1.1
- Nginx: https://github.com/nginx-proxy/nginx-proxy (dev Version)
- SQLite Adapter: https://github.com/aaemnnosttv/wp-sqlite-db


## Custom CSS

- Install "Simple Custom CSS"
- Add the following:
```
/* Makes images smaller on blog pages. Before it was by the height of the image */
.wp-block-post-featured-image.alignwide img {
    max-height: 250px;
    width: auto;
	  display: block;
    margin-left: auto;
    margin-right: auto;
	  background-color: "red";
}

/* Remove the dim effect, because it is totally stupid */
.wp-block-post-featured-image .wp-block-post-featured-image__overlay.has-background-dim-50 {
   opacity: 0;
}
```
