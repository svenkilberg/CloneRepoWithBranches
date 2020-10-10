# CloneRepoWithBranches
How to clone a repo with more than one branch.

When cloning an repository from GtiHub that contains more branches than main, only main is tracked localy from the start.

To fix this do as follows:

The repository on GtiHub with three branches:

![0 github repo](https://user-images.githubusercontent.com/36561823/95650694-70baa200-0ae5-11eb-90ba-b3c3dd43b978.JPG)


Clone the repository to your local machine:

![1GitClone](https://user-images.githubusercontent.com/36561823/95650696-73b59280-0ae5-11eb-8748-616c0f64d598.JPG)


Change directory to the repository:

![2CdToRepo](https://user-images.githubusercontent.com/36561823/95650698-7617ec80-0ae5-11eb-8c3f-8ab4b8849d52.JPG)


If you type **_git branch_** only the main branch is shown as tracked localy:

![3GitBranchOnlyMain](https://user-images.githubusercontent.com/36561823/95650700-77e1b000-0ae5-11eb-9280-fabb98d1103a.JPG)


If you type **_git branch -a_** all branches are shown. You can see that Branch1 and Branch2 is not tracked localy:

![4GitBranchAAllBranches](https://user-images.githubusercontent.com/36561823/95650701-7a440a00-0ae5-11eb-8fac-2e182aada1f6.JPG)


To be able to work with Branch1 you have to do a checkout of the branch:

![5GitCheckoutBranch1](https://user-images.githubusercontent.com/36561823/95650704-7ca66400-0ae5-11eb-946f-5306e901d0c7.JPG)


Now if you type **_git branch_** you can see that booth Main and Branch1 is tracked localy:

![6GitBranchBoothMainAndBranch1](https://user-images.githubusercontent.com/36561823/95650706-7f08be00-0ae5-11eb-9240-42258ed6f6ef.JPG)


If you whant to work with Branch2, do a checkout on that to.


