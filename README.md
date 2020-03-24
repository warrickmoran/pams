# pams

How it works

1. Visit https://mybinder.org/
2. Enter warrickmoran/pams as the GitHub repository information
3. Mybinder builds a Docker image of your repository
Binder will search for a dependency file, such as requirements.txt or environment.yml, in the repository's root directory (more details on more complex dependencies in documentation). The dependency files will be used to build a Docker image. If an image has already been built for the given repository, it will not be rebuilt. If a new commit has been made, the image will automatically be rebuilt.
4. Interact with your notebooks in a live environment using the URL provided under "Copy the URL below and share your Binder with others:"
A JupyterHub server will host your repository's contents. We offer you a reusable link and badge to your live repository that you can easily share with others.
