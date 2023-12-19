# Template for building devcontainer images

## Purpose:

To prepare GitHub codespaces for each session with the required software for the given theme, a linux container needs to be built.

## How to use:

Use this repo template to create a new repo for your theme. Then, edit the Dockerfile to install the required software for your theme.

### Scope of this template:

- Include standard things in Dockerfile expected by GH codespaces (such as users)
- build the container image with GH actions
- push the image to GH container registry
