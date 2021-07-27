# NIL-1.0

Native Information License is a free license.

The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT", "SHOULD", "SHOULD NOT", "RECOMMENDED",  "MAY", and "OPTIONAL" in this document are to be interpreted as described in RFC 2119.

## TL;DR

NIL is equivalent as `(Unlicense OR CC0-1.0)` plus conditions that:

- The author(s) MUST NOT include any form of "copyright notice" in the work
- The author(s) MUST include the licence notification that the work is licensed under NIL by the work itself, not by the author(s)
  - This is done by bundling LICENSE file with the work

## Concept

NIL doesn't allow you to license your work to someone. ***The work*** does it. It licenses the work itself to other beings, including you. This point is the core concept of NIL.

If you apply NIL to your work, you MUST NOT notice that you are the "copyright holder", but you MAY still notice that you are the "author" or "contributor" simply, however, including such notices absolutely SHALL NOT mean that you're treated as the copyright holder, because you apply NIL to your work. NIL just rejects any rights holded by other than the work itself.

So, strictly speaking, "You license it under NIL" is not correct wording, you SHOULD say "You apply NIL to your work" or "The work licenses itself under NIL to everyone" instead. Of course, you MAY use the incorrect wording when you're incorrect or not strict.

## Compatibility

In the sentences below, "include" means "be distributed with".

### When you license your dataset under NIL

#### The dataset MUST NOT include any parts (e.g. code snippets) of datasets licensed under

- GPL
- LGPL
- MPL

but MAY

- Apache License
- MIT License

#### The dataset MUST NOT include any of files or static libraries licensed under

- GPL
- LGPL

but MAY

- MPL
- Apache License
- MIT License

#### The dataset MUST NOT be linked to any of datasets (e.g. dynamic libraries) licensed under

- GPL

but MAY

- LGPL
- MPL
- Apache License
- MIT License

### To use datasets licensed under NIL in your project

The whole of your project MAY be licensed under any license you prefer, as long as a license notice for the NIL-licensed dataset can be kept available to your licensees (see above for compatibility). Even if you extract some parts (e.g. code snippets) and/or files from the NIL-licensed dataset, you MUST notice that those parts are licensed under NIL. This will not apply where you have made some changes to those.

### To change datasets licensed under NIL

When you have made some changes to a dataset licensed under NIL, you SHOULD NOT apply any other licenses to the changed parts for leaving them simple (still possible though). In this case, any of copyright associated with the changed parts shall be disclaimed.

## Multilicensing

If you want to use NIL **AND** some other licenses, you MAY do it only with:

- CC0
- Unlicense

Because other licenses would require copyright notices. In SPDX syntax, You might specify like `(CC0-1.0 AND SEE LICENSE IN ./LICENSE)` since NIL is not in SPDX License List.

Still free to use OR with any other licenses.