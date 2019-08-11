### clint
---
https://github.com/kennethreitz/clint

```py
fro clint.textui import puts, indent
puts('not indented text')
with indent(4):
  puts('indented text')

puts('not indented text')
with indent(4, quote=' >'):
  puts('quoted text')
  puts('pretty cool, eh?')


from clint.textui import colored, puts
puts(colored.red('red text'))

clint.piped_in()

from clint import arguments
args = argumets.Args()
args.get(0)

from clint import resources
resources.init('Company', 'AppName')
resources.user.write('config.ini', file_contents)

from clint.textui import prompt, validators
path = prompt.query('Installation Path', default='/usr/local/bin', validators=[validators.PathValidator()])
```

```sh
pip install clint
easy_install clint
```

```
```


