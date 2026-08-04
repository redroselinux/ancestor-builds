# Contributing guide

If you want to contribute a package, please read this.

## How to make packages?

Go to the docs site: https://docs.redroselinux.org/#/ancestor

## Rules

1. If you want to submit a proprietary package, email us at [proprietary.packages@redroselinux.org](mailto:proprietary.packages@redroselinux.org).
2. The package must not contain any sort of malware, illegal, or NSFW content. Please use common sense.
3. If you use the anonymous identity in your package manifest, we will delete the package in case it fails to build.
4. Only package packages you are actually allowed to package.
5. In case you patch source: you MUST include the patch file in the package folder.

## AI usage

This deserves its own section outside of the Rules section.

You can use AI to ask how to compile package. However, if you use it to generate a package manifest, you have to check if there are any mistakes.

## Submitting a PR

If you are updating a package, format the title like this: `[update] package: ...`. If you are adding a package, format the title like this: `[add] package: package description`.
In the description, explain what you added, and most importantly, why.
