---
stage: Govern
group: Compliance
info: To determine the technical writer assigned to the Stage/Group associated with this page, see https://handbook.gitlab.com/handbook/product/ux/technical-writing/#assignments
---

# Compliance frameworks report

DETAILS:
**Tier:** Ultimate
**Offering:** GitLab.com, Self-managed, GitLab Dedicated

> - [Introduced](https://gitlab.com/gitlab-org/gitlab/-/issues/422973) in GitLab 16.5 [with a flag](../../../administration/feature_flags.md) named `compliance_framework_report_ui`. Disabled by default.
> - In GitLab 16.4 and earlier, **Compliance frameworks report** referred to what is now called **Compliance projects report**. The formally-named **Compliance frameworks report** was [renamed to **Compliance projects report**](https://gitlab.com/gitlab-org/gitlab/-/issues/422963) in GitLab 16.5.
> - [Enabled by default](https://gitlab.com/gitlab-org/gitlab/-/merge_requests/140825) in GitLab 16.8.

FLAG:
On self-managed GitLab, by default this feature is available. To hide the feature an administrator to [disable the feature flag](../../../administration/feature_flags.md) named
`compliance_framework_report_ui`. On GitLab.com and GitLab Dedicated, this feature is available.

With compliance frameworks report, you can see all the compliance frameworks in a group. Each row of the report shows:

- Framework name.
- Associated projects.

The default framework for the group has a **default** badge.

## View the compliance frameworks report for a group

Prerequisites:

- You must be an administrator or have the Owner role for the group.

To view the compliance frameworks report:

1. On the left sidebar, select **Search or go to** and find your group.
1. Select **Secure > Compliance center**.
1. On the page, select the **Frameworks** tab.

## Create a new compliance framework

Prerequisites:

- You must be an administrator or have the Owner role for the group.

To create a new compliance framework from the compliance frameworks report:

1. On the left sidebar, select **Search or go to** and find your group.
1. Select **Secure > Compliance center**.
1. On the page, select the **Frameworks** tab.
1. Select the **New framework**.
1. Select the **Add framework** to create compliance framework.

## Edit a compliance framework

Prerequisites:

- You must be an administrator or have the Owner role for the group.

To edit a compliance framework from the compliance frameworks report:

1. On the left sidebar, select **Search or go to** and find your group.
1. Select **Secure > Compliance center**.
1. On the page, select the **Frameworks** tab.
1. Hover over framework and select **Edit the framework**.
1. Select the **Save changes** to edit compliance framework.

## Delete a compliance framework

Prerequisites:

- You must be an administrator or have the Owner role for the group.

To delete a compliance framework from the compliance frameworks report:

1. On the left sidebar, select **Search or go to** and find your group.
1. Select **Secure > Compliance center**.
1. On the page, select the **Frameworks** tab.
1. Hover over framework and select **Edit the framework**.
1. Select the **Delete framework** to delete compliance framework.
