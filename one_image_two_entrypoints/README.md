This project demonstrates two deployments using live\_update with two different entrypoints on the same image.

(i.e., a workaround for https://github.com/tilt-dev/tilt-extensions/issues/310)

Once you've run `tilt up`, you can edit the contents of 1.txt and 2.txt to see the deployments get live updated and restarted to pick up the new values.
