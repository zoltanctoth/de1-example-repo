# de1-example-repo

## Install AWS in the Codespace:
```
ARCH=$(uname -m) && \
    cd /tmp && \
    curl "https://awscli.amazonaws.com/awscli-exe-linux-${ARCH}.zip" -o "awscliv2.zip" && \
    unzip awscliv2.zip && \
    sudo ./aws/install && \
    rm -rf awscliv2.zip aws && cd
```

And then
```
cd $CODESPACE_VSCODE_FOLDER
```

### Configure AWS
```
aws configure
# Add your access and secret key
# For the region use eu-west-1
# For the output format just press enter
```

## Install packages
```
pip install boto3 beautifulsoup4 jupyter
```
