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
- [ ] Add ESLint for stability.
- [ ] Add Flow for type-safe and null-safe.
- [ ] Internationalisation. currently I need `en` and `ja`. For the time being create `index.ja.pug`.
- [ ] Use React.js or Vue.js for template. This is for HMR and scoped CSS and internationalisation.
- [ ] Add script for build. Generate multilingual PDF to `/dist`.
- [ ] `screenshot` command Internationalisation.
- [ ] Create GitHub page or Netlify implementation to render this as actual web page.
