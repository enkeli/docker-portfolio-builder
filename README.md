# Portfolio Builder Docker Image

Docker image for [Portfolio Builder](https://github.com/ajshiff/portfolio-builder)

>A portfolio builder that takes a JSON Portfolio Items file, and builds a webpage that highlights the items listed in the JSON Portfolio Items file. 

# Usage

```
$ docker run -it --rm -v $(pwd):/app enkeliwrt/docker-portfolio-builder
```

It comes with the same defaults as the original tool, so the full list of arguments is:

```                                                                                    
$ docker run -it --rm -v $(pwd):/app enkeliwrt/docker-portfolio-builder input.json output.html template.html               
```

**Note:**
>As you are mounting the current path with $(pwd), the argument files are relative to it.
