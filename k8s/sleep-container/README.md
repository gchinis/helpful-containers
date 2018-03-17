# Sleep Container

A container that immediately sleeps.

Useful if you want to exec into the cluster and inspect its state.

## Usage
`kubectl apply -f sleep.yaml`

wait for the container to come up

`kubectl exec -it sleep bash`
