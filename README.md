plantingtheswag
VISUAL
ComputerCraftEdu:turnRight 2

ComputerCraftEdu:variable x
ComputerCraftEdu:equalTo
ComputerCraftEdu:number 1000

ComputerCraftEdu:repeat
ComputerCraftEdu:variable x
ComputerCraftEdu:do

ComputerCraftEdu:if
ComputerCraftEdu:getItemCount
ComputerCraftEdu:notEqualTo
ComputerCraftEdu:number 0
ComputerCraftEdu:then

ComputerCraftEdu:if
ComputerCraftEdu:inspectDown
ComputerCraftEdu:equalTo
ComputerCraftEdu:block "minecraft:grass"
ComputerCraftEdu:then
ComputerCraftEdu:select
ComputerCraftEdu:number 16
ComputerCraftEdu:place

ComputerCraftEdu:while
ComputerCraftEdu:inspect
ComputerCraftEdu:equalTo
ComputerCraftEdu:block "minecraft:sapling"
ComputerCraftEdu:do
ComputerCraftEdu:turnLeft
ComputerCraftEdu:turnLeft

ComputerCraftEdu:if
ComputerCraftEdu:inspectDown
ComputerCraftEdu:equalTo
ComputerCraftEdu:block "minecraft:grass"
ComputerCraftEdu:then
ComputerCraftEdu:select
ComputerCraftEdu:number 16
ComputerCraftEdu:place

ComputerCraftEdu:while
ComputerCraftEdu:inspect
ComputerCraftEdu:equalTo
ComputerCraftEdu:block "minecraft:sapling"
ComputerCraftEdu:do
ComputerCraftEdu:turnRight
ComputerCraftEdu:moveForward
ComputerCraftEdu:moveForward
ComputerCraftEdu:turnRight

ComputerCraftEdu:end

ComputerCraftEdu:end

ComputerCraftEdu:end

ComputerCraftEdu:end

ComputerCraftEdu:end

ComputerCraftEdu:end
