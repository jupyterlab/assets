---
layout: post
title: "JupyterLab 4.0.0 Release Candidate is out"
date: 2023-04-11 14:00:00 -0000
categories: posts
excerpt: "The next major version of JupyterLab is coming soon; check it out."
---

# JupyterLab 4.0.0 Release Candidate is out

The next major version of JupyterLab is coming soon (ETA mid-May). We have
started to publish release candidate version that you can try using:

With `pip`

```sh
pip install --pre "jupyterlab>=4.0.0rc0"
```

Or with `conda`

```sh
conda install -c "conda-forge/label/jupyterlab_rc" jupyterlab
```

## What is new?

Have a look at the [major highlights](https://hackmd.io/@fcollonval/HJiUph5bn).
The detailed changes can be found on the [GitHub release page](https://github.com/jupyterlab/jupyterlab/releases/tag/v4.0.0b1).

## How can you help?

There are many ways, you can help making this release better:

- [Report issues](https://github.com/jupyterlab/jupyterlab/issues/new/choose).
- [Help translating](https://crowdin.com/project/jupyterlab) - required registration to the Crowdin platform.
- [Contribute to fix issues]().
- [For developer] start porting your extension. Please look at the [migration guide](https://jupyterlab.readthedocs.io/en/latest/extension/extension_migration.html#jupyterlab-3-x-to-4-x). You could also look at the PR migrating [the extension examples](https://github.com/jupyterlab/extension-examples/pull/225).
