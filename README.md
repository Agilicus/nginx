## nginx

This is a base-container running ubuntu 18.04 with nginx.
What makes it different than the others is it includes

- [nginx_cookie_flag_module](https://github.com/AirisX/nginx_cookie_flag_module)
- [lua-resty-waf](https://github.com/p0pr0ck5/lua-resty-waf)

The nginx_cookie_flag_module allows setting HttpOnly, Secure, SameSite on cookies
coming from upstream.

The lua-resty-waf allows complex security filtering.

The Dockerfile itself is made available under the [Apache 2 license](https://www.apache.org/licenses/LICENSE-2.0).
Individual files within the built container have their own licenses.
