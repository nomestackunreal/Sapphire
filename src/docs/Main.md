# Getting Started

Copy the Sapphire folder of this repository to your project, you should put it in your directory root. Do not put it in a different folder.

```lua
-- Wrong
'./libs/Sapphire'
-- Correct
'./Sapphire'
```

(For now it's like that but as the project develops more I will eventually fix this.)

# Components

Every file of this library is a component so, `Sapphire.Button` is a component, when you require it, a function is returned. With that function you will be able to create your instances.

Example:
```moonscript
Button = require('Sapphire.Button')

popupButton = Button()

love.draw = ->
    popupButton.draw()
```

This code will create a new instance of a Button.

