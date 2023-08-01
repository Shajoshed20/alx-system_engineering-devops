# 0x06. Regular expression

## Background cotext :page_with_curl:

For this project, you have to build your regular expression using Oniguruma, a regular expression library that which is used by Ruby by default. Note that other regular expression libraries sometimes have different properties.

Because the focus of this exercise is to play with regular expressions (regex), here is the Ruby code that you should use, just replace the regexp part, meaning the code in between the //:

sylvain@ubuntu$ cat example.rb
#!/usr/bin/env ruby
puts ARGV[0].scan(/127.0.0.[0-9]/).join
sylvain@ubuntu$
sylvain@ubuntu$ ./example.rb 127.0.0.2
127.0.0.2
sylvain@ubuntu$ ./example.rb 127.0.0.1
127.0.0.1
sylvain@ubuntu$ ./example.rb 127.0.0.a

## Tasks :heavy_check_mark:

* Task 0 - The regular expression must match School
        - Using the project instructions, create a Ruby script that accepts one argument and pass it to a regular expression matching method

* Task 1 - Find the regular expression that will match the above cases
        - Using the project instructions, create a Ruby script that accepts one argument and pass it to a regular expression matching method

* Task 2 - Find the regular expression that will match the above cases
        - Using the project instructions, create a Ruby script that accepts one argument and pass it to a regular expression matching method

* Task 3 - Find the regular expression that will match the above cases
        - Using the project instructions, create a Ruby script that accepts one argument and pass it to a regular expression matching method

* Task 4 - Find the regular expression that will match the above cases
        - Using the project instructions, create a Ruby script that accepts one argument and pass it to a regular expression matching method
        - Your regex should not contain square brackets

* Task 5 - The regular expression must be exactly matching a string that starts with h ends with n and can have any single character in between
        - Using the project instructions, create a Ruby script that accepts one argument and pass it to a regular expression matching method

* Task 6 - The regular expression must match a 10 digit phone number

* Task 7 - The regular expression must be only matching: capital letters
