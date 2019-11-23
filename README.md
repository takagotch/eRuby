### eRuby
---
http://www2a.biglobe.ne.jp/~seki/ruby/erb.html

https://docs.ruby-lang.org/ja/latest/library/erb.html

```.erb
<% 3.times do |n| - %>
% n = 0
  <%- m = 0 %>*
*<%- m = 0 %>
<% end -%>
```

```rb
require 'erb'

template = ERB.new <EOF
<%#-*- conding: Big5 -*-%>
  __ENCODING__ is <%= __ENCODING__ %>.
EOF
puts template.result # => __ENCODING__ is Big5
```

```
```


