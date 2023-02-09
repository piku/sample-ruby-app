# Sample Ruby Application for `piku`

> Contributed by @ewalk153

This is a simple ruby [Sinatra](https://sinatrarb.com) that demonstrates running a ruby application on `piku`.

To publish this app to `piku`, clone this repository run the following commands:

```bash
git remote add piku piku@your_server:sample-ruby-app
git push piku main
```

Then you can set up an SSL cert and connect a domain by setting config variables like this:

```bash
ssh piku@your_server config:set sample-ruby-app NGINX_SERVER_NAME=your_server
```
