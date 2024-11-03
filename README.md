# Blog

A static blog built with [Hugo](https://gohugo.io/) using the [panr/hugo-theme-terminal](https://github.com/panr/hugo-theme-terminal) theme.

## Prerequisites

- **Git**: Ensure Git is installed to manage the repository and submodules.
- **Hugo**: Download and install Hugo by following the instructions on the [Hugo website](https://gohugo.io/getting-started/installing/).

## Getting Started

1. **Clone the repository**:

```bash
git clone --recurse-submodules https://github.com/ZSM-Sat-Team/blog.git blog
cd blog
```

2. **Run locally**:

```bash
hugo server
```

3. **Add content**:

```bash
hugo new content content/posts/my-new-post.md
```

4. **Build the site**:

```bash
hugo
```

## Hosting

We don't have any deployment instructions since our blog is hosted on a VPS provided by [mikr.us](https://mikr.us), where we manage our own deployment setup.

For your own use case, refer to Hugo's [deployment documentation](https://gohugo.io/hosting-and-deployment/) to find the best hosting solution.

## Sponsors

Thanks to [mikr.us](https://mikr.us) for providing free hosting for our blog.

<a href="https://mikr.us"><img height="200" src="https://github.com/user-attachments/assets/c76ba45d-ff8e-4b39-afc6-465ab86bc688" /></a>

