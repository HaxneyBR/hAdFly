#hAdFly
A New Way To Fly in Minecraft!

#hAdFly( english version )

- Hey, you! Yeah, Yourself. Are you creating an rpg or something? Well, this plugin Will help you.

* About the plugin: In this plugin the player can use a specific chestplate to be able to fly!
The Divine Breastplate. 

? How can i use?

Simple: 

 The plugin active the **PlayerChatEvent**
 So when the player send in chat: @adfly the plugin Will a line
 To help you.

public function PlayerChatEvent(PlayerChatEvent $event) {

  $p = $event->getPlayer();

  $args = explode(' ', $event->getMessage());

  if ($args[0] === '@adfly') {
  // do something 
    }
  }
