---
title: Migration
category: rails
---

## Migration

### Migration to add column

`rails generate migration AddPartNumberToProducts part_number:string`

### Run migration

`rake db:migrate`

### Rollback a step

`rake db:rollback`

`rake db:rollback STEP=3`

