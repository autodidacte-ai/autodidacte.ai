# autodidacte.ai

autodidacte.ai web site

See [here](http://blog.teamtreehouse.com/using-github-pages-to-host-your-website) for setup details.
Visible at [https://autodidacte-ai.github.io/autodidacte.ai/](https://autodidacte-ai.github.io/autodidacte.ai/).

First you will need to create a new file in your GitHub repo called CNAME that contains the domain name (or subdomain) that you wish to use. This file should be placed in the gh-pages branch if you are using project-pages (as we have been in this post). If you are using user-pages the file should be placed in the master branch.

Your CNAME file might look like the following:

```txt
www.autodidacte.ai
```

Next you will need to update the DNS records for your domain name. This is usually done through a control panel provided by your domain registrar.

If you want to use a root domain (such as `example.com`) for your website you will need to setup a new A record that points to the IP address:

`192.30.252.153` or `192.30.252.154`

If you are using a subdomain (such as `blog.example.com`) it’s best to create a new CNAME record that points to your GitHub user subdomain
(`**username**.github.io`). This is so that the DNS will be automatically adjusted if the servers IP address changes on GitHub.
