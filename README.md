# Ruby Strings Party

<img src="https://s3.amazonaws.com/after-school-assets/hogwarts.jpg" width="400px" align="right" hspace="10">
puts "What's your #{party_name}?"
puts "What's your #{guest_name}?"
puts "What's your #{date}?"
puts "What's your #{time}?"
puts "What's your #{host_name}?"
* guest_name = gets.chomp 

* party_name = gets.chomp
* date = gets.chomp
* time = gets.chomp
* host_name = gets.chomp


...and then prints out custom invitations that look something like this:

```
Dear #{guest_name},

You are cordially invited to the #{party_name} on #{date} at #{time}. Please RSVP no later than October 30.

Sincerely,

#{host_name}
```
