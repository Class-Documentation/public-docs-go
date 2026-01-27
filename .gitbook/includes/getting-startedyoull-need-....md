---
title: Getting startedYou’ll need ...
---

{% stepper %}
{% step %}
**Getting started**

You’ll need to [create an account](https://app.gitbook.com/join) before you can get started with your first documentation site.

After creating your account, you’ll automatically see a new docs site that’s ready for you to edit and customize. Choose how you want to add content to your site before you publish from the on-screen options.

{% hint style="success" %}
Your content isn’t published yet — so you can edit, customize and preview your docs site before making it live. Hit **Publish** to make it live immediately.

<i class="fa-arrow-down">:arrow-down:</i> [Jump to the ‘Publishing’ section on this page](#publish-your-documentation)
{% endhint %}
{% endstep %}

{% step %}
**Edit your content**

There are two ways to edit and update your content in GitBook — in our visual editor, or following a docs-as-code workflow. **You can choose one, or use a combination of both**.

Whichever workflow you prefer, you’ll edit your content using a **branch-based editing flow**. Find out more on [the Concepts page](../../getting-started/concepts.md).

<details>

<summary>Use the visual editor</summary>

GitBook’s what-you-see-is-what-you-get (WYSIWYG) editor lets you edit content visually, drag content blocks to reorganize them and see how your content will look as you work.

This visual editing workflow is ideal for users who don’t want to work in a code editor, or who have experience working with tools like Notion or Google Docs.

**1. Edit your docs in a change request**

First, find your docs site in the sidebar and click the item below it. This takes you to the space where your content lives.

Click **Edit** in the top-right. This opens a change request where you can edit the content of the space.

Click **Add new…** in the table of contents on the left-hand side to add a page, and give it a title.

<div data-with-frame="true"><figure><img src="../assets/25_11_13_change_request.png" alt="A screenshot of the Editor in the GitBook app, zoomed in to show the menu that lets you add new pages, groups, links and more to a GitBook space."><figcaption></figcaption></figure></div>

**2. Preview your changes**

Along the top of the web app you’ll see tabs for **Editor**, **Changes** and **Preview**. These switch between different views for your content.

Click **Preview** to see a live preview of what your docs site will look like with all the changes in your change request, on both desktop and mobile.

<div data-with-frame="true"><figure><img src="../assets/25_11_13_site_preview@2x.png" alt="A screenshot of the GitBook app with the Preview tab open, showing a docs site being previewed on a mobile-size display"><figcaption></figcaption></figure></div>

**3. Merge your changes**

Once you’re happy with your changes, click the **Merge** button in the top-right corner.

This will update the primary version of your content with all the edits from the change request. If the content is part of a live docs site, the site will be updated immediately.

</details>

<details>

<summary>Code-based editing</summary>

Sync your documentation with a GitHub or GitLab repository to enable code-based editing. Once synced, you can edit your docs in your existing developer environment.

This workflow is ideal for technical users who don’t want to switch tools and prefer to manage their documentation alongside other code.

**1. Set up Git Sync**

If you haven’t already set up Git Sync when creating your site, first find your docs site in the sidebar and click the name of the content below it. This takes you to the space where your content lives.

Click the **Set up Git Sync** button in the top-right and follow the instructions to sync your space to your chosen Git repository.

Head to the [Git Sync pages](../../getting-started/git-sync/) to find out more.

**2. Edit your docs from your developer environment**

Once you’ve synced your space to your Git repository, you can update the content of your docs from that repository in your development environment.

Open the repository, create a pull request and make the changes you want.

{% hint style="info" %}
### Markdown editing

GitBook supports [Markdown editing](../../creating-content/formatting/markdown.md), so you can create and format content using common syntax.

Every standard block in GitBook can be written and formatted using Markdown syntax.
{% endhint %}

**3. Preview your changes**

You can [preview your changes](../../getting-started/git-sync/github-pull-request-preview.md) on your published docs site from the pull request in GitHub or GitLab.

In your pull request, you’ll see a status with a unique preview URL. Click **Details** on that status to open the preview URL and see how your site will look when the pull request is merged and your site is updated.

**4. Merge your changes**

You’re good to go. Merge your pull request and your content will be updated both in the GitBook app and on your docs site, if it’s live.

In the GitBook app, every commit and your merged pull request will be synced to your space as updates in the version history.

<div data-with-frame="true"><figure><img src="../assets/25_10_13_github_history@2x.png" alt="A screenshot of the GitBook app showing the version history side panel open. In the side panel the highlighted entry shows a pull request from GitHub that was merged as part of the history, with a link to view the pull request on GitHub."><figcaption></figcaption></figure></div>

</details>
{% endstep %}

{% step %}
**Customize your docs**

<details>

<summary>Organize your site navigation</summary>

You can add more content to your site — such as an API reference, a help center or a changelog — at any time. When you add content, you can organize your site’s navigation bar to help users easily find what they’re looking for.

Head to [the Concepts page](../../getting-started/concepts.md) to find out more about site navigation.

Head to [the Site structure page](../../publishing-documentation/site-structure/) to find out more about adding content to your site.

<div data-with-frame="true"><figure><img src="../assets/25_11_13_site_navigation@2x.png" alt="A screenshot of a published docs site hosted on GitBook. The top of the site has a navigation bar, and the cursor is hovering over a drop-down in that bar, with a submenu open below it showing links to more pages"><figcaption></figcaption></figure></div>

</details>

<details>

<summary>Customize the look and feel of your docs site</summary>

Your docs site will look great out of the box, but you can also customize many settings that change the look and feel of your published site.

You can customize your site’s [logo, colors and font](../../publishing-documentation/customization/icons-colors-and-themes.md), add to your site navigation bar using [site sections](../../publishing-documentation/site-structure/site-sections.md) and [variants](../../publishing-documentation/site-structure/variants.md), update your [site’s visibility](../../publishing-documentation/site-settings.md#audience) settings and much more.

<div data-with-frame="true"><figure><img src="../assets/25_07_16_customization_demo.png" alt="An illustration showing five docs sites hosted in GitBook, each with distinct visual customizations"><figcaption></figcaption></figure></div>

</details>
{% endstep %}

{% step %}
**Publish your documentation**

<details>

<summary>Publish your docs</summary>

You can publish your site with a click at any time.

Open your site’s dashboard by clicking the site’s name in the sidebar. Then click **Publish** in the top-right corner to make it live.

Once your site is live, the dashboard will update with a link to the live site.

<div data-with-frame="true"><figure><img src="../assets/25_11_13_site_dashboard@2x.png" alt="A screenshot of the GitBook app showing a dashboard for a docs site. The dashboard shows the public URL, site status, site content, some top-level analytics for the site, and other options in tabs along the top of the screen."><figcaption></figcaption></figure></div>

{% hint style="success" %}
Want to explore publishing in more detail? Check out [our complete guide to creating and publishing content in GitBook](https://app.gitbook.com/s/LBGJKQic7BQYBXmVSjy0/editing-and-publishing-documentation/complete-guide-to-publishing-docs-gitbook).
{% endhint %}

</details>

<details>

<summary>Add a custom domain</summary>

By default, you site will be published with a unique URL with this format:

```
https://[organization-name].gitbook.io/[site-title]
```

While this may be suitable for some teams, many choose to change their URL to [a custom domain](../../publishing-documentation/custom-domain.md) or [a custom subdirectory](../../publishing-documentation/setting-a-custom-subdirectory/).

To do this, open your site dashboard by clicking the site’s name in the sidebar, then open the **Settings** tab and choose **Domain and URL**.

<figure><img src="../assets/25_11_13_custom_domain@2x.png" alt="A screenshot of the GitBook app showing the menu that guides you through the process of setting up a custom domain for your docs site."><figcaption></figcaption></figure>

Use the buttons on the screen to choose the option you want, and follow the instructions to configure the DNS settings with your domain provider.

{% hint style="info" %}
It can take up to 48 hours for your DNS changes to take effect — although they typically propagate much faster.
{% endhint %}

</details>
{% endstep %}
{% endstepper %}
