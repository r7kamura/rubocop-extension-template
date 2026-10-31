# rubocop-extension-template

> [!NOTE]
> This project is archived because I no longer actively use it, and there seems to be no recent activity from other users either. If you are still using it and would like to take over maintenance, contact me somewhere.

Custom [RuboCop](https://github.com/rubocop/rubocop) extension template.

## Usage

1. [Use this template](https://github.com/r7kamura/rubocop-extension-template/generate) to create a repository
2. Rename gem name from `my_extension` to your own
3. Run `bin/setup`
4. Add your custom cop by running `bundle exec rake new_cop[Foo/Bar]`
5. Edit `lib/rubocop/cop/foo/bar.rb`

## License

The template is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).

Copyright (c) 2022 Ryo Nakamura
