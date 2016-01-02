# Contributing
Contributing guidelines for all @duyetdev project.

So, you want to contribute to this project! That's awesome. However, before
doing so, please read the following simple steps how to contribute. This will
make the life easier and will avoid wasting time on things which are not
requested. :sparkles:

## Discuss the changes before doing them
 - First of all, open an issue in the repository, using the **bug tracker**,
   describing the contribution you would like to make, the bug you found or any
   other ideas you have. This will help us to get you started on the right
   foot.

 - If it makes sense, add the platform and software information (e.g. operating
   system, Node.JS version etc.), screenshots (so we can see what you are
   seeing).

 - It is recommended to wait for feedback before continuing to next steps.
   However, if the issue is clear (e.g. a typo) and the fix is simple, you can
   continue and fix it.


## Fixing issues
 - Fork the project on Github and create a branch with your fix:
   `some-great-feature` or `some-issue-fix`.

 - Commit your changes in that branch, writing the code following the
   [code style][1]. If the project contains tests (generally, the `test`
   directory), you are encouraged to add a test as well. :memo:

 - If the project contains a `package.json` or a `bower.json` file add yourself
   in the `contributors` array (or `authors` in the case of `bower.json`;
   if the array does not exist, create it):

   ```json
   {
      "contributors": [
         "Your Name <and@email.address> (http://your.website)"
      ]
   }
   ```

## Creating a pull request

 - Open a pull request, and reference the initial issue in the pull request
   message (e.g. *fixes #<your-issue-number>*). Write a good description and
   title, so everybody will know what is fixed/improved.

 - If it makes sense, add screenshots, gifs etc., so it is easier to see what
   is going on.

## Wait for feedback
Before accepting your contributions, I will review them. You may get feedback
about what should be fixed in your modified code. If so, just keep committing
in your branch and the pull request will be updated automatically.

## Everyone is happy!
Finally, your contributions will be merged, and everyone will be happy! :smile:
Contributions are more than welcome!

Thanks! :sweat_smile:

[1]: https://github.com/duyetdev/node-style-guide
