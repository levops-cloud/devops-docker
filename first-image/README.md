# Create your first image

```
docker build . -t helloworld


docker run -d -p 5000:5000 --restart=always --name registry -v /mnt/registry:/var/lib/registry registry:2
docker tag 409806a8ce8b localhost:5000/helloworld
docker push localhost:5000/helloworld
```
