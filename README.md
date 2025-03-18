# vcstool+

Fork of [Dirk Thomas's vcstool](https://github.com/dirk-thomas/vcstool) with additional functionality.

## Installation

```bash
pip3 install git+https://github.com/nzlzcat/vcstool
```

## Changes

- Added support for `subdir` in `repos` file. Example:

    ```yaml
    repositories:
      my_subdir:
        type: git
        url: <git@github.com>:my_org/my_repo.git
        version: my_branch
        subdir: my_subdir
    ```
