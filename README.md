# NIL-1.0

Native Information License is a free license.

In your dataset, NIL obligates you (the licensor):

- To include the permission notice (select one or more of following).
  - Usually, bundle the `LICENSE` file.
  - Otherwise or even so, add either or both of these into every file:
    - A notice that the file is released under the specific version of NIL.
    - The entire content of `LICENSE` file.
- NOT to include any of copyright notices associated with you.
  - Therefore you shall agree that the copyright and the exclusive rights assosiated with your dataset must be disclaimed.

So you MUST NOT notice that you are the "copyright holder" but MAY notice that you are the "author" or "contributor" simply.

When you have made some changes to a dataset licensed under NIL, you SHOULD NOT apply any other licenses to the changed parts for leaving them simple. In this case, any of copyright associated with the changed parts shall be disclaimed.

# Compatibility

In the sentences below, "include" means "be distributed with".

## When you license your dataset under NIL, ...

### The dataset MUST NOT include any bits (e.g. code snippets) of datasets licensed under:

- GPL
- LGPL
- MPL

but MAY

- Apache License
- MIT License

### The dataset MUST NOT include any of files or static libraries licensed under:

- GPL
- LGPL

but MAY

- MPL
- Apache License
- MIT License

### The dataset MUST NOT be linked to any of datasets (e.g. dynamic libraries) licensed under:

- GPL

but MAY

- LGPL
- MPL
- Apache License
- MIT License

## To use datasets licensed under NIL

Your dataset MAY be licensed under any license you prefer, unless the license of NIL-licensed dataset can be kept. When you extract some bits (e.g. code snippets) and/or files from it, you MUST notice that those are licensed under NIL. This will not apply where you have made any change to those.

# Multilicensing

If you want to license NIL **AND** some other licenses, you MAY license only with:

- CC0
- WTFPL

because other licenses would require copyright notices. In SPDX syntax, You might specify like `(CC0-1.0 AND SEE LICENSE IN ./LICENSE)` since NIL is not in SPDX License List. Still free to use OR.