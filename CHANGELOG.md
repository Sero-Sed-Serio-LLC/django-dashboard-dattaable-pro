# Change Log

## [1.0.4] 2021-11-07
### Improvements

- Bump Django Codebase to [v2.0.4](https://github.com/app-generator/boilerplate-code-django-dashboard/releases)
  - `assets` & `templates` moved to `apps` folder
- Adeed Gulp tooling for SCSS compilation

## [1.0.3] 2021-09-09
### Improvements & Fixes

- Bump Django Codebase to [v2.0.2](https://github.com/app-generator/boilerplate-code-django-dashboard/releases)
  - Dependencies update (all packages)
  - Use Django==3.2.6 (latest stable version)
  - Better Code formatting
  - Improved Files organization
  - Optimize imports
  - Docker Scripts Update 
- Tooling
  - SCSS compilation via Gulp
  - Update README with build instructions: `Recompile CSS` section     
- Fixes: 
  - Patch 500 Error when authenticated users access `admin` path (no slash at the end)
  - Patch: Update sidebar to reflect the current page 
  - Patch [#16](https://github.com/app-generator/boilerplate-code-django-dashboard/issues/16): Minor issue in Docker 

## [1.0.2] 2020-03-22
### Fixes 

- Bump Codebase: [Django Dashboard](https://github.com/app-generator/boilerplate-code-django-dashboard) v1.0.4
- Bump UI: [Jinja Datta PRO](https://github.com/app-generator/jinja-datta-able-pro) v1.0.2

## [1.0.1] 2020-05-30
### Bug fixing, Improvements
- Add CHANGELOG.md to track all changes
- Patch - Error-404.html not used in all contexts
- Update LICENSE file - added more information regarding the app usage

## [1.0.0] 2020-05-01
### Initial Release
