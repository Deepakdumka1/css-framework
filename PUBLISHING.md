# Publishing QuantumCSS to npm

Here's my checklist for publishing this to npm when ready:

## Prerequisites

1. Create an npm account if you don't have one:
   - Go to [npmjs.com](https://www.npmjs.com) and sign up

2. Login to npm from terminal:
   ```bash
   npm login
   ```

## Before Publishing

1. Update version in package.json (follow semver)

2. Make sure the package.json contains:
   - Correct package name (should be `quantumcss`)
   - Version number
   - Description
   - Main file
   - Repository link
   - License info

3. Check what files will be included:
   ```bash
   npm pack --dry-run
   ```

4. Consider adding a .npmignore file to exclude unnecessary files

## Publishing

1. For first time publishing:
   ```bash
   npm publish --access=public
   ```

2. For updates:
   ```bash
   npm version patch # or minor or major
   npm publish
   ```

## After Publishing

1. Tag the release in git:
   ```bash
   git tag -a vX.X.X -m "Version X.X.X"
   git push origin vX.X.X
   ```

2. Update documentation to reflect the new version

3. Test installation:
   ```bash
   npm install quantumcss
   ```

## Notes to self

- Remember to remove personal comments from code before publishing
- Make sure builds are passing
- Update CDN links in README and docs
- Don't forget to update the homepage with the new version number