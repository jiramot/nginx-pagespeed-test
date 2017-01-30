# Tesging Nginx with Google PageSpeed

## What's about PageSpeed
https://developers.google.com/speed/pagespeed/module/?hl=th

## How to build PageSpeed with Nginx
https://modpagespeed.com/doc/build_ngx_pagespeed_from_source

This experimental will use Docker Image form https://hub.docker.com/r/jiramot/nginx/
or you can clone form Github https://github.com/jiramot/nginx

## How to test
- Request to http://localhost:20001/0ef7d59e-b923-4387-9356-035ce18c7e74.jpg
- Firstly, It should return image size ~222KB.
- After cached the image size should return ~75.3KB
