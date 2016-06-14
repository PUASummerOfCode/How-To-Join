# How-To-Join
Methods of organizing our work and documenting it for others to join in.

0) Learn to use git and github.
  1. Signup on github.
  2. Download git (GUI or CLI, I use CLI).
  3. Pick a tutorial (there are many like https://try.github.io/levels/1/challenges/1, http://rogerdudler.github.io/git-guide/, recommended: https://www.udacity.com/course/how-to-use-git-and-github--ud775)
  4. Finish the tutorial and ask to join PUASummerOfCode through github.
  5. Pick teams depending on your preferred project(s).
  6. YOU'VE JOINED IN! Now let's do some real work!!

1) We need to establish a method of **initiating a project**, here are a few steps:
  1. Open a Directory (when applicable) with a proposed name (or a repository).
  2. Provide a README.md file like this with the idea in general.
  3. Update README.md with suggested features list. Team can add or comment through commits.
  4. Pick the simplest and core feature; mention it at the beginning to start working on it (feature 0).
  5. Prioritize the rest of the features for the team to take notice (give them numbers).

After Step 1, you would have the base.

2) We need to establish a method of **researching suggested features** of a project, here are a few steps:
  1. Create a new label from Issues->Labels->New Label called 'suggested feature' (different from feature request)
  2. Create an issue per each suggested feature with that label. Put initial description, interesting references, etc.
  3. When the feature is properly researched, design is needed.

After Step 2, you would have the details of each feature (including the base).

3) We need to establish a method of **designing researched features** of a project, here are a few steps:
  1. Pick a suitable and open design document style (UML for OOP, ERD for Databases, Wireframing for Websites)
  2. Detail it as much as you can, also make sure to tell everyone else how to edit it (which tool you're using)
  3. Finalizing the design can be done individually or through team effort as comments in issues.

After Step 3, you would have a design for your researched feature.

4) We need to establish a method of **implementing each design**, here are a few steps:
  1. Assign portions/parts of the design to team members through new issues.
  2. Agree on a method of implementation (programming language, coding styles, protocols, speeds etc.) in comments to issues.
  3. Start implementaion and try as much as you can to unit test before pushing!!

After Step 4, you would have a unit-tested implementation of your design.

5) We need to establish a method of **integrating implementations**, here are a few steps:
  1. I suggest that only one person (or a small limited group) would be allowed to accept pull requests and push changes to the main branch.
  2. The rest would fork the main branch and work on their own forks then when finished, they could make a pull request for integration. This should make things smoother and the main branch would not break.

After Step 5, you would have an integrated unit-tested implementation.

6) We need to establish methods of **Testing**, here are a few ***ideas***:
  1. Learn what testing methods are there.
  2. Learn what testing tools are there.
  3. Prepare test cases.
  4. Use automated test tools and nightly builds to verify.

After Step 6, you would have a tested build.

7) We need to establish methods of **Releasing the product**, here are a few ***ideas***:
  1. After a few feature updates, the team (or the head/leader/manager/supervisor) could start deciding whether to release or not
  2. Any development code/system should be dropped and the product should be made as compact as possible for the target device(s)/platform(s).
  3. Make a new release.
