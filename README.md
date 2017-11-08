RAILS TESTING BOILERPLATE:

### In Terminal

```
rails generate rspec:install
rails g rspec:model user
rails g rspec:controller users
rails stats

# Run Tests
rspec

# Run tests of specific file and line
# where 20 is the line of spec that you want to run
rspec spec/models/user_spec.rb:20
```