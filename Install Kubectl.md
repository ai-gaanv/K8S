## STEP 1 - Download the latest release with the command:
curl -LO "https://storage.googleapis.com/kubernetes-release/release/$(curl -s https://storage.googleapis.com/kubernetes-release/release/stable.txt)/bin/linux/amd64/kubectl"

## STEP 2 - Make the kubectl binary executable.
chmod +x ./kubectl

## STEP 3 - Move the binary in to your PATH.
sudo mv ./kubectl /usr/local/bin/kubectl

## STEP 4 - Test to ensure the version you installed is up-to-date:
kubectl version --client
