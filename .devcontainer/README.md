# Devcontainer configuration for Codespaces

The file ```.devcontainer/devcontainer.json``` is read when your Codespace is created.  Note that if you change your git branch then the configuration is not checked, so it is important that you create your Codespace from the branch you intend to work in. 

## Dockerfile

The ```with-dockerfile``` branch includes a Dockerfile.  It can be used with Codespaces or with VS Code 'Remote-Containers' feature, however it will make the Codespaces startup much slower.

## More information

See <https://docs.microsoft.com/en-us/visualstudio/codespaces/reference/configuring>