# MyApp

## Repro

1. Go to `/users`
1. Click "New user"
1. Without touching any form fields, click "Save"
1. Inspect error tag spans, there are non with the `phx-no-feedback` class

### Walkthrough

https://user-images.githubusercontent.com/206066/193598106-4bf45040-50a4-43ec-967f-8b5608d1c17c.mov

## Phoenix 

To start your Phoenix server:

  * Install dependencies with `mix deps.get`
  * Create and migrate your database with `mix ecto.setup`
  * Start Phoenix endpoint with `mix phx.server` or inside IEx with `iex -S mix phx.server`

Now you can visit [`localhost:4000`](http://localhost:4000) from your browser.

Ready to run in production? Please [check our deployment guides](https://hexdocs.pm/phoenix/deployment.html).

## Learn more

  * Official website: https://www.phoenixframework.org/
  * Guides: https://hexdocs.pm/phoenix/overview.html
  * Docs: https://hexdocs.pm/phoenix
  * Forum: https://elixirforum.com/c/phoenix-forum
  * Source: https://github.com/phoenixframework/phoenix
