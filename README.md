# Brakeman-Lightning-Talk
A high level intro to the functionality of the Brakeman Gem for Ruby Apps

Overview:

* "Static Analysis Security Scanner for Ruby on Rails Apps"
* A gem which runs diagnostics on a Rails App, looking for any potential security vulnerabilities
* Brakeman generates a relatively easy to read report, in the terminal, which highlights vulneratbilities, ranked by level of confiedence, bucketed by category of warning (25 categories)
* Brakeman policy is to over report on potential vulnerabilities



Basic useful feature list:

 * Attempts to pinpoint the issue through File Name and Line Number
 * Options of Running Targeted / Non-Default tests



Adding the Gem to Gemfile:

```ruby 
gem "brakeman", :require => false
```

### Documentation:

* [Brakeman Homepage](http://brakemanscanner.org/) Checkout their homepage for a quick overview 
* [Confidence Levels of Risks](http://brakemanscanner.org/docs/confidence/) Explanation of the Confidence levels used in the reports
* [Warning Types](http://brakemanscanner.org/docs/warning_types/) Full list and description of warning types used
