Open questions:
- What are rules? What are aspects? What's the difference?
- What's the purpose/advantage of bazel's client/server mechanism?
- What are modules? (How does a module extend the workspace?)
- How do we add a new module and how do you add a a new registry?
- What are `Make Variables`? -> https://bazel.build/reference/be/make-variables
- What are the 3 phases of bazel?
- How does the Starlark debugger work? Can we use it effectively in the ADA? (e.g. https://docs.stack.build/docs/vscode/debugger/)
- How does select work? https://bazel.build/versions/7.1.0/docs/configurable-attributes -> Implement a dummy variant

Continue here next time:
    [Cheat Sheet Appendix](https://pace-docs.azurewebsites.net/pace/main/docs/developer/design_and_develop/software_development_with_bazel/bazel_cheatsheet.html#appendix)
        -> https://bazel.build/reference/be/common-definitions#label-expansion continue with "deps"

Useful links:
- https://bazel.build/concepts
- Bazel user guide - basics
  - Start with: https://bazel.build/build/style-guide
  - Continue with other topics from here: https://bazel.build/docs
- Bazel query
  - The Bazel Query Reference https://bazel.build/query/language
  - Query Guide https://bazel.build/query/guide
