<header>

<!--
  <<< Author notes: Course header >>>
  Read <https://skills.github.com/quickstart> for more information about how to build courses using this template.
  Include a 1280×640 image, course name in sentence case, and a concise description in emphasis.
  In your repository settings: enable template repository, add your 1280×640 social image, auto delete head branches.
  Next to "About", add description & tags; disable releases, packages, & environments.
  Add your open source license, GitHub uses the MIT license.
-->

# Create a release based workflow

_Create a release based workflow that is built on the foundations of the GitHub flow._

</header>

<!--
  <<< Author notes: Step 2 >>>
  Start this step by acknowledging the previous step.
  Define terms and link to docs.github.com.
-->

## Step 2: Add a new feature to the release branch

_Great job creating a beta release :heart:_

### Release management

As you prepare for a future release, you'll need to organize more than the tasks and features. It's important to create a clear workflow for your team, and to make sure that the work remains organized.

There are several strategies for managing releases. Some teams might use long-lived branches, like `production`, `dev`, and `main`. Some teams use simple feature branches, releasing from the main branch.

No one strategy is better than another. We always recommend being intentional about branches and reducing long-lived branches whenever possible.

In this exercise, you'll use the `release-v1.0` branch to be your one long-lived branch per release version.

### Protected branches

Like the `main` branch, you can protect release branches. This means you can protect branches from force pushes or accidental deletion. This is already configured in this repository.

### Add a feature

Releases are usually made of many smaller changes. Let's pretend we don't know about the bug we added earlier and we'll focus on a few features to update our game before the version update.

- You should update the page background color to black.
- I'll help you change the text colors to green.

### :keyboard: Activity: Update `base.css`

1. Create a new branch off of the `main` branch and change the `body` CSS declaration in `base.css` to match what is below. This will set the page background to black.

```
body {
    background-color: black;
}
```

1. Open a pull request with `release-v1.0` as the `base` branch, and your new branch as the `compare` branch.
1. Fill in the pull request template to describe your changes.
1. Click **Create pull request**.

### Merge the new feature to the release branch

Even with releases, the GitHub flow is still an important strategy for working with your team. It's a good idea to use short-lived branches for quick feature additions and bug fixes.

Merge this feature pull request so that you can open the release pull request as early as possible.

### :keyboard: Activity: Merge the pull request

1. Click **Merge pull request**, and delete your branch.
1. Wait about 20 seconds then refresh this page (the one you're following instructions from). [GitHub Actions](https://docs.github.com/en/actions) will automatically update to the next step.

<footer>

<!--
  <<< Author notes: Footer >>>
  Add a link to get support, GitHub status page, code of conduct, license link.
-->

---

Get help: [Post in our discussion board](https://github.com/orgs/skills/discussions/categories/release-based-workflow) &bull; [Review the GitHub status page](https://www.githubstatus.com/)

&copy; 2023 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)

</footer>


Xin Chao!!!
我是黄文和。
我是越南人。

