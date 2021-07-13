# Contributions
Hi! I am happy that you thought of contributing! If you have any suggestions or issues, please raise it [here](https://github.com/uwasystemhealth/shl-mkdocs-tutorial-and-template/issues). I would be happy if you could provide pull requests, if you know how to do it [here](https://github.com/uwasystemhealth/shl-mkdocs-tutorial-and-template/pulls). Also add your name in the contributors section.

## Structure

### Folder Structure
The structure of this repo is as follows:

```
├── docs                    // Folders for documentation
│   ├── CNAME
│   ├── contributions.md
│   ├── deployment_and_automated_site_deployment.md
│   ├── flavoured_markdown.md
│   ├── images              // Assets
│   │   ├── shl.png
│   │   └── shl_with_text.png
│   ├── index.md
│   └── writing_markdown.md
├── LICENSE
├── mkdocs.yml              // MkDocs Configuration
├── overrides
│   └── partials
│       └── footer.html
├── README.md
└── requirements.txt
```

### Branch Structure
You might have noticed that there are a couple of branches that are important:

- `gh-pages` is the branch that contains the GitHub Pages build as per requirement of a website hosted in Github Pages
- `main` is the branch that contains the `main` branch for any development and contribution
- `template` is the branch that is in the front page of the Github Repo. This is the branch where all repositories will inherit the template.

???+ info "Why have `template` and `main` separate?"
    One of the things that you could see in `main` is the file called `CNAME` this is configuration for the domain name. Templates that inherit the files should not have this, otherwise there would be conflict in the organisation deployment for domain name.

    Furthermore, by separating this, the changes could be version batched before releasing it in `template`.

