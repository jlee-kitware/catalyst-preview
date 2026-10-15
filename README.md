# catalyst-preview

**Generated. Do not edit `index.html` here — it is overwritten on every deploy.**

Source of truth:

    ~/gitsync/catalyst_website/prototype/index.html

To publish a change:

    cd ~/gitsync/catalyst_website
    ./deploy.sh "what changed"

Live at https://jlee-kitware.github.io/catalyst-preview/

This is a staging host, not a destination. `deploy.sh` adds a `noindex, nofollow`
meta to the copies here and writes a `robots.txt` that disallows everything, so
this copy cannot compete in search with the kitware.com page the content is
headed for. Neither the meta nor the robots.txt exists in the source, so porting
`prototype/index.html` into the CMS will not carry a noindex onto the live page.
