# Quick Start for Python Google App Engine

## app.yaml

Deploys to `standard` or `flex` app engine.

## Simulators

```bash
gcloud beta emulators datastore start &
(gcloud beta emulators datastore env-init)

# emulators - start
gcloud beta emulators pubsub start &
`gcloud beta emulators pubsub env-init`

# emulators - kill
pkill -f emulators
unset PUBSUB_EMULATOR_HOST

```