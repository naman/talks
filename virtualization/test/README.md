Test
===============

1. Create a memory hungry application, try to limit it's resources using cgroups and create a separate proc namespace to isolate processes. [10 points]
2. Nextcloud is an OpenSource private self-hosted storage solution akin to Dropbox. A Nextcloud deployment typically contains a web proxy, mysql, a php application, and the letsencrypt certbot for automated TLS certificate renewals. Deploy a Nextcloud instance using containers (You may use a Dockerfile or docker-compose, up to you). You may skip deploying the TLS certificate generator / renewal bot  (letsencrypt-nginx-proxy-companion) if you don't want to support TLS / HTTPS (EFF's certbot).

    `Hint 1`: Nextcloud is OpenSource.

    `Hint 2`: HTTPS is usually configured to run on port 443.

    `Submit` your Dockerfiles / docker-compose files and nextcloud deployment endpoints.

    ## Learning objectives:

    By the end of the exercise, you should learn about
    1. Containerizing deployment and application parts - resource limiting, isolation, efficient usage
    2. stateless vs stateful architecture - volume mounts
    2. basics of overlay networks

    [40 points]

    Bonus: Try to make the deployment stateless. [40 points]

3. 
