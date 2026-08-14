# changcui.cc

Personal homepage built with [Hugo](https://gohugo.io/) and
[Hugo Bear Blog](https://github.com/janraasch/hugo-bearblog).

## Local development

Clone the repository with its theme submodule, then start Hugo:

```sh
git clone --recurse-submodules git@github.com:changcui/changcui.github.io.git
cd changcui.github.io
hugo server
```

Open <http://localhost:1313>.

## Publishing

Push changes to `master`. GitHub Actions builds and deploys the site to
<https://changcui.cc/> automatically.
