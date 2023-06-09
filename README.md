# pytorch builder

Scripts to build pytorch binaries and do end-to-end integration tests.

Folders:

- **conda** : files to build conda packages of pytorch, torchvision and other dependencies and repos
- **manywheel** : scripts to build linux wheels
- **wheel** : scripts to build OSX wheels
- **windows** : scripts to build Windows wheels
- **cron** : scripts to drive all of the above scripts across multiple configurations together
- **analytics** : scripts to pull wheel download count from our AWS s3 logs

## Testing

In order to test build triggered by PyTorch repo's GitHub actions see [these instructions](https://github.com/pytorch/pytorch/blob/master/.github/scripts/README.md#testing-pytorchbuilder-changes)
