# P3.1 Simple tekton CI

It is just a simple tekton ci demo, the following components are used: Lighthouse, Tekton, Kaniko, local docker registry, helm3, go.

Be based on installing lighthouse, tekton. We set up webhook with them. Then we run a pipeline, which can clone the golang code from github, build it, build image and push to registry in the end.

