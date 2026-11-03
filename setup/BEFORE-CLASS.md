# Set up your individual workspace before class

Use your own GitHub account and your own fork. Class repository: https://github.com/vtaerodoctor-hokie/2145211-2026-uav-investigation. Do not enter passwords or access tokens in chat, worksheets or repository files.

## 1 Create your fork
Open the class repository in GitHub and select **Fork**. Choose your own account and create the fork from the default branch. Check that the repository owner shown at the top is your username. Bookmark both your fork and the instructor's repository.

## 2 Connect ChatGPT
In ChatGPT, look in **Settings → Plugins → GitHub** (some interfaces may use Apps). Connect your GitHub account and select only the repository access you need for this lesson, including your fork. Check the permission screen before accepting it. Never assume a public repository is automatically selected for the connection.

Availability and read/write features vary by account, plan and ChatGPT experience. A connection that can retrieve files may not be able to commit changes. Do not purchase an upgrade for this lesson without discussing the issue with the instructor. A browser-only GitHub route and released-file upload route are available.

If GitHub is not available in ordinary chat, check the available deep-research or agent tool selector. Availability differs by account/workspace. A newly created fork can take several minutes to appear; check the connected GitHub account and selected repositories, then retry. Do not repeatedly change broad permissions. If still unavailable, use the fallback below.

If you prefer another AI tool, arrange and test your own connection before class. The guided demonstration will use ChatGPT.

## 3 Prove that you can read the right files
Paste this prompt after replacing the repository URL:

> Read `README.md` and `MISSION.md` in my fork at [paste your fork URL]. Tell me the repository owner, the exact file paths you accessed, and the requested mapping area. Quote one short sentence from the mission brief. If you cannot access the files, say so instead of guessing. Do not make any changes.

Compare the answer with the files in GitHub. A confident answer is not proof of access. Record whether the test passed and what you compared; share any setup problem privately with the instructor before class.

## 4 Prove that data analysis works
Complete [the harmless CSV practice](DATA-PRACTICE.md): six data rows, a manually checked mean and a rendered plot. Verify the actual CSV, not just the AI's claim. Test the file-upload fallback too if repository retrieval does not make the full CSV available to analysis. This practice contains no mission evidence.

## 5 Practice a small save
Open `work/setup-check.md` in your fork using GitHub's pencil/edit control. Record that you checked the mission brief. Preview the change, then commit it to your fork with a short message such as `Complete setup check`. Do not put your student ID or personal details in this public file.

If your AI experience supports writing, you may instead ask it to propose this small change. Read the diff before approving the commit. Do not give it broad permission to overwrite files or change repository settings.

## 6 Receive a release during class
The instructor adds only the selected package to the upstream `main` branch under `evidence/`, and updates `RELEASE-STATUS.md` with its version and paths. A GitHub Release attachment alone does not appear through Sync fork; use its announced download route if instructed.

1. Open your fork's `main` branch on GitHub. First commit any browser edits and note your existing `work/setup-check.md` text.
2. Select **Sync fork**, review the upstream changes, then **Update branch** when the instructor announces a release.
3. Open `RELEASE-STATUS.md` and compare the announced version and exact package paths. Confirm the files exist and your own work note is still present. “Up to date” alone is not proof that the expected release is present.
4. Ask your AI tool to retrieve the newly released file by exact path and current version. Verify one row/value yourself. Old chat context may still contain old data; provide the current file if needed.
5. If you use a local clone or separate AI workspace, update that copy too without resetting or discarding your work. Syncing GitHub does not automatically refresh every local copy.

For a setup rehearsal, an instructor-announced harmless upstream marker change can be synced after your practice-note commit. Record the old/new marker and preservation of your note. If no new upstream change exists, mark the rehearsal **not yet tested**, not passed. Do not request an early mission package just to test syncing.

If GitHub reports a conflict, stop and ask for help. Do not choose a discard/reset option that may erase your work. Instructor files and your notes are kept in separate folders to reduce conflicts, but that is not a guarantee.

## Fallback
Download only the instructor's released package and upload the relevant file to your AI tool, or follow the instructor's analysis with a partner. Preserve your individual paper answer and explanation. Do not upload private student records or credentials.

## Official reference links
- [Connect GitHub to ChatGPT](https://help.openai.com/en/articles/11145903-connecting-github-to-chatgpt)
- [Sync a fork](https://docs.github.com/en/pull-requests/how-tos/work-with-forks/syncing-a-fork)
- [About fork permissions and visibility](https://docs.github.com/en/pull-requests/reference/forks)

Instructions checked November 4, 2026 Bangkok. Interfaces may differ; report what you see rather than inventing a missing button.
