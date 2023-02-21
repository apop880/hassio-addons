# Getting Started

After installing this add-on, there is only one piece of configuration needed. The default port exposed by the add-on is 8800, but if you have another add-on using that port or want to change the exposed port for another reason, you are free to do so.

In addition, you'll also need to add your Photodash URL as a CORS allowed origin in Home Assistant. For example,  if your Home Assistant server is running at 192.168.1.2, and Photodash is configured on the default port 8800:

```yaml
http:
  cors_allowed_origins:
    - "http://192.168.1.2:8800"
```

## Why not Ingress?

Home Assistant Add-ons using Ingress require the Home Assistant sidebar be displayed. Because Photodash has been designed to be used as a full-screen slideshow dashboard, it must expose a port locally rather than using Ingress.

# Using Photodash

After starting the add-on, check out the [Photodash User Guide](https://photodash.apop.tech/docs/category/user-guide) for full instructions on how to get started.