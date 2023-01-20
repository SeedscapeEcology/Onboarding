# Source Code, Data, and Reproducibility

**Pride:** We expect lab members to sign their code.
To quote from _The Pragmatic Programmer_:

> Craftsmen of an earlier age were proud to sign their work.
You should be, tooÉ
People should see your name on a piece of code and expect it to be solid, well written, tested, and documented.

While some code will be proof-of-concept code, it should be of a form that inspires confidence.

**Version Control Services:** Our primary version control service is GitHub, and we have a [`Seedscape Ecology` account](https://github.com/SeedscapeEcology) there.
We expect that group members will maintain their code in repositories under these team accounts.
However, group members should not commit to the branch that is shown as default on GitHub for any of these repositories.
Instead commits happen as described below to facilitate code review.

**Creating a Seedscape Ecology Repository:**

1.  Create a repository under the team account.
2.  Immediately fork this repository into one that your user account owns.
3.  Make commits to your own repository, and move code back to the `Seedscape Ecology` repository as described below.

**Getting Code into Seedscape Ecology Repositories:** Code moves from user repositories to `Seedscape Ecology` repositories through a process of code review.
Code review is handled through pull requests.
The process is described briefly below.
Feel free to ask for guidance if you are uncomfortable with the process.
**We will revoke write access for failing to adhere to these rules.**

1.  Make changes to your code and commit them in your own repository first.
2.  Create a pull request into the repository owned by Seedscape Ecology.
3.  Name potential reviewers for your pull request.
4.  Once at least one lab member has approved your pull request, you or a reviewer may merge your pull request.
The exceptions to this policy are the "Onboarding" and "Policies" repositories where, in addition to the above rules, Noelle must also approve the pull request.

**Composition of Pull Requests:** Each pull request may contain one or more changesets.
In keeping with good source control practice, each changeset or commit should contain *all* changes necessary for a particular fix or update.
In addition, each pull request should relate to no more than one functional area in the code base you are updating.
Keeping the pull request focused to one area makes it easier for your reviewers to provide thoughtful feedback.

**Reviewing Pull Requests:** We expect that all lab members will participate in review of pull requests.
If you get named by the submitter, it's courteous to review the request.
We have created a checklist to facilitate review.
As a reviewer, you are responsible for making sure that all [checklist guidelines](https://github.com/SeedscapeEcology/Onboarding/blob/master/code-review-checklist.md) are followed.

**Projects that didn't work:** We expect that repositories will contain failures (e.g. proof-of-concepts that didn't work).
This is ideal.
Being able to find them will make sure we don't make the same failure twice.

**Non-Code Versioning:** Non-code documents should be kept in a place that maintains version history (e.g. Box for word documents and data). We maintain a Box account through USU for these purposes. Please do not delete data files from Box. If you leave a project, please transfer ownership to someone who is still on the project; this will need to be done for each folder/file you created/uploaded. 

**Data Management:** For publicly available data, scripts used to download and process these data should be preserved, as should the versions of items used in processing (e.g. demographic or functional trait data).
These items should be version controlled.
Where possible, intermediate files of reasonable size can be stored to facilitate re-use, but the process to regenerate these files from publicly available data should be preserved.
When we generate data, they should be stored in a location where they are replicated and uploaded to the relevant database as soon as possible (e.g. Knowledge Network for Biocomplexity, Dryad Digital Repository).

**Reproducibility:** We expect all lab members to maintain code that performs reproducible analyses.
This can be in the form of makefiles, shell scripts, or other automation approaches that allow analyses to be automatically performed.
We expect that these scripts, including those to generate figures in papers generated as a consequence of such analyses, will be included in source control repositories (see "Getting Code into Seedscape Ecology Repositories) and made publicly available before or concurrent with the submission of preprint (if submitted) or manuscripts.
Combined with the review guidelines, this means that all code must have been reviewed for these documents to be submitted.

> The material in these guidelines is derived from "[Greene Lab Onboarding Repository](https://github.com/greenelab/onboarding)" by Dr. Casey Greene and the Greene Lab team, used under [CC0 License](https://creativecommons.org/publicdomain/zero/1.0/legalcode.txt).


