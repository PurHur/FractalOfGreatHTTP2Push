# FractalOfGreatHTTP2Push
Real HTTP 2 Push for everything (wich uses nginx). 

# nginx config

This works really well with the nginx config

```
http2_push_preload on;
```

## Behind the scenes

The script collects all resources and pre renders a preload link header. This will then be converted to real http2 push by nginx.
