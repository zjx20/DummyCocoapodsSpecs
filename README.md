# DummyCocoapodsSpecs
This repo is used for getting rid of the huge master specs when you don't need it. For example:

```ruby
source "https://github.com/zjx20/DummyCocoapodsSpecs.git"

platform :ios, '7.0'

target 'MyProject' do
  pod 'MyPod', :path => 'path/of/the/pod'
end
```
