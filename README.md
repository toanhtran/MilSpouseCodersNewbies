# MilSpouseCodersNewbies

Want to connect with other military spouses learning software development? MilSpouseCodersNewbies helps you ask questions, connect, and learn from a large military community.

## Table of Contents
* [Technologies Used](#technologies)
* Wistia API
* How to use MilSpouseCodersNewbies
* Register for an account

## <a name="technologies"></a> Used
* Back-end: Ruby, Rails
  * Ruby version 2.4.2
  * Rails version 5.1.4

* Front-end: Materialize framework [Materializecss.com](http://materializecss.com/)
  * Materialize version 0.100.2

* API: Google Maps, Wistia [Wistia] (https://wistia.com)

* [Installation instructions](#installation)

## <a name="installation"></a>Installation
To run MilSpouseCodersNewbies

Install Ruby Version Manager (RVM) [RVM](https://rvm.io/)
```
$ \curl -sSL https://get.rvm.io | bash -s stable

```
Download Ruby version 2.4.2
```
$ rvm install ruby-2.4.2

```


Download Rails version 5.1
```sh
$ rvm use ruby-2.4.1@rails5.1 --create

```

Check that you have the latest version of Ruby and Rails
```
$ ruby -v
Ruby 2.4.2
$ rails -v
Rails 5.1.0

```
Check your RubyGems
```
$ gem -v
2.6.12
```
If you don't see the gem version 2.6.12
Upgrade your Ruby Gems
```
$ gem update --system

```
Install Bundler
```
$ gem install Bundler

```

Install Nokogiri
```
$ gem install nokogiri

```

Clone or fork this repo:
```
$ git@github.com:toanhtran/MilSpouseCodersNewbies.git
```


Run the app:
```
$ rails server

```

You can now navigate to localhost:3000 [localhost](http://localhost:3000) to access MilSpouseCodersNewbies

Use Control + C to stop the server.



## Author
[ToAnh Tran](https://www.linkedin.com/in/toanhtran/) is a Full Stack Web Developer living in San Diego, CA.  If you have any questions about MilSpouseCodersNewbies, feel free to reach out toanh.t.tran@gmail.com
