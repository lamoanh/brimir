Development notes
=================

based in: https://github.com/ivaldi/brimir

## Deploy

```
bundle install --without postgresql
rake db:schema:load

bundle exec rails s # start server
```

## Develop

- Commit viết theo formet: `#taskID + mô tả về thay đổi`
    Ví dụ: `#3 add development notes`.

- Branch đặt tên theo format: `taskID + mô tả branch`
    Ví dụ: `3-dev-note`