##

brew install pyenv
pyenv install 3.7.6
pyenv global 3.7.6

# 系统默认 python 3.7.6
echo -e '\nif command -v pyenv 1>/dev/null 2>&1; then\n  eval "$(pyenv init -)"\nfi' >> ~/.bash_profile

# 查看版本
pyenv version

# tensorflow
pip install tensorflow

# bert
pip install bert-serving-server
pip install bert-serving-client

