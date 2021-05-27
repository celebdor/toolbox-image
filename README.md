# Building

In order to build release 34:

    cd 34
    podman build -t quay.io/my_quay_username/fedora-toolbox:34 -f Containerfile .

# Creating the toolbox

    toolbox create --image quay.io/my_quay_username/fedora-toolbox:34 fedora-toolbox-34

# Running

    toolbox enter
