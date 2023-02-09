# Change Log

## [1.0.10] 2023-02-09
### Changes

- Bump UI: [Django AdminLTE](https://github.com/app-generator/django-admin-adminlte) `v1.0.5`
  - `AdminLTE v3.2.0` is fully integrated 

## [1.0.9] 2023-02-04
### Changes

- `Fix Docker` Execution
  - `Update Settings`: ALLOWED_HOSTS, CSRF_TRUSTED_ORIGINS `sections`

## [1.0.8] 2023-02-04
### Changes

- Bump UI: [Django AdminLTE](https://github.com/app-generator/django-admin-adminlte) `v1.0.4`
- DOCS Update (readme). New sections:
  - `How to customize the theme`
  - Render deployment
- Configure the project to use `home/templates`
- Added `custom-footer` sample

## [1.0.7] 2023-01-09
### Changes

- Move to theme-based pattern
  - [Django AdminLTE](https://github.com/app-generator/django-admin-adminlte) `v3.2.0`
- 🚀 `Deployment` 
  - `CI/CD` flow via `Render`

## [1.0.6] 2022-05-30
### Improvements

- Built with [AdminLTE Generator](https://appseed.us/generator/adminlte/)
  - Timestamp: `2022-05-30 20:42`

## [1.0.5] 2022-01-16
### Improvements

- Bump Django Codebase to [v2stable.0.1](https://github.com/app-generator/boilerplate-code-django-dashboard/releases)
- Dependencies update (all packages) 
  - Django==4.0.1
- Settings update for Django 4.x
  - `New Parameter`: CSRF_TRUSTED_ORIGINS
    - [Origin header checking isn`t performed in older versions](https://docs.djangoproject.com/en/4.0/ref/settings/#csrf-trusted-origins)  

## [1.0.4] 2021-10-07
### Improvements

- Bump Django Codebase to [v2.0.4](https://github.com/app-generator/boilerplate-code-django-dashboard/releases)
- Codebase update
  - `assets` & `templates` moved to `apps` folder
  - `apps/base` renamed to `apps/home`

## [1.0.3] 2021-09-12
### Improvements & Fixes

- Bump Django Codebase to [v2.0.2](https://github.com/app-generator/boilerplate-code-django-dashboard/releases)
  - Dependencies update (all packages)
    - Use Django==3.2.6 (latest stable version)
  - Better Code formatting
  - Improved Files organization
  - Optimize imports
  - Docker Scripts Update 
- Tooling: 
  - Aded Gulp compilation script
- Revert the license to MIT    
- Fixes: 
  - Patch 500 Error when authenticated users access `admin` path (no slash at the end)
  - Patch [#16](https://github.com/app-generator/boilerplate-code-django-dashboard/issues/16): Minor issue in Docker 

## [1.0.2] 2021-02-08
### Update License

- [EULA License](https://github.com/app-generator/license-eula): Free, Basic, Company

## [1.0.1] 2021-02-07
### Improvements 

- Bump UI: [Jinja AdminLTE](https://github.com/app-generator/jinja-adminlte/releases) v1.0.1
- Bump Codebase: [Django Dashboard](https://github.com/app-generator/boilerplate-code-django-dashboard/releases) v1.0.4

## [1.0.0] 2020-07-16
### Initial Release

- Codebase - [Django Dashboard Boilerplate](https://github.com/app-generator/boilerplate-code-django-dashboard) v1.0.2
- Bump UI - AdminLTE v3.1.0 / buid timestamp 2020-07-13
- [Jinja2 AdminLTE](https://github.com/app-generator/jinja2-adminlte) v1.0.0
