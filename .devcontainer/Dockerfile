FROM mcr.microsoft.com/devcontainers/ruby:0-3.1-bullseye

# Dev Container のイメージでは、使用したいバージョンの Ruby が
# インストールされたものがなかったため、ここでインストールしています
RUN rvm install "ruby-3.2.0"

# Install Rails
RUN gem install rails webdrivers 

# [Optional] Uncomment this section to install additional OS packages.
# RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
#     && apt-get -y install --no-install-recommends <your-package-list-here>

# [Optional] Uncomment this line to install additional gems.
# RUN gem install <your-gem-names-here>

# [Optional] Uncomment this line to install global node packages.
# RUN su vscode -c "source /usr/local/share/nvm/nvm.sh && npm install -g <your-package-here>" 2>&1
