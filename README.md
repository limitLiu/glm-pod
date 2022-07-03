# glm-pod

## Usage

U can clone it into your project.

```bash
$ cd <Your Project Name>
$ git clone https://github.com/limitLiu/glm-pod.git specs
```

```ruby
platform :ios, '14.0'

project '<Your Project Name>'

target '<Your Target Name>' do
  
  use_frameworks!
  
  # use local file
  pod 'glm', :podspec => './specs/glm.podspec.json'

end
```

