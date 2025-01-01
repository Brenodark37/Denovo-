function createBrenoHub()
    if love and love.window then
        love.window.setTitle("BRENO HUB")
    end

    if love and love.graphics then
        love.graphics.setBackgroundColor(0, 0, 0)
    end
end

function drawBrenoHub()
    if love and love.graphics then
        love.graphics.setColor(1, 1, 1)
        love.graphics.print("Bem-vindo ao BRENO HUB!", 100, 100)
    end
end

if love then
    function love.load()
        createBrenoHub()
    end

    function love.draw()
        drawBrenoHub()
    end
end
