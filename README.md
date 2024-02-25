# zmk-config

Related:

- https://github.com/lttb/qmk-config

```sh
west build -b corneish_zen_v2_left -s app -d build/corneish_zen_v2_left -- -DZMK_CONFIG=/workspaces/zmk-config/config
west build -b corneish_zen_v2_right -s app -d build/corneish_zen_v2_right -- -DZMK_CONFIG=/workspaces/zmk-config/config
```
