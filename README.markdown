## Recruiter Project

### Octopress

This blog is based on Octopress. To set it up for GitHub Pages deployment,
run:

```bash
bundle exec rake 'setup_github_pages[git@github.com:ckdake/recruiter-project-octopress.git]'
```

The `setup_github_pages` command only needs to be run once. To deploy it to
[recruiterproject.org](http://recruiterproject.org), run:

```bash
bundle exec rake gen_deploy
```
