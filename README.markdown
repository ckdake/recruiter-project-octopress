## Recruiter Project

### Local Server

```bash
bundle exec rake preview
```

Then navigate to <http://localhost:4000>

### New Post

```bash
bundle exec rake 'new_post[my new post title]'
```

### New Page

```bash
bundle exec rake 'new_page[my new page title]'
```

### Deploy

This blog runs on GitHub Pages. To set it up for deployment, run this command
once:

```bash
bundle exec rake 'setup_github_pages[git@github.com:ckdake/recruiter-project-octopress.git]'
```

To generate the site and deploy it to
[recruiterproject.org](http://recruiterproject.org), run:

```bash
bundle exec rake gen_deploy
```
