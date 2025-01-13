# Build an Ansible Collection

A GitHub action to build an Ansible collection.

## Usage

```yaml
- name: Build Ansible collection
  uses: syaghoubi00/ansible-collection-build-action@v1
```

## Inputs

### `collection-path`

description: "Path to the collection directory"

required: false

### `galaxy-file`

default: "galaxy.yml"

description: "Path to galaxy.yml file"

## Outputs

### `artifact-filename`

description: "The filename of the built collection artifact"

### `collection-name`

description: "The name of the built collection"

### `collection-namespace`

description: "The namespace of the built collection"

### `collection-version`

description: "The version of the built collection"
