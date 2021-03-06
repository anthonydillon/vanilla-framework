---
title: Spacing settings
table_of_contents: true
---

## Spacing

Vanilla uses numerous spacing variables across the codebase in order to ensure consistency in spacing between components, and to ensure typographic elements sit on the baseline grid.

### Spacing unit

Vanilla uses a default spacing unit of `.5rem` (`8px`) as a basis to calculate spacing inside and between components, as well as the line-heights of the different type sizes.

![Baseline grid example](https://assets.ubuntu.com/v1/d2c31b2d-screenshot.png 'Baseline grid example')

The image shows the headings sitting on the baseline grid, where the space between each line is one `$sp-unit`.

### Vertical spacing

The `$spv-inner` variables are used to determine vertical spacing inside components, while `$spv-outer` variables are used for spacing between components.

| Spacing variable        | Formula            | Default value |
| ----------------------- | ------------------ | ------------- |
| `$spv-inner`            | `$sp-unit`         | `.5rem`       |
| `$spv-inner--condensed` | `$spv-inner * .5`  | `.25rem`      |
| `$spv-inner--expanded`  | `$spv-inner * 1.5` | `.75rem`      |
| `$spv-outer--regular`   | `$sp-unit * 2`     | `1rem`        |
| `$spv-outer--condensed` | `$sp-unit`         | `.5rem`       |
| `$spv-outer--expanded`  | `$sp-unit * 3`     | `1.5rem`      |

The following vertical spacing variables are used between a group of components and its wrapper, for example in strips.

| Spacing variable                | Formula        | Default value |
| ------------------------------- | -------------- | ------------- |
| `$spv-outer--shallow-scaleable` | `$sp-unit * 4` | `2rem`        |
| `$spv-outer--regular-scaleable` | `$sp-unit * 6` | `3rem`        |
| `$spv-outer--deep-scaleable`    | `$sp-unit * 8` | `4rem`        |

### Horizontal spacing

The `$sph-inner` variables are used to determine horizontal spacing inside components, while `$sph-outer` variables are used for spacing between components.

| Spacing variable        | Formula        | Default value |
| ----------------------- | -------------- | ------------- |
| `$sph-inner`            | `$sp-unit * 2` | `1rem`        |
| `$sph-inner--condensed` | `$sp-unit`     | `.5rem`       |
| `$sph-outer`            | `$sp-unit`     | `.5rem`       |
| `$sph-outer--expanded`  | `$sp-unit * 3` | `1.5rem`      |

### Generic units

There are also generic spacing units for backwards compatibility with components created with Vanilla before `v1.7.0`.

| Spacing variable  | Formula          | Default value |
| ----------------- | ---------------- | ------------- |
| `$sp-xx-small`    | `$sp-unit * .25` | `.125rem`     |
| `$sp-x-small`     | `$sp-unit * .5`  | `.25rem`      |
| `$sp-small`       | `$sp-unit`       | `.5rem`       |
| `$sp-medium`      | `$sp-unit * 2`   | `1rem`        |
| `$sp-large`       | `$sp-unit * 3`   | `1.5rem`      |
| `$sp-x-large`     | `$sp-unit * 4`   | `2rem`        |
| `$sp-xx-large`    | `$sp-unit * 5`   | `2.5rem`      |
| `$sp-xxx-large`   | `$sp-unit * 6`   | `3rem`        |
| `$sp-xxxx-large`  | `$sp-unit * 8`   | `4rem`        |
| `$sp-xxxxx-large` | `$sp-unit * 12`  | `6rem`        |
