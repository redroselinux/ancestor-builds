# Contributing guide

If you want to contribute a package, please read this.

## How to make packages?

Go to the docs site: https://docs.redroselinux.org/#/ancestor

## Rules

1. If you want to submit a proprietary package, email us at [proprietary.packages@redroselinux.org](mailto:proprietary.packages@redroselinux.org).
2. The package must not contain any sort of malware, illegal, or NSFW content. Please use common sense.
3. If you use the anonymous identity (as mentioned in the docs) in your package manifest and the package fails to build, we will delete the package.
4. Only package packages you are actually allowed to package.
5. In case you patch source: you MUST include the patch file in the package folder.

## AI usage

This deserves its own section outside of the Rules section.

You can use AI to ask how to compile package; we do that ourselves.
However, if you use it to generate a whole package manifest, you have to check if there are any mistakes.

Please also tell us if you used AI.

## Submitting a PR

If you are updating a package, format the title like this: `[update] package: ...`.
For fixing a package, use `[fix]` and explain in the description what you did.
If you are adding a package, format the title like this: `[add] package: package description`.
If you added/edited multiple packages, just do: `[...] package1, package2, etc`.
In the description, explain what you added, and most importantly, why.
