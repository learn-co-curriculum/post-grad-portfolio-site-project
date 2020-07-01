# Build Your Personal Website

## Introduction

In addition to upgrading and polishing your portfoilo projects, building a personal
website is a great way to both build your online presence and show off your abilities
as a web developer.

## Building Your Site

The Career Prep track already includes a detailed lesson on what you can include on your
website, so we recommend [reading through the suggestions there][career prep lesson] to get
an idea of what content your site should include. Also, be sure to review the
[lesson on personal brand building][personal brand] to help you think about how your site should
represent you.

You are free to develop your personal website however you choose - if you'd like to build one
using a a site like WordPress or Wix, feel free to. However, you do have all the skills required to
create one entirely from scratch, and doing this will give you a greater degree of control over
exactly how your site looks and functions. You might consider building a site based on what sort
of roles you're looking to apply for - particuarly, if you are going to be applying for frontend
or full-stack development roles, building a nicely polished frontend in React or JavaScript/HTML
can be an additional opportunity to showcase your abilities beyond your portfolio projects.

Your personal website does not have to be very fancy. Many professional developers 
actually opt for a minimal approach to their personal website. One important thing to keep in mind,
though - make sure your site looks good on multiple devices, not just your personal computer. It is
entirely possible a company recruiter might look at your site using their phone, especially if
you've linked to it from your LinkedIn profile.

## Deploying Your Site

Custom built personal sites are typically static, so you probably don't need a backend. Because of
this, hosting on [GitHub pages][] is a good option to consider as your site will probably already
be stored on your GitHub account. For deploying React sites, we recommend the [gh-pages][] NPM package,
as it streamlines the process of pushing up changes. One challenge with GitHub pages - if you're hosting
multiple React sites and using routing in any of them, setting them all up to work without interfering
with eachother can be tricky. If this is the case, it may be worth considering alternatives like
[Google Firebase][] to handle your personal website. Firebase offers free hosting and provides a
command-line tool for rapid deployment.

## Getting a Domain Name

You aren't required to get a domain for your personal site, but it can be helpful as part of building your
personal brand. For example, you might have a GitHub account name that isn't recognizable as _you_, so hosting your
personal website at `<your-cool-username>.github.io` may not be ideal. Having a custom domain name gives you the option
to publicize something more direct, like `<your-full-name>.com`.

There are many domain registration services available online. [GoDaddy][], for instance, offers domain
registration options for less than $20 a year and includes documentation on how to redirect from your
custom domain to where your site is hosted. **Be careful to explore what options are available before
locking in a domain name, though**. You do not want to register a domain for a year, only to realize
shortly after you'd rather use a different service or different name.

[career prep lesson]: https://github.com/learn-co-curriculum/careers-personal-website-portfolio
[personal brand]: https://github.com/learn-co-curriculum/careers-personal-brand-building
[GitHub pages]: https://pages.github.com/
[gh-pages]: https://www.npmjs.com/package/gh-pages
[Google Firebase]: https://firebase.google.com/
[GoDaddy]: https://godaddy.com
