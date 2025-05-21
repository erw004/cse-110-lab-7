# Eric Wang

1) You would fit your automated tests within a Github action that runs whenever code is pushed because you want to make sure that the changes you made work and don't deprecate other functionalities.

2) No, you would not use an end to end test because we want to design end to end tests for user navigation from start to finish instead of focusing on whether one function or step returns the correct output.

3) The difference between navigation and snapshot mode is that in navigation mode, user navigation of the webpage is simulated.

4) Three things to improve performance could be:
   - Properly size images
   - Serve images in next-gen formats
   - Add `<meta name="viewport">` tag with `width` or `initial-scale`







