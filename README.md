# BRISKODA Cars

The 2019 BRISKODA Cars minisite, using [Hugo], deployed via [Netlify]

[![Netlify Status](https://api.netlify.com/api/v1/badges/40a55931-eb9c-427c-8e62-914b21477605/deploy-status)](https://app.netlify.com/sites/briskoda-cars-1d562e/deploys)

## Building locally

To work locally with this project, you'll have to follow the steps below:

1. Fork, clone or download this project
1. [Install][] Hugo
1. Preview your project: `hugo server`
1. Add content
1. Generate the website: `hugo` (optional)

Read more at Hugo's [documentation][].

### Preview your site

If you clone or download this project to your local computer and run `hugo server`,
your site can be accessed under `localhost:1313/hugo/`.

## Troubleshooting

1. CSS is missing! That means two things:

   Either that you have wrongly set up the CSS URL in your templates, or
   your static generator has a configuration option that needs to be explicitly
   set in order to serve static assets under a relative URL.

[hugo]: https://gohugo.io
[netlify]: https://netlify.com
[install]: https://gohugo.io/overview/installing/
[documentation]: https://gohugo.io/overview/introduction/
