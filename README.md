# Stackbit Vanilla Theme

This site was generated by [www.stackbit.com](https://www.stackbit.com), v0.2.85.

Stackbit Vanilla Theme original README is located [here](./README.theme.md).

The content of this site is managed by NetlifyCMS. Visit https://{yoursite-domain}/admin to manage site content.

# Running Your Site Locally

1. [Install Hugo](https://gohugo.io/getting-started/quick-start/#step-1-install-hugo)

1. get "stackbit-api-key" from project menu in [Stackbit dashboard](https://app.stackbit.com/dashboard)

1. run the following command to assign this key to `STACKBIT_API_KEY` environment variable:

        export STACKBIT_API_KEY={stackbit_netlify_api_key}

1. run the following command to fetch additional site contents from Stackbit if needed:

        npx @stackbit/stackbit-pull --stackbit-pull-api-url=https://api.stackbit.com/pull/5e8b96938a53180014e5b048

1. Build the site and start the Hugo server with drafts enabled

        hugo server -D

1. Browse to [http://localhost:1313/](http://localhost:1313/)
