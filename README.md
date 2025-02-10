# EBT-Site3

This is the repository template for SC-Voice.net language-specific websites.

[View template web site](https://ebt-site.sc-voice.net)

## Instructions

### Github Account

To create a language-specific ${appName} website, you'll need a
[Github account](https://docs.github.com/en/get-started/signing-up-for-github/signing-up-for-a-new-github-account) (Note: a free account is fine).
Your Github account will own and administer the new website.
The new website will share the SC-Voice.net API servers with other websites.

### Create an Organizational Account

For collaborative administration,
you new website will need a Github
[organizational account](https://docs.github.com/en/organizations/collaborating-with-groups-in-organizations/creating-a-new-organization-from-scratch).
An organizational account will help you work with others
on content creation.

### Account Settings

Your new website relies on 
[Github Actions](https://github.com/features/actions)
for updating content and software.
Navigate to your Github account and click <kbd>Settings</kbd>
In the left navbar, open the <kbd>Actions</kbd> panel.
Then select <kbd>General</kbd> and scroll down to 
_Workflow Permissions_.
Update workflow permissions as follows:

<a href="https://ebt-site.sc-voice.net/img/account-settings.png">
  <img style="height: 50%"
    src="https://ebt-site.sc-voice.net/img/account-settings.png" />
</a>

Click <kbd>Save</kbd> to update your workflow permissions.

### Create new repository

1. Login to Github
1. Then click the <kbd>Use this template</kbd>
button, and choose <kbd>Create new repository</kbd>.

<img src="https://ebt-site.sc-voice.net/img/use-this-template.png" />. 

### Configure new repository

After clicking <kbd>Create new repository</kbd>,
you'll see a new webpage form for you to fill out:

1. Specify the new repository name (e.g., "my-ebt-site")
1. Choose <kbd>Public</kbd> repository (free)
1. Select <kbd>Include all branches</kbd>
1. Review your form entries
1. When ready, click ```Create repository from template```

We now need to enable Github pages for your new repository.

### Enable Github pages

Navigate to your new repository and click <kbd>Settings</kbd>.
Then click the "Pages" link in the left navigation bar.
Configure the ```Build and deployment``` settings as shown below:

<a href="https://ebt-site.sc-voice.net/img/github-pages.png">
<img src="https://ebt-site.sc-voice.net/img/github-pages.png" style="width:35em">
</img>
</a>. 

Also verify that your repository has the following settings for
<kbd>Actions</kbd> <kbd>General</kbd>:

<a href="https://ebt-site.sc-voice.net/img/account-settings.png">
  <img style="height: 50%"
    src="https://ebt-site.sc-voice.net/img/account-settings.png" />
</a>

Next, you'll need to edit the EBT-Site configuration.
You won't be able to view your new website until you have configured it correctly.
See [EBT site configuration](#/wiki/design/config).

