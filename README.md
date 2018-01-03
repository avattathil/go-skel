# Creating the environment

```
mkdir -p ~/environment/go/
cd ~/environment/go/
```

# Set Go Variables
```
echo "# Go Variables" >> ~/.bash_profile
echo "export GOPATH=$HOME/environment/go" >> ~/.bash_profile
echo "export GOBIN=$GOPATH/bin" >> ~/.bash_profile
source  ~/.bash_profile
```
# Get go-skel code
`go get -x github.com/avattathil/go-skel`

# Install go-skel
`go install github.com/avattathil/go-skel/`

The binary will be here: `~/environment/go/bin/go-skel`

The source will be here: `~/environment/go/src/github.com/avattathil/go-skel/main.go`
