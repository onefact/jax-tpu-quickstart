# Create your TPU

1. https://console.cloud.google.com/compute/tpus
2. "Create TPU"
3. find the correct zone for your TPU type from this table https://cloud.google.com/tpu/docs/regions-zones; under "Basics" set "Zone"
4. under "TPU Settings" set "TPU software version" to tpu-ubuntu2204-base and "TPU type" to your TPU type
5. under "Management" select Preemptibility if desired

# Install Jax

per https://cloud.google.com/tpu/docs/run-calculation-jax:
```sh
python3 -m pip install jax[tpu] -f https://storage.googleapis.com/jax-releases/libtpu_releases.html
```

# Run Jax

TODO
