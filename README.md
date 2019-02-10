# Blog Code Samples


This repo contains code samples from my blog posts on [Medium](https://medium.com/@engbrunoeilliar) or any other plataform that I use to write some bulshit. Feel free to use the sample codes, but if you built something that works at least be honest and give me some credit for helping you to excel in whatever you are doing. But if you built something that does not work, no need to use my name. :smirk:


## Requirements 

If you want to run any code in a previously tested environment, I recomend using the `docker-compose.yml` file that you can find in this repo. To run that you will need:

- docker >= 18.0X
- docker-compose >= 1.21.0

Once you have all that docker stuff installed, you can run one of the following containers (make sure to check the blog post to check which container to use) by typing:

```bash
docker-compose up <service-name>
```

For instance, if you wanto to run an environment with all basic Data Science modules (scipy, numpy, pandas, scikit-learn, matplotlib and so on) you can do so by running the following command:

```bash
docker-compose up sandbox
```

## Accessing the Jupyter Notebooks

Once you launched any container, you can access the Jupyter Notebooks by opening your web browser (I recommend Chrome or Firefox, if you dare to use Internet Explorer/Edge, please, get out!) and typing  `localhost:<service_port>`. You can find the port in the `docker-compose.yml`. The password to access the working directory is __42__ (if you known the reference, you are a man/woman/_alien_ of culture).


:rocket: