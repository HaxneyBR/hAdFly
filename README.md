• hAdFly
A New Way To Fly in Minecraft!

# hAdFly( english version )

- Hey, you! Yeah, Yourself. Are you creating an rpg or something? Well, this plugin Will help you.

* About the plugin: In this plugin the player can use a specific chestplate to be able to fly!
The Divine Breastplate. 

? How can i use?

Simple: 

 The plugin active the **PlayerChatEvent**
 So when the player send in chat: @adfly the plugin help you.

```
public function PlayerChatEvent(PlayerChatEvent $event) {

  $p = $event->getPlayer();

  $args = explode(' ', $event->getMessage());

  if ($args[0] === '@adfly') {
  // do something 
    }
  }
```
• hAdFly( versão em português)
Uma nova maneira de voar no Minecraft!

- Ei você! Sim, você mesmo. Você está criando um rpg ou algo assim? Bem, este plugin irá ajudá-lo.
* Sobre o plugin: Neste plugin o jogador pode usar um peitoral específico para poder voar!
O Peitoral Divino. 

? Como eu uso? 

Simples:

 O plugin ativa o **PlayerChatEvent**
 Então quando o jogador manda no chat: @adfly o plugin vai ajudá-lo.

public function PlayerChatEvent(PlayerChatEvent $event) {

  $p = $event->getPlayer();

  $args = explode(' ', $event->getMessage());

  if ($args[0] === '@adfly') {
  // do something 
    }
  }
