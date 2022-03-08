# README

The code in this repository is intended to accompany the tutorial originally published [here](https://www.colby.so/posts/toggling-view-layouts-with-kredis-and-rails).

This application is a demonstration of using Kredis with Rails to toggle between a list and a card view, with a little bit of Turbo Frames and Tailwind to tie it all together.

To run this application locally, clone the repository and then:
```
bundle install
rails db:create db:migrate
bin/dev
```

Afer starting the server, head to `/players`.

Check the final implementation in the `final` branch of this repository. The `main` branch is intentionally left at the initial commit for those who wish to code along with the tutorial.
