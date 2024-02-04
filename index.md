---
layout: default
---

# Ruby on Rails
## ActiveRecord
This is the ORM bundled in rails gem, and rails is a open soure MVC based web development framework
```ruby
  class User < ApplicationRecord
    self.table_name = 'devise_users'

    def full_name
      "#{self.first_name} #{self.last_name}"
    end

    def find_by_name(name)
      User.where(name: name)
        .first
    end
  end
```

# My Favorite open source repos
* [numpy](https://github.com/numpy/numpy)
* [rails](https://github.com/rails/rails)
* [tensorflow](https://github.com/tensorflow/tensorflow)
* [pandas](https://github.com/pandas-dev/pandas)