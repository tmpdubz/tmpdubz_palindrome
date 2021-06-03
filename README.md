# TmpdubzPalindrome

`tmpdubz_palindrome` is a sample Ruby gem created for learning purposes in the online tutorial [Learn Enough Ruby to Be Dangerous](https://www.learnenough.com/ruby-tutorial)

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'tmpdubz_palindrome'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install tmpdubz_palindrome

## Usage

`tmpdubz_palindrome` adds a `palindrome?` method to the `String` class, and can be used as follows:

```
$ irb
>> require 'tmpdubz_palindrome'
>> "honey badger".palindrome?
=> false
>> "deified".palindrome?
=> true
>> "Able was I, ere I saw Elba.".palindrome?
=> true
>> phrase = "Madam, I'm Adam."
>> phrase.palindrome?
=> true
```
