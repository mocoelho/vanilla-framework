---
wrapper_template: '_layouts/docs.html'
context:
  title: Placeholders | Settings
---

## Placeholders

<hr>

Vanilla uses several global placeholders to share common styles between components. These placeholders can be edited via the following placeholder variables, assuming a `$sp-unit` of `0.5rem`.

| Placeholder variable | Default value                                   | Use cases                                               |
| -------------------- | ----------------------------------------------- | ------------------------------------------------------- |
| `$bar-thickness`     | `3px`                                           | Navigation, notification                                |
| `$border-radius`     | `2px`                                           | Button, Card, Code, Form, Media object, Switch, Tooltip |
| `$border`            | `1px solid $color-mid-light`                    | Card, Code, Form, Search box                            |
| `$box-shadow`        | `0 1px 5px 1px transparentize($color-dark, .8)` | Card (highlighted), Modal, Notification, Switch         |

### Related

- [Spacing settings](/docs/settings/spacing-settings)
