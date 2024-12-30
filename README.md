# gh-actions-custom-artifact-upload-poc

## TODO:

- [x] template for *.vsix files in monorepo like structure
- [ ] github action to trigger on tag push
- [ ] identify the exact tag during the build
- [ ] translate the tag to a *.vsix file name 


## Questions:

- [x] How to handle packages which do not produce a *.vsix?
      - perhaps a more specific tags pattern for the artifact upload action?
- [ ] can github actions glob pattern by dynamic via env vars?
- [ ] how to access github actions current tag?

