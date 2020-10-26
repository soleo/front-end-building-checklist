# Front End Feature Building Checklist

## Before Building

- [ ] Have clear idea of the business requirements
- [ ] Get UX/UI designer's mock ups and understand what the designer's visions are, and how they fit in our current design system
- [ ] Understand the current design system, and what are the possible impacts for current layouts

## During Development Process

- [ ] Have conistent naming convention, preferablly enforced by a linter (e.g. eslint)
- [ ] Used preferred way for layouts (grid > flexbox > absolute/relative position)
- [ ] Consolidate similar elements or make them re-usable
- [ ] The boy scout rule: everywhere you touched is cleaner than before
- [ ] (SOLID)[https://en.wikipedia.org/wiki/SOLID] and (DRY)[https://en.wikipedia.org/wiki/Don%27t_repeat_yourself]?

## Before Testing/QA

- [ ] Created pull request for code review
- [ ] Check in different browsers (Check on Chrome, FireFox, Safari, Edge)
- [ ] Check in native apps (iOS/Android)
- [ ] Works well in different break points (Mobile, Tablet, Desktop) and different length of text sizes
- [ ] Check voice over in Safari for your feature
- [ ] Profile in ChromeDevTool to see any performance issues
- [ ] Check color contrast
- [ ] Add unit tests to your feature
- [ ] Add documentation for future/peer developers

## Before Deployment

- [ ] Feature branch is synchronized with master
- [ ] Add configuration changes

## After Deployment

- [ ] 🎉 Celebrate and watch what kind of impact/usage the feature going to bring.


