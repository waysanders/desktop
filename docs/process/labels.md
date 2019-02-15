# Issue and Pull Request Labels

This section outlines the labels currently used in the project, and adds context
about what each label represents.

## Common labels

These labels are used for both issues and pull requests, and are assigned to
help understand the type of work involved.

|                                    | Label name .          | Description |
| ---------------------------------- | ----------------------| ----------- |
| [:mag_right:][area:docs]           | `area:docs`           | Issues and pull requests related to documentation work on the project |
| [:mag_right:][area:infrastructure] | `area:infrastructure` | Issues and pull requests related to scripts and tooling for GitHub Desktop |
| [:mag_right:][area:tech-debt]      | `area:tech-debt`      | Issues and pull requests related to addressing technical debt or improving the codebase |

## Issue-specific labels

This section is organized into sub-groups, as groups of labels relate to
specific work being done in the issue tracker.

### Issue triage

The triage process is how the maintainers process incoming issues and prioritize
the work required to address the feedback raised. These labels help us to track
the flow of an issue through this process

|                                               | Label name                       | Description |
| --------------------------------------------- | ---------------------------------| ----------- |
| [:mag_right:][status:confirmed-bug]           | `status:confirmed-bug`           | Confirmed bugs or reports that are very likely to be bugs |
| [:mag_right:][enhancement]                    | `enhancement`                    | Issues that propose to improve the app and solve a problem for users |
| [:mag_right:][status:investigation-needed]    | `status:investigation-needed`    | Likely bugs, but haven't been reliably reproduced by a reviewer |
| [:mag_right:][status:more-information-needed] | `status:more-information-needed` | The submitter needs to provide more information about the issue |
| [:mag_right:][impact:priority-1]              | `impact:priority-1`              | Major bug affecting large population and inhibiting their work |
| [:mag_right:][impact:priority-2]              | `impact:priority-2`              | Bug that affects more than a few users in a meaningful way but doesn't prevent core functions |
| [:mag_right:][impact:priority-3]              | `impact:priority-3`              | Bugs that affect small number of users and/or relatively cosmetic in nature |
| [:mag_right:][support]                        | `support`                        | Issues specific to an individual users' configuration requiring diagnosis and clarification to resolve |

### External contributions

We use these labels to identify work that is ideal for external contributors to
get involved with.

|                                 | Label name         |  Description |
| ------------------------------- | ------------------ |  ----------- |
| [:mag_right:][good first issue] | `good first issue` | Issues marked as ideal for a brand new contributor to start with |
| [:mag_right:][help wanted]      | `help wanted`      | Issues marked as ideal for external contributors |

### Planning

We use these labels to track tasks outside the usual flow of addressing bugs or
implementing features:

|                                          | Label name                  |  Description |
| ---------------------------------------- | --------------------------- |  ----------- |
| [:mag_right:][meta]                      | `meta`                      | Issues used to co-ordinate tasks or discuss a feature before the required work is captured |
| [:mag_right:][user-research]             | `user-research`             | Issues that may benefit from user interviews, validations, and/or usability testing |
| [:mag_right:][status:needs-design-input] | `status:needs-design-input` | Issues that require design input from the core team before the work can be started |

### Specialized areas

We use these labels to identify issues related to a specific area or the app,
or a specific subset of users:

|                                  | Label name          | Description |
| -------------------------------- | ------------------- | ----------- |
| [:mag_right:][area:codemirror]   | `area:codemirror`   | Issues related to our use of [CodeMirror](https://codemirror.net/) that may require upstream fixes |
| [:mag_right:][area:electron]     | `area:electron`     | Issues related to our use of [Electron](https://electronjs.org) that may need updates to Electron or upstream fixes |
| [:mag_right:][area:integrations] | `area:integrations` | Issues related to editor and shell integrations that ship in Desktop |
| [:mag_right:][area:performance]  | `area:performance`  | Relating to things affecting performance |
| [:mag_right:][area:themes]       | `area:themes`       | Issues related the light or dark themes that ship in Desktop |
| [:mag_right:][area:website]      | `area:website`      | Issues that relate to external websites and require co-ordination to resolve |

### Environments

Sometimes issues are isolated to a specific operating system. We use these
labels to help identify these issues, so maintainers with that setup - or
experience with that setup - can easily find them in the issue tracker.

|                                 | Label name          | Description |
| ------------------------------- | ------------------- | ----------- |
| [:mag_right:][platform:linux]   | `platform:linux`    | Issues specific to Desktop usage on Linux |
| [:mag_right:][platform:macOS]   | `platform:macOS`    | Issues specific to Desktop usage on macOS |
| [:mag_right:][platform:windows] | `platform:windows`  | Issues specific Desktop usage on Windows |


## Pull Request-specific labels

These labels should only be assigned to pull requests, and are intended to help
reviewers navigate the open contributions to identify how best to spend their
time:

|                                        | Label name                | Description |
| -------------------------------------- | ------------------------- | ----------- |
| [:mag_right:][status:ready-for-review] | `status:ready-for-review` | Pull Requests that are ready to be reviewed by the maintainers |
| [:mag_right:][status:time-sensitive]   | `status:time-sensitive`   | Pull Requests that require review in a more timely manner      |


[status:confirmed-bug]: https://github.com/desktop/desktop/labels/status%3Aconfirmed-bug
[area:codemirror]: https://github.com/desktop/desktop/labels/codemirror
[area:docs]: https://github.com/desktop/desktop/labels/docs
[area:electron]: https://github.com/desktop/desktop/labels/electron
[enhancement]: https://github.com/desktop/desktop/labels/enhancement
[good first issue]: https://github.com/desktop/desktop/labels/good%20first%20issue
[help wanted]: https://github.com/desktop/desktop/labels/help%20wanted
[area:infrastructure]: https://github.com/desktop/desktop/labels/infrastructure
[area:integrations]: https://github.com/desktop/desktop/labels/integrations
[status:investigation-needed]: https://github.com/desktop/desktop/labels/investigation-needed
[platform:linux]: https://github.com/desktop/desktop/labels/linux
[platform:macOS]: https://github.com/desktop/desktop/labels/macOS
[meta]: https://github.com/desktop/desktop/labels/meta
[status:more-information-needed]: https://github.com/desktop/desktop/labels/more-information-needed
[status:needs-design-input]: https://github.com/desktop/desktop/labels/needs-design-input
[area:performance]: https://github.com/desktop/desktop/labels/performance
[impact:priority-1]: https://github.com/desktop/desktop/labels/priority-1
[impact:priority-2]: https://github.com/desktop/desktop/labels/priority-2
[impact:priority-3]: https://github.com/desktop/desktop/labels/priority-3
[status:ready-for-review]: https://github.com/desktop/desktop/labels/ready-for-review
[support]: https://github.com/desktop/desktop/labels/support
[area:tech-debt]: https://github.com/desktop/desktop/labels/tech-debt
[area:themes]: https://github.com/desktop/desktop/labels/themes
[status:time-sensitive]: https://github.com/desktop/desktop/labels/time-sensitive
[status:user-research]: https://github.com/desktop/desktop/labels/user-research
[area:website]: https://github.com/desktop/desktop/labels/website
[platform:windows]: https://github.com/desktop/desktop/labels/windows
