### 👋 &nbsp;Hi there, I'm Luismi Bautista, glad to see you here

```ruby
class AwesomeProfile
  def initialize(profile:)
    @profile = profile
  end

  def to_s
    ["",
     "######################################",
     "   Here we have an awesome profile!   ",
     "######################################",
     "",
     profile.map { |title, description| "#{title}: #{description}" },
     "",
     ""].join("\n")
  end


  attr_accessor :profile
end

lmbautista_profile = {
  "🤓 Full name" => "Luis Miguel Bautista",
  "🤖 Skills" => "Software engineer and technology enthusiast that enjoy learning, teaching and coding",
  "🌴 Hobbies" => "I love running, nature, my 🦊, books, food and cooding",
  "💻 Current role" => "Ruby backend engineer",
  "🚀 Current position" => "Currently working as Backend developer in Jobandtalent having fun with awesome challenges"
}

puts AwesomeProfile.new(profile: lmbautista_profile).to_s
```

### ⚡&nbsp; Tech stack

<p align="center">
  <a href="#"><img src="https://img.shields.io/badge/Ruby-9B111E?style=for-the-badge&logo=ruby&logoColor=white"></a>
  <a href="#"><img src="https://img.shields.io/badge/Rails-white?style=for-the-badge&logo=rubyonrails&logoColor=9B111E"></a>
  <a href="#"><img src="https://img.shields.io/badge/react-20232A?style=for-the-badge&logo=react&logoColor=61DAFB"></a>
  <a href="#"><img src="https://img.shields.io/badge/javascript-white?style=for-the-badge&logo=javascript&logoColor=red"></a>
  <a href="#"><img src="https://img.shields.io/badge/jQuery-white?style=for-the-badge&logo=jquery&logoColor=78cff5"></a>
  <a href="#"><img src="https://img.shields.io/badge/bootstrap-563d7c?style=for-the-badge&logo=bootstrap&logoColor=white"></a>
  <a href="#"><img src="https://img.shields.io/badge/html5-orange?style=for-the-badge&logo=html5&logoColor=white"></a>
  <a href="#"><img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"></a>
  <a href="#"><img src="https://img.shields.io/badge/mysql-00758F?style=for-the-badge&logo=mysql&logoColor=white"></a>
  <a href="#"><img src="https://img.shields.io/badge/postgresql-0064a5?style=for-the-badge&logo=postgresql&logoColor=white"></a>
  <a href="#"><img src="https://img.shields.io/badge/docker-0db7ed?style=for-the-badge&logo=docker&logoColor=white"></a>
  <a href="#"><img src="https://img.shields.io/badge/github-white?style=for-the-badge&logo=github&logoColor=6e5494"></a>
  <a href="#"><img src="https://img.shields.io/badge/vstudio-20232A?style=for-the-badge&logo=visual-studio&logoColor=0078d7"></a>
  <a href="#"><img src="https://img.shields.io/badge/aws-20232A?style=for-the-badge&logo=amazon&logoColor=FF9900"></a>


### 📮&nbsp; Contact

Find out more about me & feel free to connect with me here:

<p align="center">
 <a href="https://www.linkedin.com/in/luis-miguel-bautista-fraile-259a9499/">
  <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
 </a>
 <a href="https://twitter.com/ipep0n">
  <img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" />
 </a>
 <a href="https://www.instagram.com/pepothon/?hl=es">
  <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" />
 </a>
  <a href="mailto:lmiguelbautista@gmail.com">
  <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
 </a>

