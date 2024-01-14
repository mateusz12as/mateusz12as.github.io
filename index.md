---
layout: default
---


# Krótki opis
Obecnie jestem studentem AGH w Krakowie. Wraz z kolegami pracujemy nad projektem SPACE SHOOTER. Będzie to gra rozgrywająca się w kosmicznej przestrzni. Gracz będzie statkiem kosmicznym i będzie walczyl z przeciwnikami










### Obrazek

![Statk_kosmiczny](https://play-lh.googleusercontent.com/7tZaYZzRqxHToU5ToDUfxhe-c7YhlPpV1AcdxBPi9znbuDjGSMcyRQ_fphs4yJy1tQ)




# Fragment kodu
```
class Projectile(pygame.sprite.Sprite):
    def __init__(self, coord):
        super().__init__()
        self.image = pygame.image.load("img/Bullet.png")
        self.rect = self.image.get_rect()
        self.rect.center = coord
        self.velocity = 8
        self.damage = 1
```

