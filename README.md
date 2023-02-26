# Sapphire

An UI library for Love2D. (Inspired in Flutter)

## YueScript?

I coded this library in YueScript, it's a language that compiles to Lua. You can use this library in a YueScript project or a normal Lua project too

The Lua files of this project will be at `build/` directory *(currently non-existent)* and the YueScript files will be at `src/` folder 

## Example

```moonscript

Center = require('Sapphire.Center')
Rectangle = require('Sapphire.Rectangle')

-- The main component
root = Center(Rectangle())

-- Explanation:
-- The 'Center' component takes a child in make it on the center of its box.
-- Since we passed the Rectangle to the Center as the child, the Rectangle will be on the center of the screen

love.draw = ->
    -- Use '.' not '\' or ':'
    root.draw()

```

## Status

For now this project is just experimental and you shouldn't use it for big projects. I didn't bug check it yet. If you find some bug you can send it to 'Issues'

**Update**: This project is still experimental but I made some big advancements. I'm experimenting things like https request so this project could be used for more advanced stuff. I call this project phase as *writing examples and fixing bugs* also need to create more components as the projects grow more and more.

## Documentation

Still on progress.
