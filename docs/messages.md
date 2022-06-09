# Messages System!

DiscordSRVUtils Uses a Smart Messages System. 

## How to set any Discord Message in the Plugin

Any Message in the configurations that is a discord message uses the same way to customize it. If you want a normal Message, write the string normally, but if you want an embed, add the message embed to messages folder. Extension is json. then set the message to "embed:name" do not put json extension.

## Placeholders

Depends on the message, for example afk message have "player" and you can use anything after it like "[player.name]". Must be a get method in the Player class, this is an example, other messages like welcome message have "user", "member" and "guild". Any of these must have [] and a .something (as i said needs to have a get method in the class)

[Join Support if you don't understand this](https://discordsrvutils.xyz/support)

# PAPI

PAPI is always supported if you have it installed. the player is not set if its not a player-related message, what are player-related messages? Just like AFK Messages


# SpEL

- SpEL is supported too. Read how to use it: 
 * <a href="https://docs.spring.io/spring/docs/4.2.x/spring-framework-reference/html/expressions.html" target="blank">https://docs.spring.io</a> 
 * <a href="https://dzone.com/articles/learn-spring-expression-language-with-examples" target="blank">https://dzone.com</a> 


# Testing
You can test your changes using `/testmessage <message name>`