# Your Green Future

A prototype built as part of mySociety’s June 2022 prototyping week exploring digital services to support a fair transition to a world that’s reducing climate risks and harm.

## Use it online

Visit <https://mysociety.github.io/your-green-future>.

All modern browsers are supported. Internet Explorer is not. See `.browserlistrc` for details.

## Running locally

Requirements:

- [Ruby](https://www.ruby-lang.org/en/documentation/installation/)
- [Bundler](https://bundler.io/#getting-started)

Install all dependencies and get a local server running immediately, in one command:

    script/server

The site will be available at both <http://localhost:4000> and <http://0.0.0.0:4000>.

If you want to serve locally over SSL (recommended) then generate self-signed SSL certificates with:

    script/generate-ssl-certificates

Once the SSL certificates are in place, `script/server` will serve the site over HTTPS, at both <https://localhost:4000> and <https://0.0.0.0:4000>. (You will need to tell your web browser to accept the self-signed certificate.)

You can build the site to `_site` (without serving it) with:

    script/build
