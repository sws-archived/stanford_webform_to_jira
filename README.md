#[Stanford Webform to Jira](https://github.com/SU-SWS/stanford_webform_to_jira)
##### Version: 7.x-1.x

Maintainers: [jbickar](https://github.com/jbickar), [sherakama](https://github.com/sherakama)
[Changelog.txt](CHANGELOG.txt)

Drupal Features module for pulling creating forms with webform that can be directly submitted to a Jira project.



Installation
---

Install this module like any other module. [See Drupal Documentation](https://drupal.org/documentation/install/modules-themes/modules-7)

Configuration
---

1. Connect to Jira through the Jira Rest module  configuration page. admin/config/services/jira_rest. You may want to create a user in Jira for this connection.

2. Create a webform and add some components.
Must have a summary and a project key component. The project component should be a hidden field with the project's short name as the value. eg: BASIC

3. Enable Jira submission on the form settings tab of the webform. eg: node/[123]/webform/configure.

4. Choose the default issue type.
This setting in on the form settings page for the webform and should be set to the name (case-sensitive) value of the issue type you want to create.

Troubleshooting
---

If you are experiencing issues with this module try reverting the feature first. If you are still experiencing issues try posting an issue on the GitHub issues page.

Contribution / Collaboration
---

You are welcome to contribute functionality, bug fixes, or documentation to this module. If you would like to suggest a fix or new functionality you may add a new issue to the GitHub issue queue or you may fork this repository and submit a pull request. For more help please see [GitHub's article on fork, branch, and pull requests](https://help.github.com/articles/using-pull-requests)
