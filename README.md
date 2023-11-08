# 25340-2

Test Details:

1. Create a repo with single package and 2 labels A and B in renovate config
2. Renovate the repo ... now repo has an update PR with 2 labels A and B
3. Remove labels A and B and add labels C and D in renovate config
4. Renovate the repo ... now update PR should have 2 labels C and D

   INFO: Performing removal and addition in same run
