# Sapphire

An UI library for Love2D. (Inspired in Flutter)

## YueScript?

I coded this library in YueScript, it's a language that compiles to Lua. But you can use the library in a YueScript project or a regular Lua project too.

The Lua files of the project will be at build/lua and the YueScript files will be at src/ folder

## Example

```moonscript

Center = require('Sapphire.Center')
Rectangle = require('Sapphire.Rectangle')

-- The main component
root = Center(Rectangle())

-- Explanation:
-- The 'Center' component takes a child in make it on the center of its box.
--  Since we passed the Rectangle to the Center as the child, the Rectangle will be on the center of the screen

love.draw = ->
    -- Use '.' not '\' or ':'
    root.draw()

```

## Status

For now this project is just experimental and you shouldn't use it for big projects. I didn't bug check it yet. Any bug reports send it to 'Issues'

## Documentation

Still on progress. But there are some doc files in the project source.