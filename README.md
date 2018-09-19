# Resume

Resume of Melusi Khumalo, built with Webpack + Pug + Postcss.

# Getting started

After checking out the repo, run:

```
yarn install
yarn start
```

open localhost:3000 and you can see my resume.

# Write your resume with this template

Feel free to write your resume with this template, if you are enough to do so.

- `src/app.postcss` is for css
- `src/index.pug` is for template
- If you want to write your resume with sass, just add `sass-loader`

# Screenshot

To take a screenshot, just run

- `yarn start`
- `yarn screenshot`

This runs your Chrome headlessly and take an image.

# TODO

- [x] Add script for taking screenshot.
- [x] Add Gitbook for styled README file.
- [ ] Add ESLint for stability.
- [ ] Add Flow for type-safe and null-safe.
- [ ] Use React.js or Vue.js for template. This is for HMR and scoped CSS and internationalisation.
- [ ] Add script for build. Generate multilingual PDF to `/dist`.
- [ ] `screenshot` command Internationalisation.
- [ ] Create GitHub page or Netlify implementation to render this as actual web page.

# Lighthouse

- [ ] Does not respond with a 200 when offline
- [ ] User will not be prompted to Install the Web App - Failures: No manifest was fetched, Site does not register a service worker.
- [ ] Does not redirect HTTP traffic to HTTPS
- [ ] Does not register a service worker
- [ ] Is not configured for a custom splash screen - Failures: No manifest was fetched.
- [ ]Address bar does not match brand colors - Failures: No manifest was fetched.
