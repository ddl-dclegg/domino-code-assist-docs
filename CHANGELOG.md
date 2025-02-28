v0.0.24
====
- fix: edit buttons outside viewport when snippet list is long

v0.0.23
====
- feat: add reload button for snippets
- feat: edit snippets from LCA
- feat: builtin snippets

v0.0.22
====
- feat: user replaceable dataframe in the app

v0.0.21
=======
- feat: crossfilter option for plots
- feat: search for snippets in external git repositories
- fix: app start from failed state is not working
- feat: support for 4.x
- feat: option to select demo data

v0.0.20
=======
- feat: code snippets
- fix: handle quotes in string values of filter correctly
- fix: replace auto quoting with a switch

v0.0.19
=======
- fix: datasets directory is not always present
- fix: generate only valid python variable names in transformations

v0.0.18
=======
- fix: deploy doesn't work correctly if a project contains a shared project
- fix: deploy app status incidentally stuck in error state
- fix: require Plotly>=4 so plotly.express is included

v0.0.17
=======
- feat: WYSIWYG editor for markdown
- feat: new UX
- fix: S3 datasource name is hardcoded
- fix: show app doesn't work on other domains

v0.0.14
=======
- feat: remove loader selection from deployer

v0.0.13
=======
- feat: support offline environments

v0.0.12
=======
- fix: restore directory on 'edit' load file.
- fix: undo button not disabled when no undo available
- feat: store undo/redo state, so it is available again when editing
- fix: no columns selectable on erroneous transformation line
- fix: first transformation line can not be deleted
- feat: auto quote filter values for string columns
- fix: selecting a different dataframe the second time in the transformation panel doesn't show the right dataframe
- feat: Add option to use markdown cells and dataframes in app builder

v0.0.11
=======
- fix: incompatibility with solara 0.2.0

v.0.0.10
========
- fix: Generate correct code for all config parameters
- fix: Remove unnecessary scrollbar in preview window
- fix: Deployer: handle "Failed" app state correctly
- fix: Deployer: make it possible to start app when an app is not yet created
- fix: Deployer: use correct name for the plain loader setting

v0.0.9
======
- fix: Edit option is working again

v0.0.8
======
- App configurator with positioning and resizing
- App preview
- Deploy app

v0.0.7
=====
- SQL code editor with auto-complete for redshift and snowflake
- S3 support
- Get available data sources from the domino API

v0.0.6
=====
- Redshift support

v0.0.5
=====
- rename extension button to Low Code Assistant™
