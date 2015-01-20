# tiptip-rails
This gem just includes [TipTip jQuery plug-in](https://github.com/drewwilson/TipTip) as an asset in the Rails 3.1 (or newer) asset pipeline.

The current version in the gem is TipTip 1.3

## Installation

Add the gem to the Gemfile

    gem "tiptip-rails", "~> 1.0.0"

## Usage

In your JavaScript manifest (e.g. `application.js`)

    //= require tipTip

In your Stylesheet manifest (e.g. `application.css`)

    *= require tipTip

## Licensing

TipTip, which makes up the majority of this gem, has [its own licensing](https://github.com/drewwilson/TipTip).

The gem itself is released under the MIT license
