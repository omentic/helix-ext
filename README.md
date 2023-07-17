# helix-patches

Patches to the Helix editor for personal use.

Currently based on `2ace6032e7de46893ee87d1a2ac425b9057fa061`.
To be rebased every three months on helix/stable.

Some of these are suitable for upstreaming, pulled together from rejected or inactive patches:
- [Make initial editing mode configurable](0001-Make-initial-editing-mode-configurable.patch) by p-e-w:
  - Rejected in https://github.com/helix-editor/helix/pull/3366.
- [Fix writes from insert mode](0002-Fix-writes-from-insert-mode.patch) by omentic:
  - Fixes https://github.com/helix-editor/helix/issues/3501 and https://github.com/helix-editor/helix/issues/6513, addresses https://github.com/helix-editor/helix/issues/1142 and https://github.com/helix-editor/helix/issues/1583.
  - Rejected in https://github.com/helix-editor/helix/pull/7226.
- [Add support for moving lines](0003-Add-support-for-moving-lines.patch) by sireliah:
  - Rejected in https://github.com/helix-editor/helix/pull/4545.
- [Support for Unicode input](0004-Add-support-for-Unicode-input.patch) by Lindenk
  - Necessary for Lean, Agda, helpful for Julia, etc.
  - https://github.com/helix-editor/helix/pull/2852

Some of these are accepted patches, liable to be merged soon:
- [File explorer and tree helper](0011-Add-file-explorer-and-tree-helper.patch) by wongjiahau
  - Blocked by a O(n^2) tree structure, currently being rewritten: https://github.com/helix-editor/helix/pull/5768
- [Rainbow tree-sitter matches](0012-Add-rainbow-tree-sitter-matches.patch) by the-mikedavis:
  - Languishing in https://github.com/helix-editor/helix/pull/2857, likely will be merged for an upcoming release?
- [Rainbow indentation](0013-Add-rainbow-indentation-guides.patch) by SoraTenshi
  - Blocked by the above, https://github.com/helix-editor/helix/pull/4493
- [unbind-default-keys config option](0014-Add-unbind-default-keys-config-option.patch) by Lindenk:
  - Waiting on review in https://github.com/helix-editor/helix/pull/2733.
