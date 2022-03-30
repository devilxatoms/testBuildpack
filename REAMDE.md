pack buildpack new examples/node \
    --api 0.7 \
    --path node-buildpack \
    --version 0.0.1 \
    --stacks io.buildpacks.samples.stacks.bionic


pack build test-node-app --path ./node-sample-app --buildpack ./node-buildpack