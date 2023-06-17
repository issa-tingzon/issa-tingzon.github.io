## Personal Website
This website template was sourced from: https://github.com/alshedivat/al-folio

### Local setup using Docker (Recommended on Windows)
You need to take the following steps to get the website up and running in your local machine:

- First, install [docker](https://docs.docker.com/get-docker/) and [docker-compose](https://docs.docker.com/compose/install/).
- Run the following command that will pull a pre-built image from DockerHub and will run your website.

```bash
$ docker-compose up
```

Note that when you run it for the first time, it will download a docker image of size 300MB or so.

Now, feel free to customize the theme however you like (don't forget to change the name!). After you are done, you can use the same command (`docker-compose up`) to render the webpage with all you changes. Also, make sure to commit your final changes.