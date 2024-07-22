
## Building the image
```bash 
docker build -t iris-notebook .
```

## Running the container
```bash
docker run -p 8888:8888  -v ./notebooks:/usr/src/app iris-notebook

```