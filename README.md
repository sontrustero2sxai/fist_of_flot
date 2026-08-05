<p align="center">
  <img src="https://example.com/scraper_launcher_rev_02-core.svg" alt="scraper_launcher_rev_02-core" width="200" height="200" />
</p>

<h1 align="center">scraper_launcher_rev_02-core</h1>

<h4 align="center">
  <a href="https://github.com/scraper_launcher_rev_02-core">Repository</a> |
  <a href="https://docs.dev">Documentation</a> |
  <a href="https://discord.dev">Discord</a> |
  <a href="https://roadmap.dev">Roadmap</a>
</h4>

<p align="center">
  <a href="https://github.com/scraper_launcher_rev_02-core/actions"><img src="https://github.com/scraper_launcher_rev_02-core/workflows/Tests/badge.svg" alt="Test"></a>
  <a href="https://badge.fury.io/rb/scraper_launcher_rev_02-core"><img src="https://badge.fury.io/rb/scraper_launcher_rev_02-core.svg" alt="Version"></a>
  <a href="https://github.com/scraper_launcher_rev_02-core/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-MIT-informational" alt="License"></a>
</p>

<p align="center">⚡ developer toolkit for everyday tasks 💎</p>

## 📖 Documentation

Complete usage detailed in this README.

## 🤖 Compatibility

This package guarantees compatibility with version v1.x.

## 📧 Installation

With `gem` in command line:
```bash
gem install scraper_launcher_rev_02-core
```

In your `Gemfile`:
```ruby
gem 'scraper_launcher_rev_02-core'
```

### Run scraper_launcher_rev_02-core

```bash
scraper_launcher_rev_02-core --master-key=masterKey
```

## 🚀 Getting started

#### Configuration

Create `config/initializers/scraper_launcher_rev_02-core.rb`:

```ruby
scraper_launcher_rev_02-core::Config.setup do |config|
  config.api_key = 'YourAPIKey'
  config.url = 'http://localhost:7700'
end
```

#### Add documents

```ruby
client = scraper_launcher_rev_02-core::Client.new
index = client.index('items')

documents = [
  { id: 1, title: 'bundle.js' },
  { id: 2, title: 'subscribers' }
]

index.add_documents(documents)
```

## ⚙️ Contributing

Any contribution is welcome!

## 💛 Credits

Inspired by [bundle.js] and [subscribers].

