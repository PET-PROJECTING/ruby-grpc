### Jira ticket
[<task number>](https://jira.teladoc.net/browse/<task number>)
<!-- where <task number> looks like P360-1000, DM-1000 etc. -->
<!-- Provide links to related tickets, e.g. Content, DM or others if any -->

### What was done
<!-- Describe briefly what was done -->

- Added service Foo
- Added logic Bar
- Refactored Baz
- Changed Qux

### Feature toggle
<!-- Use this section if toggle's added otherwise delete -->

```ruby
# Activation
$rollout.activate(:toggle_name)
# Setting feature data
$rollout.set_feature_data(:toggle_name, { foo: 'bar' })
```
- [ ] Describe toggle in [Docs](https://confluence.teladoc.net/display/TDOC/Feature+Toggle) (mark when done)

### Demo
<!--  Use next section for regular PR otherwise delete -->
<!--  Cover all possible scenarios and cases -->

#### Scenario #1
<!-- Video recording/screenshots -->
#### Scenario #2
<!-- Video recording/screenshots -->
#### Scenario #N
<!-- Video recording/screenshots -->

<!-- Use this section for BUG fixes otherwise delete -->
#### Before fix
<!-- Video recording/screenshots -->
#### After fix
<!-- Video recording/screenshots -->

### Tests
<!-- Run whole set of unit tests for service/module you've affected in any way -->
#### BE
<!-- Screenshots -->
#### FE
<!-- Screenshots -->
