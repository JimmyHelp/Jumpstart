# Jumpstart

Jumpstart is a library for Figura avatars that adds a bunch of functions to make scripting easier for new users.

This script does not need to be required to be used.

For full descriptions of how the functions work, see [the website](https://www.notion.so/jimmyhelp/Jumpstart-Lib-297fbe64a79d49309c75d6356eda35e5).

# Additions:

## Player API
- player:isWalking()
- player:isIdling()
- player:isCrawling()
- player:isSwimmingInWater()
- player:isSitting()
- player:isGrounded()
- player:isMovingBackwards()
- player:isMovingRight()
- player:isMovingLeft()
- player:isTurningRight()
- player:isTurningLeft()
- player:isSwingingRightArm()
- player:isSwingingLeftArm()
- player:isTargetingBlock(range)
- player:isTargetingEntity(range,living)
- player:getHandItem(hand)
- player:getRightItem()
- player:getLeftItem()
- player:getHelmetItem()
- player:getChestplateItem()
- player:getLeggingsItem()
- player:getBootsItem()

These functions are only true for a single tick

- player:wasHurt()
- player:firedbow()
- player:firedCrossbow()
- player:blockedDamage()
- player:launchedFirework()
- player:threwPotion()

These functions are synced by the script via pings, if you use them

- player:isFlying()
- player:getStatusEffects()
- player:getScreen()

## ItemStack
- ItemStack:isLoadedCrossbow()

## Sounds API
- sounds:replaceSound(soundID,replacement,range)

## LivingEntity API
- livingEntity:getHandItem()
- livingEntity:getRightItem()
- livingEntity:getLeftItem()

## Entity API
- entity:getHelmetItem()
- entity:getChestplateItem()
- entity:getLeggingsItem()
- entity:getBootsItem()
- entity:isGrounded()
