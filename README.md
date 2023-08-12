# Sky-Deployment-Nginx

Clone this repo onto your ec2 and then run this command:

```bash
docker run -d --name nginx --network mynet -p 80:80 -v $PWD/nginx.conf:/etc/nginx/nginx.conf nginx
```

It'll make your back-end available on port 80 which'll help a lot with linking it to the front-end.
